# 📧 Email Spam Detection using Machine Learning

## 📌 Project Overview

Email Spam Detection is a Natural Language Processing (NLP) project that classifies incoming messages as either **Spam** or **Ham (Not Spam)**. This project uses machine learning techniques to automatically identify unwanted messages, helping improve email security and user experience.

The project covers the complete machine learning pipeline, including text preprocessing, feature extraction using TF-IDF, model training, evaluation, and performance comparison.

---

## 🎯 Objective

The primary objectives of this project are to:

- Detect whether a message is Spam or Ham.
- Perform text preprocessing to clean raw text data.
- Convert text into numerical features using TF-IDF Vectorization.
- Train multiple machine learning classification models.
- Compare model performance using various evaluation metrics.
- Identify the best-performing model for spam detection.

---

## 📂 Dataset

- **Dataset:** SMS Spam Collection Dataset
- **Source:** Kaggle / UCI Machine Learning Repository
- **Format:** CSV

### Dataset Features

| Column | Description |
|----------|-------------|
| label | Spam or Ham |
| message | SMS or Email Text |

---

## 🛠 Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- NLTK
- WordCloud

---

## 📋 Project Workflow

### 1. Data Collection

- Load SMS Spam Dataset
- Inspect dataset
- Check class distribution

### 2. Data Cleaning

- Remove duplicate records
- Handle missing values
- Convert labels into numerical values

### 3. Text Preprocessing

- Convert text to lowercase
- Remove punctuation
- Remove stopwords
- Tokenization
- Lemmatization (Optional)

### 4. Feature Extraction

- TF-IDF Vectorization
- Convert text into numerical vectors

### 5. Model Building

The following Machine Learning models were trained:

- Multinomial Naive Bayes
- Logistic Regression

### 6. Model Evaluation

Models were evaluated using:

- Accuracy Score
- Precision
- Recall
- F1 Score
- Confusion Matrix
- Classification Report

### 7. Visualization

Generated visualizations include:

- Spam vs Ham Distribution
- WordCloud for Spam Messages
- WordCloud for Ham Messages
- Confusion Matrix
- Model Comparison Chart

---

## 📊 Exploratory Data Analysis (EDA)

Performed:

- Dataset inspection
- Missing value analysis
- Duplicate value analysis
- Class distribution
- Message length analysis
- Word frequency analysis
- Spam vs Ham comparison

---

## 📈 Visualizations

- Count Plot of Spam vs Ham
- Message Length Distribution
- WordCloud for Spam Messages
- WordCloud for Ham Messages
- Confusion Matrix
- Accuracy Comparison Chart

---

## 🤖 Machine Learning Models

| Model | Purpose |
|--------|---------|
| Multinomial Naive Bayes | Baseline text classification model |
| Logistic Regression | Alternative classification model |

---

## 📊 Evaluation Metrics

The following metrics were used to evaluate model performance:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

---

## 📁 Project Structure

```
DataScience-Task4-EmailSpamDetection/
│
├── Email_Spam_Detection.ipynb
├── README.md
├── requirements.txt
├── spam.csv
└── images/
    ├── spam_distribution.png
    ├── spam_wordcloud.png
    ├── ham_wordcloud.png
    ├── confusion_matrix.png
    └── model_comparison.png
```

---

## ▶️ How to Run

### 1. Clone Repository

```bash
git clone https://github.com/your-username/OIBSIP.git
```

### 2. Open Project Folder

```bash
cd DataScience-Task4-EmailSpamDetection
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Open Notebook

Run the notebook in:

- Google Colab
- Jupyter Notebook

### 5. Execute All Cells

The notebook will:

- Load dataset
- Clean text
- Generate TF-IDF features
- Train models
- Evaluate performance
- Predict spam messages

---

## 📊 Results

The machine learning models successfully classified SMS messages into Spam and Ham categories.

Among the trained models, **Multinomial Naive Bayes** achieved excellent performance due to its effectiveness in text classification tasks, while **Logistic Regression** also delivered strong and competitive results.

---

## 🚀 Future Improvements

- Train advanced NLP models such as Support Vector Machine (SVM).
- Implement Deep Learning using LSTM or BERT.
- Deploy the model using Streamlit or Flask.
- Integrate with an email application for real-time spam filtering.
- Improve preprocessing using advanced NLP techniques.

---

## 👨‍💻 Author

**Satyam Sharma**

MCA (AI & Data Science)

Oasis Infobyte Data Science Internship

---

## 🙏 Acknowledgements

- Oasis Infobyte for providing this internship project.
- UCI Machine Learning Repository.
- Kaggle.
- Scikit-learn Documentation.
- NLTK Documentation.
- Python Open Source Community.
