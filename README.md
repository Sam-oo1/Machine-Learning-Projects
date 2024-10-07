# Machine-Learning-Projects
Some Machine Learning Practise Projects

## Binary Email Classification
Dataset link: The emails.csv dataset on the Kaggle
https://www.kaggle.com/datasets/balaka18/email-spam-classification-dataset-csv

Models Trained:
#### KNN
KNN Classification Report

|              | Precision | Recall | F1-Score | Support |
|--------------|-----------|--------|----------|---------|
| 0            | 0.93      | 0.87   | 0.90     | 739     |
| 1            | 0.73      | 0.84   | 0.78     | 296     |
| **Accuracy** |           |        | 0.86     | 1035    |
| **Macro Avg**| 0.83      | 0.86   | 0.84     | 1035    |
| **Weighted Avg** | 0.87  | 0.86   | 0.87     | 1035    |

KNN Accuracy: 0.8628

#### SVM
SVM Classification Report

|              | Precision | Recall | F1-Score | Support |
|--------------|-----------|--------|----------|---------|
| 0            | 0.98      | 0.97   | 0.97     | 739     |
| 1            | 0.92      | 0.94   | 0.93     | 296     |
| **Accuracy** |           |        | 0.96     | 1035    |
| **Macro Avg**| 0.95      | 0.95   | 0.95     | 1035    |
| **Weighted Avg** | 0.96  | 0.96   | 0.96     | 1035    |

SVM Accuracy: 0.9594

## Uber Ride Price Prediction
Dataset link: https://www.kaggle.com/datasets/yasserh/uber-fares-dataset

Models Trained:
#### Linear Regression model


| Mean Absolute Error (MAE)     | 3.2898525988467457   | 
|-------------------------------|----------------------|
| Mean Squared Error (MSE)      | 20.907273771177874   |
|Root Mean Squared Error (RMSE) | 4.572447240939788    |        
| R² Score                      | 0.011967786655664336 |

#### Random Forest Regressor

  Mean Squared Error: 9.201159079012482

  R² Score: 0.5651732660284641







