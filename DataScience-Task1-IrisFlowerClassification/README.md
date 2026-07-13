# 🌸 Iris Flower Classification using Machine Learning

## 📌 Project Overview

This project is a Machine Learning classification task that predicts the species of an Iris flower based on its physical measurements. The model classifies flowers into one of three species:

* Setosa
* Versicolor
* Virginica

The project includes data preprocessing, exploratory data analysis (EDA), model training, evaluation, and comparison of multiple machine learning algorithms.

---

## 🎯 Objective

The objective of this project is to build and evaluate machine learning models capable of accurately classifying Iris flower species using four botanical features:

* Sepal Length
* Sepal Width
* Petal Length
* Petal Width

---

## 📂 Dataset

* **Dataset:** Iris Dataset
* **Source:** Scikit-learn (`sklearn.datasets.load_iris()`)
* **Total Records:** 150
* **Features:** 4 Numerical Features
* **Target Classes:** 3

| Species    | Samples |
| ---------- | ------: |
| Setosa     |      50 |
| Versicolor |      50 |
| Virginica  |      50 |

---

## 🛠 Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## 📊 Exploratory Data Analysis (EDA)

The following analyses were performed:

* Dataset inspection
* Missing value analysis
* Duplicate record check
* Statistical summary
* Species distribution
* Histograms
* Boxplots
* Pairplot
* Correlation Heatmap

### Key Findings

* The dataset contains **150 samples** with **no missing values**.
* All three classes are equally distributed.
* Petal Length and Petal Width are the most important features for distinguishing species.
* Setosa is clearly separable from the other two species.

---

## 🤖 Machine Learning Models

The following models were trained and evaluated:

1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifier

---

## 📈 Model Evaluation

Each model was evaluated using:

* Accuracy Score
* Confusion Matrix
* Classification Report

  * Precision
  * Recall
  * F1-Score

A comparison table was created to identify the best-performing model.

---

## 📌 Feature Importance

Random Forest was used to determine feature importance.

The most significant features were:

* Petal Length
* Petal Width

---

## 🚀 Results

The trained models achieved excellent classification performance on the Iris dataset.

The **Random Forest Classifier** provided the best overall performance and was selected as the final model for prediction.

---

## 📷 Visualizations Included

* Species Distribution
* Histograms
* Boxplots
* Pairplot
* Correlation Heatmap
* Confusion Matrix
* Model Comparison Chart
* Feature Importance Graph

---

## 📁 Project Structure

```text
DataScience-Task1-IrisClassification/
│
├── Iris_Flower_Classification.ipynb
├── README.md
├── requirements.txt
└── images/
```

---

## ▶️ How to Run the Project

1. Open the notebook in Google Colab or Jupyter Notebook.
2. Run all cells in sequence.
3. The dataset is loaded directly from Scikit-learn, so no manual download is required.
4. View the visualizations and model evaluation results.
5. Use the prediction section to classify new flower measurements.

---

## 📚 Future Improvements

* Perform Hyperparameter Tuning
* Apply Cross-Validation
* Train additional models such as SVM and XGBoost
* Deploy the model using Streamlit or Flask
* Create an interactive web application for predictions

---

## 👨‍💻 Author

**Satyam Sharma**

MCA (AI & Data Science)

Oasis Infobyte Data Science Internship

---

## ⭐ Acknowledgements

* Scikit-learn for providing the Iris dataset.
* Oasis Infobyte for the internship project.
