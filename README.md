# Titanic Survival Prediction Using Machine Learning

## 📖 Introduction

The Titanic Survival Prediction project is a supervised machine learning classification project that predicts whether a passenger survived the Titanic disaster. The project uses passenger information such as age, gender, passenger class, fare, and family details to build an accurate prediction model.

This project demonstrates the complete machine learning workflow, including data preprocessing, feature engineering, exploratory data analysis, model training, evaluation, and model saving.

---

## 🎯 Project Objective

The main objective of this project is to develop a machine learning model that can predict passenger survival based on historical Titanic passenger data. The project also aims to provide practical experience in data preprocessing, feature engineering, and classification algorithms.

---

## 📂 Dataset Description

The dataset contains information about Titanic passengers, including:

* PassengerId
* Survived
* Pclass
* Name
* Sex
* Age
* SibSp
* Parch
* Ticket
* Fare
* Cabin
* Embarked

The dataset was analyzed to understand passenger characteristics and identify important factors affecting survival.

---

## 🔍 Exploratory Data Analysis (EDA)

Exploratory Data Analysis was performed to understand the dataset and discover patterns.

The following visualizations were created:

* Survival count plot
* Gender vs survival analysis
* Age distribution histogram
* Passenger class vs survival plot

These visualizations helped identify relationships between passenger features and survival outcomes.

---

## 🛠 Data Preprocessing

Several preprocessing techniques were applied to prepare the dataset for machine learning:

* Missing values in the Age column were replaced using the median.
* Missing values in the Fare column were handled using the median value.
* Missing values in the Embarked column were filled using the mode.
* Categorical features were converted into numerical values using Label Encoding.

These preprocessing steps improved data quality and ensured compatibility with machine learning algorithms.

---


### CabinPresent

A new feature was created to indicate whether cabin information was available.

These engineered features improved the prediction performance of the model.

---

## 🤖 Machine Learning Model

The Random Forest Classifier was selected for this project because of its strong performance in classification problems.

The dataset was divided into:

* Training Data: 80%
* Testing Data: 20%

The model was trained using the selected passenger features.

---

## 📊 Features Used for Prediction

The following features were used to train the model:

* Pclass
* Sex
* Age
* Fare
* FamilySize
* CabinPresent
* Title

---

## 📈 Model Evaluation

The model performance was evaluated using:

* Accuracy Score
* Classification Report
* Confusion Matrix
* Feature Importance

The evaluation results showed that the model successfully predicts passenger survival.

---

## 📌 Feature Importance

Feature importance analysis was performed to determine which features contributed most to the prediction process. The feature importance graph provides insights into the influence of different passenger attributes.

---

## 💾 Model Saving

The trained model was saved using Joblib as:

```text
titanic_model.pkl
```

This allows the model to be reused without retraining.

---

## 🧰 Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Google Colab
* Joblib

---

## 📁 Project Structure

```text
Titanic_Survival_Prediction/
│
├── Titanic_Survival_Prediction.ipynb
├── titanic.csv
├── titanic_model.pkl
├── Executive_Summary.pdf
├── README.md
└── screenshots/
```

---

## ▶️ Steps to Run the Project

1. Open the notebook in Google Colab.
2. Upload the Titanic dataset.
3. Install the required libraries.
4. Perform data preprocessing.
5. Create additional features.
6. Train the Random Forest model.
7. Evaluate model performance.
8. Save the trained model.

---

## 📚 Learning Outcomes

Through this project, the following concepts were learned:

* Data preprocessing
* Handling missing values
* Feature engineering
* Data visualization
* Classification algorithms
* Model evaluation
* Feature importance analysis
* Model saving and deployment

---

## 🚀 Future Improvements

* Implement additional classification algorithms.
* Perform hyperparameter tuning.
* Develop a web application for predictions.
* Apply SHAP analysis for explainable AI.

---

## 👩‍💻 Author

**Matteddula Mayuri**
Department of Artificial Intelligence and Machine Learning
Sri Venkateswara College of Engineering

---
