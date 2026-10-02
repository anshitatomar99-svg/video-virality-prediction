# YouTube Video Virality Prediction

## Project Overview
A machine learning model built to predict whether a YouTube video will go viral based on user engagement metrics. This project analyzes a dataset of trending YouTube videos and uses classification algorithms to identify the key drivers of virality.

## Technologies Used
* **Python**
* **Pandas** (Data manipulation and feature engineering)
* **Scikit-Learn** (Random Forest Classifier)
* **Matplotlib** (Data visualization)

## Dataset
The dataset contains records of top-trending YouTube videos, including metrics such as views, likes, dislikes, and comment counts. The target variable (`is_viral`) was engineered by classifying videos with view counts above the dataset median as viral.

## Key Results
* Achieved **88.46% accuracy** in predicting virality using only post-publication engagement metrics (excluding direct view counts to prevent data leakage).
* **Feature Importance Analysis** revealed that `dislikes` and `likes` were the strongest predictors of a video's trending potential, significantly outranking the `comment_count`.
