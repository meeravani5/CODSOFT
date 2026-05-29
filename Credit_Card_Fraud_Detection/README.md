# 💳 Credit Card Fraud Detection

## 📌 Objective

The objective of this project is to build a Machine Learning model that can identify fraudulent credit card transactions and distinguish them from legitimate transactions.

---

## 📊 Dataset

The dataset contains information about credit card transactions, including transaction amount, merchant details, customer information, location details, and fraud labels.

Target Variable:

* **is_fraud**

  * 0 = Legitimate Transaction
  * 1 = Fraudulent Transaction

---

## 🛠️ Technologies Used

* Python
* Pandas
* Matplotlib
* Scikit-learn
* Jupyter Notebook

---

## 🔄 Data Preprocessing

The following preprocessing steps were performed:

1. Loaded the dataset using Pandas.
2. Checked for missing values.
3. Removed unnecessary columns:

   * Unnamed: 0
   * first
   * last
   * street
   * trans_num
4. Converted categorical features into numerical values using Label Encoding.
5. Removed date-based string columns:

   * trans_date_trans_time
   * dob

---

## 🤖 Machine Learning Model

Algorithm Used:

* Logistic Regression

The dataset was divided into training and testing sets using an 80:20 ratio.

---

## 📈 Model Evaluation

Evaluation Metrics:

* Accuracy Score
* Classification Report
* Confusion Matrix

### Result

The Logistic Regression model achieved approximately **99% accuracy** on the test dataset.

---

## 📊 Visualization

A bar chart was created to visualize the distribution of:

* Fraudulent Transactions
* Legitimate Transactions

---

## 📂 Project Files

* fraud_detection.ipynb
* fraudTrain.csv
* README.md

---

## ✅ Conclusion

This project demonstrates how Machine Learning can be used to detect fraudulent credit card transactions. Data preprocessing, feature encoding, and Logistic Regression were used to build a fraud detection model capable of identifying suspicious transactions with high accuracy.

---

## 👩‍💻 Author
s
**Meera Vani Jagana**
