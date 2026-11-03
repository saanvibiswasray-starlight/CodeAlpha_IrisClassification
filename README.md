# CodeAlpha_IrisClassification
## Overview
This repository contains the code for the **Iris Flower Classification** project completed as part of the CodeAlpha Data Science Internship. The objective is to train a machine learning model to classify Iris flower species (*setosa*, *versicolor*, *virginica*) based on physical measurements[span_0](start_span)[span_0](end_span).

## Project Workflow
1. **Dataset Loading:** Automatically fetched the Iris dataset using `kagglehub`.
2. **Data Preprocessing:** Cleaned the dataset and separated input features (sepal/petal dimensions) from the target species labels.
3. **Model Training:** Split the data into training and testing sets, then trained a **K-Nearest Neighbors (KNN)** classification model using `scikit-learn`[span_1] (start_span) [span_1] (end_span).
4. **Evaluation:** Evaluated the model's performance and accuracy using test data[span_2] (start_span) [span_2] (end_span).

## Libraries Used
- Python
- Pandas
- Scikit-learn
- Kagglehub

## Results
- The KNN classifier successfully predicted the flower species with high accuracy (~97%-100%).
