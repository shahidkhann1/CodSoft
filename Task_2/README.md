# 💳 Credit Card Fraud Detection

## 📌 Project Overview

This project is developed as part of the **CodSoft Machine Learning Internship**.

The objective of this project is to build a Machine Learning model that can identify fraudulent credit card transactions based on transaction details. The model helps financial institutions detect fraud quickly, reduce financial losses, and improve transaction security.

---

## 🎯 Objective

- Detect fraudulent credit card transactions.
- Perform data preprocessing and feature engineering.
- Train a Machine Learning classification model.
- Evaluate model performance using standard metrics.
- Predict whether a new transaction is **Fraud** or **Legitimate**.

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
Credit_Card_Fraud_Detection/
│
├── credit_card_fraud_detection.ipynb
├── fraud_detection_model.pkl
├── requirements.txt
└── README.md
```

---

## 📊 Dataset

The dataset contains transaction details such as:

- Transaction ID
- Transaction Date & Time
- Merchant Name
- Category
- Transaction Amount
- Customer Information
- Gender
- City
- State
- Job
- Latitude & Longitude
- Credit Card Number
- Fraud Label (Target)

**Target Variable**

- **0 → Legitimate Transaction**
- **1 → Fraudulent Transaction**

---

## ⚙️ Workflow

1. Import Required Libraries
2. Load Dataset
3. Explore Dataset
4. Handle Missing Values
5. Encode Categorical Features
6. Feature Selection
7. Train-Test Split
8. Train Random Forest Classifier
9. Evaluate Model Performance
10. Save Trained Model
11. Predict Fraud on New Transactions

---

## 🤖 Machine Learning Model

The project uses the following Machine Learning algorithm:

- Random Forest Classifier

The trained model is saved using **Joblib** for future predictions.

---

## 📈 Evaluation Metrics

The model performance is evaluated using:

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

### Install Required Libraries

```bash
pip install -r requirements.txt
```

### Run Jupyter Notebook

```bash
jupyter notebook
```

Open:

```
credit_card_fraud_detection.ipynb
```

Run all cells sequentially.

---

## 🔍 Example Prediction

### Input

```
Transaction Amount : ₹2500
Merchant Category : Shopping
Gender : Female
City : New York
Job : Engineer
```

### Output

```
Prediction : Legitimate Transaction
```

or

```
Prediction : Fraudulent Transaction
```

---

## 📌 Features

- Data Cleaning
- Feature Encoding
- Machine Learning Classification
- Fraud Detection
- Model Saving (.pkl)
- Predict New Transactions
- Beginner-Friendly Implementation

---

## 📷 Output

The notebook displays:

- Dataset Information
- Data Preprocessing
- Label Encoding
- Feature Selection
- Model Training
- Accuracy Score
- Classification Report
- Confusion Matrix
- Fraud Prediction Results

---

## 📦 Requirements

- Python 3.10+
- pandas
- numpy
- matplotlib
- scikit-learn
- joblib

Install all dependencies:

```bash
pip install pandas numpy matplotlib scikit-learn joblib
```

---

## 📊 Model Performance

| Metric | Score |
|---------|-------|
| Accuracy | 98%+ (Depends on Dataset) |
| Precision | High |
| Recall | High |
| F1-Score | High |

> **Note:** Model performance may vary depending on dataset size, preprocessing, feature selection, and train-test split.

---

## 💡 Future Improvements

- Hyperparameter Tuning
- XGBoost & LightGBM Implementation
- Deep Learning Models
- Real-Time Fraud Detection API
- Deployment using Flask or Streamlit
- Dashboard for Live Transaction Monitoring

---

## 🎓 Internship

This project was completed as **Task 2** of the **CodSoft Machine Learning Internship**.

---

## 👨‍💻 Author

**Shahid Khan**

GitHub:

https://github.com/shahidkhann1

---

## 🙏 Acknowledgement

Special thanks to **CodSoft** for providing this Machine Learning Internship project and the opportunity to improve practical Machine Learning skills.

---

## ⭐ If you found this project useful, don't forget to give it a Star ⭐ on GitHub!
