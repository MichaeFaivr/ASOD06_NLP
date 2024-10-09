# Challenge - Preprocessing pipeline

![](https://media.ouest-france.fr/v1/pictures/fe9603bace85f5c3339acb605cb31894-17133782.jpg?width=1400&client_id=eds&sign=9fb46757bc793cfe75ca6a14462ccbf26bbff31d9a7ce55d426c03ae31da2465)

## Objectives

First, the goal is to optimize the time to preprocessing text data with Spacy.
Second, classify french tweets between negative and positive tweets. 

## Guidelines

🚰 The preprocessing of texts can be time-consuming and costly for your computer, especially if your dataset is large. Spacy has developed a [feature](https://spacy.io/usage/processing-pipelines) to implement a text pre-processing pipeline to optimise the process.

To measure the time of preprocessing we will use tqdm package to display a progress bar.

## Dataset

📥 In this exercise we will use a dataset of 1.5 million French tweets and their sentiment (negative and positive) from Kaggle : https://www.kaggle.com/hbaflast/french-twitter-sentiment-analysis

To avoid any Github issue, don't forget to store the dataset in your local `data` folder.
