**Breast Cancer Prediction using Machine Learning**

This project aims to predict whether a tumor is malignant or benign using machine learning classification algorithms based on the Breast Cancer Wisconsin (Diagnostic) dataset.

**Objective**

To build an accurate classification model that can assist in early detection of breast cancer using features computed from digitized images of fine needle aspirates (FNAs) of breast masses.

**Dataset**

- Source: [Breast Cancer Wisconsin (Diagnostic) Data Set](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_breast_cancer.html)
- Features: 30 numerical features like radius, texture, perimeter, area, smoothness, etc.
- Target: Diagnosis (`0` = malignant, `1` = benign)

 **Tools & Libraries Used**

- Python 3.x
- NumPy
- Pandas
- Matplotlib, Seaborn
- Scikit-learn

**Workflow Summary**

1. Data Loading and Exploration
   - Loaded the dataset from `sklearn.datasets`.
   - Examined feature names, target labels, and data shapes.

2. Data Preprocessing
   - Converted the dataset into a Pandas DataFrame.
   - Checked for null values and data types.
   - Performed basic exploratory data analysis (EDA).

3. Model Building
   - Applied Logistic Regression for binary classification.
   - Split data into training and test sets (80/20 split).
   - Trained the model and made predictions.

4. Evaluation
   - Accuracy Score
   - Confusion Matrix
   - Classification Report (Precision, Recall, F1-score)



