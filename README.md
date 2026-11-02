# Heart-Disease-Prediction
Predicting Heart Disease by comparing machine learning models
#  Heart Disease Prediction Using Machine Learning

## 📌 Project Overview

This project focuses on predicting the presence of heart disease using Machine Learning classification algorithms. The goal is to analyze patient health-related data and identify whether a person is likely to have heart disease.

Three different machine learning algorithms are implemented and compared to identify the best-performing model.

## 🎯 Objectives

* Analyze heart disease-related patient data.
* Perform data preprocessing and feature scaling.
* Build machine learning classification models.
* Compare model performance using accuracy scores.
* Identify the best-performing model.

## 📂 Dataset Information

* **Dataset:** Heart Disease Dataset
* **Total Records:** 303
* **Total Features:** 13
* **Target Variable:** `target`
* **Missing Values:** No missing values found.

The dataset contains features such as:

* Age
* Sex
* Chest Pain Type
* Resting Blood Pressure
* Cholesterol
* Maximum Heart Rate
* Exercise-Induced Angina
* Oldpeak
* Slope
* Thalassemia

## 🛠️ Technologies & Libraries Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Google Colab / Jupyter Notebook

## ⚙️ Project Workflow

1. Import required libraries.
2. Load the heart disease dataset.
3. Perform initial data inspection.
4. Check for missing values.
5. Separate independent and dependent variables.
6. Split the dataset into training and testing sets (80:20).
7. Apply feature scaling using StandardScaler.
8. Train machine learning models.
9. Evaluate and compare model performance.
10. Identify the best-performing model.

## 🤖 Machine Learning Algorithms

The following algorithms were implemented:

1. Logistic Regression
2. K-Nearest Neighbors (KNN)
3. Decision Tree Classifier

## 📊 Model Performance

The accuracy scores obtained from the models are:

| Algorithm                 | Accuracy |
| ------------------------- | -------: |
| Logistic Regression       |   85.25% |
| K-Nearest Neighbors (KNN) |   90.16% |
| Decision Tree             |   75.41% |

### 🏆 Best Performing Model

**K-Nearest Neighbors (KNN)** achieved the highest accuracy of **90.16%**.

The KNN model was further evaluated using:

* Confusion Matrix
* Classification Report
* Precision
* Recall
* F1-Score

## 📈 KNN Classification Report

| Metric    | Class 0 | Class 1 |
| --------- | ------: | ------: |
| Precision |    0.87 |    0.93 |
| Recall    |    0.93 |    0.88 |
| F1-Score  |    0.90 |    0.90 |

**Overall Accuracy: 90.16%**

## 🚀 How to Run the Project

1. Clone this repository:

   ```bash
   git clone YOUR_GITHUB_REPOSITORY_URL
   ```

2. Install the required libraries:

   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn jupyter
   ```

3. Open the Jupyter Notebook or upload it to Google Colab.

4. Make sure the `heart.csv` dataset is available in the correct location.

5. Run all the notebook cells to train and evaluate the models.

## 📁 Project Structure

```text
Heart-Disease-Prediction/
│
├── Heart_Disease_Prediction_.ipynb
├── heart.csv
└── README.md
```

## 🔍 Conclusion

This project demonstrates the application of Machine Learning classification algorithms for heart disease prediction.

Among the three models, K-Nearest Neighbors achieved the highest accuracy of 90.16%, making it the best-performing model in this experiment.

## 👨‍💻 Author

**Eldho K W**



