# 📩 Spam SMS Detection

## Introduction

Spam SMS Detection is a Machine Learning project that classifies SMS messages as either Spam or Ham (Not Spam). The project uses Natural Language Processing (NLP) techniques to analyze text messages and identify unwanted or fraudulent content.

The increasing number of spam messages can cause inconvenience and security risks to users. This project aims to automatically filter such messages using Machine Learning algorithms.

---

## Objective

The objective of this project is to build a Machine Learning model that can accurately classify SMS messages as spam or legitimate based on their textual content.

---

## Dataset

The dataset used in this project contains SMS messages along with their labels.

### Labels

* Spam – Unwanted promotional or fraudulent messages.
* Ham – Genuine messages from users.

The dataset is stored in the file:

```text
spam.csv
```

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Jupyter Notebook

---

## Methodology

### Data Collection

The SMS dataset was loaded using Pandas and inspected for missing values and inconsistencies.

### Data Preprocessing

The following preprocessing steps were performed:

* Removing unnecessary columns
* Cleaning text data
* Encoding labels
* Splitting data into training and testing sets

### Feature Extraction

TF-IDF (Term Frequency – Inverse Document Frequency) Vectorization was used to convert SMS text into numerical features suitable for machine learning models.

### Model Building

The classification model used in this project is:

* Logistic Regression

The model was trained on the processed dataset and used to predict whether a message is spam or not.

---

## Model Evaluation

The model performance was evaluated using:

* Accuracy Score
* Classification Report
* Confusion Matrix

### Accuracy

The model achieved approximately **96% accuracy** on the test dataset.

---

## Example Prediction

### Input

```text
Free entry in a contest! Win cash now!
```

### Output

```text
Spam
```

### Input

```text
Hey, are we meeting today at 5 PM?
```

### Output

```text
Ham (Not Spam)
```

---

## Applications

This project can be used in:

* Mobile Messaging Applications
* SMS Filtering Systems
* Security Applications
* Spam Prevention Systems

---

## Project Structure

```text
Spam_SMS_Detection/
│
├── spam_sms_detection.ipynb
├── spam.csv
└── README.md
```

---

## Results

The model successfully classified SMS messages into spam and non-spam categories with high accuracy. The use of TF-IDF and Logistic Regression provided reliable performance for text classification.

---

## Conclusion

This project demonstrates the practical application of Natural Language Processing and Machine Learning in detecting spam SMS messages. By transforming text into numerical features and training a classification model, the system can effectively identify spam messages and help improve communication security.

---

## Author

**Meera Vani Jagana**

Machine Learning Internship – CodSoft
