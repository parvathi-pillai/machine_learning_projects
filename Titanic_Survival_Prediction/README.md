Titanic Survival Prediction using Logistic Regression

This project uses the Titanic dataset from Kaggle to predict whether a passenger survived the Titanic shipwreck using logistic regression — a supervised classification algorithm.

_** Project Objective**_

To build a binary classification model that can predict passenger survival based on features such as age, sex, passenger class, etc.

_** Dataset**_

- Source: [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data)
- Files:
  - `train.csv`: Training data
  - `test.csv`: Test data (without survival labels)
  - `gender_submission.csv`: A sample submission file for Kaggle

_** Features Used**_

- `Pclass` (Passenger class)
- `Sex`
- `Age`
- `SibSp` (Number of siblings/spouses aboard)
- `Parch` (Number of parents/children aboard)
- `Fare`
- `Embarked`

_** Tools & Libraries**_

- Python
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-learn (LogisticRegression, preprocessing, metrics)

_** Steps Performed**_

1. Data Exploration
   - Visualized missing values and correlations.
   - Plotted survival statistics by gender, class, and age.

2. Data Cleaning
   - Handled missing values (`Age`, `Embarked`).
   - Converted categorical variables to numeric (`Sex`, `Embarked`).

3. Model Training
   - Used `LogisticRegression` from `sklearn.linear_model`.
   - Split training data into train/validation sets.

4. Evaluation
   - Used accuracy, confusion matrix, precision, recall, and F1-score.
   - Compared performance on training vs validation data.

5. Prediction
   - Made predictions on test data and saved results in a submission CSV.


