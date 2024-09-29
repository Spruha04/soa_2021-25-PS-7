# soa_2021-25-PS-7

# Chronic Kidney Disease Prediction

## Aim
The aim of this project is to develop a machine learning model to classify whether or not a patient has **Chronic Kidney Disease (CKD)** based on medical attributes such as age, blood pressure, specific gravity, albumin, sugar, red blood cells, and more. The model is evaluated based on several performance metrics, including **accuracy, precision, recall, F1-score, and specificity**.

## Dataset
The dataset used is the **Chronic Kidney Disease Dataset** from the UC Irvine Machine Learning Repository, which contains medical records with features relevant to CKD diagnosis.

## Approach
The key steps involved in this project:
1. **Data Preprocessing**: Cleaning missing values, encoding categorical variables, and scaling numerical features.
2. **Model Training**: A Random Forest classifier was trained using 80% of the data for training and 20% for testing.
3. **Model Evaluation**: Various performance metrics such as accuracy, precision, recall, F1-score, and specificity were calculated.

## Results
The Random Forest classifier achieved the following performance metrics:

| Metric        | Score   |
|---------------|---------|
| **Accuracy**  | 100.00%  |
| **Precision** | 100.00%  |
| **Recall**    | 100.00% |
| **F1-Score**  | 100.00% |
| **Specificity** | 100.00% |

### Confusion Matrix

[[28  0][ 0 52]]

- **True Negatives**: 28
- **False Positives**: 0
- **False Negatives**: 0
- **True Positives**: 52

### Conclusion
The model shows strong performance in classifying patients with Chronic Kidney Disease, achieving high scores across all key metrics. With an accuracy of 95% and a balanced recall and specificity, the model performs well both in detecting CKD and correctly identifying non-CKD patients.

## Requirements
- Python 3.x
- Scikit-learn
- Pandas
- NumPy

