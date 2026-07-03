# 👥 Customer Churn Prediction

## 📌 Project Overview

This project is developed as part of the **CodSoft Machine Learning Internship**.

The objective of this project is to build a Machine Learning model that predicts whether a customer is likely to leave (churn) or continue using a company's services. Customer churn prediction helps businesses identify at-risk customers and improve customer retention strategies.

---

## 🎯 Objective

- Predict customer churn using Machine Learning.
- Perform data preprocessing and feature engineering.
- Train and evaluate a classification model.
- Predict whether a customer will churn or not.
- Help businesses improve customer retention.

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Label Encoder
- Random Forest Classifier
- Joblib

---

## 📂 Project Structure

```
Customer_Churn_Prediction/
│
├── customer_churn_prediction.ipynb
├── Churn_Modelling.csv
├── requirements.txt
└── README.md
```

---

## 📊 Dataset

The dataset contains customer information such as:

- Customer ID
- Credit Score
- Geography
- Gender
- Age
- Tenure
- Balance
- Number of Products
- Has Credit Card
- Is Active Member
- Estimated Salary
- Churn (Target)

### Target Variable

- **0 → Customer Stayed**
- **1 → Customer Churned**

---

## ⚙️ Workflow

1. Import Required Libraries
2. Load Dataset
3. Data Exploration
4. Handle Missing Values
5. Encode Categorical Features
6. Feature Selection
7. Train-Test Split
8. Train Machine Learning Model
9. Evaluate Model Performance
10. Save Trained Model
11. Predict Customer Churn

---

## 🤖 Machine Learning Model

The project uses:

- Random Forest Classifier

The trained model is saved using **Joblib** for future predictions.

---

## 📈 Evaluation Metrics

The model is evaluated using:

- Accuracy Score
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Classification Report

---

## 🚀 How to Run

### Clone Repository

```bash
git clone https://github.com/shahidkhann1/CODSOFT.git
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Jupyter Notebook

```bash
jupyter notebook
```

Open:

```
customer_churn_prediction.ipynb
```

Run all cells sequentially.

---

## 🔍 Example Prediction

### Input

```
Credit Score : 650
Age : 40
Balance : 65000
Geography : France
Gender : Male
Is Active Member : Yes
Estimated Salary : 75000
```

### Output

```
Prediction : Customer Will Stay
```

or

```
Prediction : Customer Will Churn
```

---

## 📌 Features

- Data Cleaning
- Feature Encoding
- Feature Selection
- Customer Churn Prediction
- Machine Learning Classification
- Model Saving (.pkl)
- Prediction on New Customer Data

---

## 📷 Output

The notebook displays:

- Dataset Information
- Data Preprocessing
- Feature Encoding
- Model Training
- Accuracy Score
- Classification Report
- Confusion Matrix
- Customer Churn Prediction

---

## 📦 Requirements

- Python 3.10+
- pandas
- numpy
- matplotlib
- scikit-learn
- joblib

Install dependencies using:

```bash
pip install pandas numpy matplotlib scikit-learn joblib
```

---

## 📊 Model Performance

| Metric | Score |
|---------|-------|
| Accuracy | 85%–90% (Depends on Dataset) |
| Precision | High |
| Recall | High |
| F1-Score | High |

> **Note:** The model's performance depends on the dataset quality, preprocessing steps, and selected algorithm.

---

## 💡 Future Improvements

- Hyperparameter Tuning
- XGBoost & LightGBM Models
- Deep Learning Implementation
- Real-Time Churn Prediction API
- Streamlit Web Application
- Customer Retention Dashboard

---

## 🎓 Internship

This project was completed as **Task 3** of the **CodSoft Machine Learning Internship**.

---

## 👨‍💻 Author

**Shahid Khan**

GitHub:

https://github.com/shahidkhann1

---

## 🙏 Acknowledgement

Special thanks to **CodSoft** for providing this Machine Learning Internship and the opportunity to work on real-world Machine Learning projects.

---

## ⭐ If you found this project useful, don't forget to give it a Star ⭐ on GitHub!
