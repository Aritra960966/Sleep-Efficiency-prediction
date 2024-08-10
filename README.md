# Sleep Efficiency Prediction and Analysis

## Overview

This project focuses on predicting sleep efficiency using various regression models and performing comprehensive data analysis. The goal is to understand the effectiveness of different machine learning models in predicting sleep efficiency based on historical data. Additionally, clustering and visualization techniques are employed to gain deeper insights into the data.

## Models Implemented

- **Linear Regression**
- **Decision Tree Regressor**
- **Random Forest Regressor**
- **XGBoost Regressor**

## Performance Metrics

The performance of the models is evaluated using several metrics, including Mean Absolute Error (MAE), Mean Squared Error (MSE), R² Score, Accuracy, Precision, Recall, and F1 Score. The metrics are computed for both training and testing datasets.

Here is a summary of the performance metrics for each model:

| Model                  | MAE (Train) | MAE (Test) | MSE (Train) | MSE (Test) | R² Score (Train) | R² Score (Test) | Accuracy (Train) | Accuracy (Test) | Precision (Train) | Precision (Test) | Recall (Train) | Recall (Test) | F1 Score (Train) | F1 Score (Test) |
|------------------------|-------------|------------|-------------|------------|------------------|------------------|------------------|-----------------|-------------------|------------------|----------------|---------------|------------------|-----------------|
| Linear Regression     | 0.048599    | 0.049442   | 0.003623    | 0.003686   | 0.813307         | 0.729183         | 0.972299         | 1.000000        | 0.968699          | 1.0              | 0.972299       | 1.000000      | 0.970360         | 1.000000        |
| Decision Tree Regressor | 0.000166    | 0.050659   | 0.000005    | 0.004975   | 0.999743         | 0.634466         | 1.000000         | 0.989011        | 1.000000          | 1.0              | 1.000000       | 0.989011      | 1.000000         | 0.994475        |
| Random Forest Regressor | 0.014364    | 0.038918   | 0.000392    | 0.002501   | 0.979810         | 0.816257         | 0.977839         | 1.000000        | 0.956170          | 1.0              | 0.977839       | 1.000000      | 0.966883         | 1.000000        |
| XGBoost Regressor      | 0.001754    | 0.040514   | 0.000011    | 0.002903   | 0.999419         | 0.786660         | 0.986150         | 1.000000        | 0.986343          | 1.0              | 0.986150       | 1.000000      | 0.983050         | 1.000000        |

## Clustering and Visualization

The dataset was also analyzed using clustering techniques and visualized to uncover patterns and insights. The visualizations help to understand the distribution of sleep efficiency and the relationships between different features.

## Getting Started

To run this project locally, follow these steps:

 **Clone the Repository:**
   ```bash
   git clone https://github.com/Aritra960966/sleep-efficiency-prediction.git
