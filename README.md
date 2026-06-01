# SIT770 Temporal Drift in News Classification

This repository contains the notebook code used for my SIT770 NLP temporal drift experiments.

## Dataset

The experiments use the News Category Dataset from Kaggle:

https://www.kaggle.com/datasets/rmisra/news-category-dataset

The dataset file used in the notebook is:

`News_Category_Dataset_v3.json`

## Task 2.2D

The 2.2D experiment compares:

1. Random-split evaluation
2. Temporal-split evaluation

The aim is to check whether random-split evaluation gives overly optimistic results when the model is tested on future news articles.

## Task 2.3HD

The 2.3HD experiment extends the 2.2D work by testing a recency-aware weighted training method.

The methods compared are:

1. Older-only baseline
2. Simple update baseline
3. Recency-aware weighted method

## Model

The model uses:

- TF-IDF features
- Logistic Regression
- Accuracy and macro-F1 as evaluation metrics

## Note

The dataset is not uploaded in this repository. It can be downloaded from Kaggle using the link above.
