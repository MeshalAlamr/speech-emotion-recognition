## Minimum Viable Product (MVP) of the Deep Learning Project
The goal of this project is to recognize emotion from speech signals. To achieve this, this project uses the Ryerson Audio-Visual Database of Emotional Speech and Song [(RAVDESS) Dataset](https://www.kaggle.com/uwrfkaggler/ravdess-emotional-speech-audio) on Kaggle.

The dataset contains 1440 audio files seperated into 24 actors (12 female, 12 male) each with 60 trials. The speech emotions include: _neutral, calm, happy, sad, angry, fearful, surprise and disgust_.

We read the files of the data and did some EDA using Librosa which is a python package for music and audio analysis. Librosa was used to perform the MFCC feature extraction technique which includes windowing the signal, applying discrete Fourier transform (DCT), taking the log of the magnitude, and then warping the frequencies on a Mel scale, followed by applying the inverse DCT. 

Furthermore, We analyzed the 8 emotions for the first actor and the figure below shows the audio signals for each emotion:

![actor_01_emotions](https://user-images.githubusercontent.com/68873733/142956248-57a2d7e4-9ad2-4c89-9161-1b7a9d6852bc.png)

Currently, we're in the midst of using a convolutional neural network (CNN) model to extract relevant features and train the network.
