# 🚢 Titanic Survival Prediction

This project predicts passenger survival on the Titanic using machine learning. It was built as a beginner-level classification task for the [Kaggle Titanic Competition](https://www.kaggle.com/competitions/titanic).

---

## 📊 Overview

The Titanic dataset provides details about passengers such as age, sex, ticket class, and more. Using this information, the goal is to predict whether a passenger survived the disaster.

---

## 🧠 Machine Learning Workflow

1. **Data Cleaning**
   - Filled missing `Age` and `Fare` values with median.
   - Normalized categorical columns (e.g. `Embarked`).

2. **Feature Engineering**
   - Combined `SibSp` and `Parch` into a new `family` feature.
   - Categorized passengers into `family_group` ("Alone", "Medium", "Large").

3. **Encoding**
   - Used `pd.get_dummies()` to one-hot encode categorical variables.

4. **Modeling**
   - Trained a `RandomForestClassifier` using `scikit-learn`.
   - Achieved predictions on test data aligned with training columns.

5. **Submission**
   - Created a `submission.csv` file as per Kaggle format.

---

## 📁 Files

- `train.csv` – Training dataset (from Kaggle)
- `test.csv` – Test dataset (from Kaggle)
- `titanic.ipynb` – Jupyter notebook with all preprocessing, training, and prediction code
- `submission.csv` – Final submission file for Kaggle

---

## 🧰 Tools & Libraries

- Python 3
- pandas
- NumPy
- scikit-learn
- Jupyter Notebook

---

## 📦 How to Run

1. Clone the repo
2. Install dependencies (optional: create a virtual environment)
3. Open `titanic.ipynb` and run all cells
4. Upload `submission.csv` to [Kaggle Titanic competition](https://www.kaggle.com/competitions/titanic)

---

## 📈 Future Work

- Try other models: Logistic Regression, XGBoost, SVM
- Hyperparameter tuning
- Cross-validation
- Model explainability using SHAP or feature importance plots

---

## 👤 Author

Aryan Shukla  
[GitHub](https://github.com/Indecre) • [Email](mailto:aryanshukla20102006@gmail.com)

