# 🚢Titanic-Dataset-Cleaning-and-Pediction
This project focuses on cleaning and preprocessing the Titanic dataset by handling missing values, dropping irrelevant features, and encoding categorical variables. A machine learning model (Random Forest) is then trained to predict passenger survival based on selected features.

---

## 📁 Dataset Source

This dataset is from the [Kaggle Titanic Competition](https://www.kaggle.com/competitions/titanic/data), which includes:

- `train.csv`: Contains training data with the `Survived` label.
- `test.csv`: Contains test data without the label.
- `gender_submission.csv`: A sample submission file (baseline prediction).

---

## 🧠 Workflow

1. **Load & explore the data**
2. **Handle missing values**
3. **Drop irrelevant features**
4. **Encode categorical columns**
5. **Train a Random Forest model**
6. **Evaluate model accuracy**
7. **Predict on test data**
8. **Save predictions to `submission.csv`**

---

## 🛠 Requirements

Install dependencies:

```bash
pip install -r requirements.txt
pandas==2.2.2
scikit-learn==1.4.2
numpy==1.26.4

