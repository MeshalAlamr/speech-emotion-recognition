# speech-emotion-recognition
SDAIA Bootcamp project 5 - Deep Learning.

This project aims to predict emotions from speech signals. The goal of this project is to help school consultancies analyze emotions of children to help them intervene in case a child shows early signs of mental illness.

## Table of Contents

- [MVP](#mvp)
- [Dataset](#data)
- [Analysis and Results](#project)
- [Presentation](#presentation)
- [Authors](#authors)



## MVP <a name="mvp" />
#### The project MVP can be found [here](https://github.com/MeshalAlamr/speech-emotion-recognition/blob/main/MVP).

## Dataset <a name="data" />
#### The dataset of this project is a merged dataset from four different datasets which are CREMA, SAVEE, TESS and RAVDESS. The dataset containing all four datasets can be found [here](https://www.kaggle.com/dmitrybabko/speech-emotion-recognition-en) on Kaggle. After loading each dataset and combining the datasets we end up with 12,162 rows. 

## Analysis and Results <a name="project" />
#### The project's notebook is split into two parts.
#### Part 1 includes loading the data, exploring it, doing some data augmentation and finally extracting the features. It can be found [here](https://github.com/MeshalAlamr/speech-emotion-recognition/blob/main/speech-emotion-recognition-1.ipynb). <b> If you'd like to replicate the results from part 1 then the Pickle file for the final dataframe can be downloaded [here](https://drive.google.com/file/d/1iKRgJXRL2roULKN_BzrotG-bRqtflznK/view?usp=sharing) on Google Drive. </b>
#### Part 2 is all about modelling using the extracted features from part 1. It can be found [here](https://github.com/MeshalAlamr/speech-emotion-recognition/blob/main/speech-emotion-recognition-2.ipynb).

#### Distribution of emotions of the combined dataset:
![chrome_7u2LRkIY5G](https://user-images.githubusercontent.com/68873733/143720982-9f146529-dcdc-4577-ac0f-b415a5a10781.png)

#### Results after training the model:
#### We obtained an accuraccy of 72.14%.
![chrome_EPSiPHwzt6](https://user-images.githubusercontent.com/68873733/143721121-1f58ce2e-43ca-4468-9d5f-737b21769e2b.png)
![chrome_mjqoFtiz5K](https://user-images.githubusercontent.com/68873733/143721092-aa582d8c-c0dd-4128-a370-adec2f18c558.png)


## Presentation <a name="presentation" />
#### The presentation can be found [here](https://github.com/MeshalAlamr/speech-emotion-recognition/blob/main/final-presentation.pdf).
#### Please note that the presentation was based off an earlier version of the project so the results differ from what is obtained in the project's notebooks.

## Authors <a name="authors"/>
- ### [Meshal Alamr](https://github.com/MeshalAlamr)
- ### [Norah Alkhalifah](https://github.com/NorahAlkhalifah)

