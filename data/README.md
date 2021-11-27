### The dataset of this project is a merged dataset from four different datasets which are CREMA, SAVEE, TESS and RAVDESS. The dataset containing all four datasets can be found [here](https://www.kaggle.com/dmitrybabko/speech-emotion-recognition-en) on Kaggle. 

### Below, the description of each dataset is provided, taken from Kaggle.

## Ravdess
Here is the filename identifiers as per the official RAVDESS website:

Modality (01 = full-AV, 02 = video-only, 03 = audio-only).
<br> Vocal channel (01 = speech, 02 = song).
<br> Emotion (01 = neutral, 02 = calm, 03 = happy, 04 = sad, 05 = angry, 06 = fearful, 07 = disgust, 08 = surprised).
<br> Emotional intensity (01 = normal, 02 = strong). NOTE: There is no strong intensity for the 'neutral' emotion.
<br> Statement (01 = "Kids are talking by the door", 02 = "Dogs are sitting by the door").
<br> Repetition (01 = 1st repetition, 02 = 2nd repetition).
<br> Actor (01 to 24. Odd numbered actors are male, even numbered actors are female).

So, here's an example of an audio filename. 02-01-06-01-02-01-12.wav
<br> This means the meta data for the audio file is:

Video-only (02)
<br> Speech (01)
<br> Fearful (06)
<br> Normal intensity (01)
<br> Statement "dogs" (02)
<br> 1st Repetition (01)
<br> 12th Actor (12) - Female (as the actor ID number is even)

## Crema:
The third component is responsible for the emotion label:

SAD - sadness;
<br> ANG - angry;
<br> DIS - disgust;
<br> FEA - fear;
<br> HAP - happy;
<br> NEU - neutral.

## Tess:
Very similar to Crema - label of emotion is contained in the name of file.

## Savee:
The audio files in this dataset are named in such a way that the prefix letters describes the emotion classes as follows:

'a' = 'anger'
<br> 'd' = 'disgust'
<br> 'f' = 'fear'
<br> 'h' = 'happiness'
<br> 'n' = 'neutral'
<br> 'sa' = 'sadness'
<br> 'su' = 'surprise'
## 
### After loading each dataset and combining the datasets, we end up with 12,162 rows.
