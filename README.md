# Medical Price Cost Prediction

## Overview

This project aims to predict the cost of medical procedures using machine learning techniques. Leveraging a dataset sourced from Kaggle and utilizing the scikit-learn library's linear regression model, this predictive model estimates the expenses associated with various medical procedures.

## Dataset

The dataset used in this project was obtained from Kaggle ([link to dataset](https://www.kaggle.com/datasets/mirichoi0218/insurance/download?datasetVersionNumber=1)). It contains comprehensive information regarding medical procedures, including patient demographics, region, type of treatments, and associated costs.

## Preprocessing

The dataset underwent thorough cleaning and preprocessing stages:
- **Data Cleaning:** Removed duplicates, handled missing values, and addressed outliers for reliable analysis.
- **Feature Engineering:** Extracted relevant features and encoded categorical variables for model compatibility.
- **Normalization:** Scaled numerical features to ensure uniformity across the dataset.

## Model Selection and Implementation

Linear regression from the scikit-learn library was chosen as the predictive model due to its simplicity and interpretability. The model was trained on the preprocessed data to learn the relationship between various factors and the cost of medical procedures.

## Results

The model achieved a reasonable level of accuracy in predicting medical costs based on the given features. Evaluation metrics such as Mean Squared Error (MSE) or R-squared were utilized to assess the model's performance.

## Usage

To run the project locally:
1. Clone this repository.
2. Install the required dependencies (`pip install -r requirements.txt`).
3. Execute the main script (`python medical_cost_prediction.py`) to train the model and make predictions.

## Further Enhancements

Potential improvements for this project include:
- Feature selection and engineering to enhance predictive power.
- Trying different machine learning algorithms to compare performance.
- Deploying the model as a web service for real-time predictions.

## Contribution

Contributions to this project are welcome! Feel free to fork the repository, propose enhancements, or report issues.
