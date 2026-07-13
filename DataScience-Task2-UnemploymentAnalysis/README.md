# 📊 Unemployment Analysis with Python

## 📌 Project Overview

This project analyzes unemployment trends in India using Python and data visualization techniques. The analysis focuses on understanding regional unemployment patterns, monthly trends, and the impact of the COVID-19 pandemic on unemployment rates.

The project demonstrates the complete data analysis workflow, including data cleaning, exploratory data analysis (EDA), visualization, and deriving meaningful insights from the dataset.

---

## 🎯 Objective

The main objectives of this project are to:

- Analyze unemployment rates across different states and regions of India.
- Identify trends in unemployment over time.
- Compare unemployment rates before and after the COVID-19 pandemic.
- Visualize unemployment patterns using various charts and graphs.
- Extract meaningful insights that can help understand employment conditions in India.

---

## 📂 Dataset

- **Dataset:** Unemployment in India
- **Source:** Kaggle
- **Format:** CSV
- **Features Include:**
  - Region
  - Date
  - Frequency
  - Estimated Unemployment Rate (%)
  - Estimated Employed
  - Estimated Labour Participation Rate (%)
  - Area (Urban/Rural)

---

## 🛠️ Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 📋 Project Workflow

### 1. Data Loading

- Imported dataset
- Loaded data into a Pandas DataFrame

### 2. Data Cleaning

- Checked missing values
- Removed null records
- Removed duplicate records
- Converted Date column into DateTime format
- Renamed columns where necessary

### 3. Exploratory Data Analysis (EDA)

Performed:

- Dataset inspection
- Statistical summary
- Missing value analysis
- Duplicate analysis
- Region-wise unemployment analysis
- Monthly unemployment trend
- State-wise comparison
- Correlation analysis
- COVID-19 impact analysis

---

## 📈 Visualizations

The following visualizations were created:

- Unemployment Rate Distribution
- Region-wise Average Unemployment Rate
- Top 10 States with Highest Unemployment
- Monthly Unemployment Trend
- Time Series Analysis
- Correlation Heatmap
- Labour Participation vs Employment Scatter Plot
- Pre-COVID vs Post-COVID Comparison
- Urban vs Rural Unemployment Boxplot

---

## 🔍 Key Insights

- The unemployment rate varies significantly across different states.
- Some regions consistently experience higher unemployment than others.
- The COVID-19 pandemic caused a noticeable increase in unemployment.
- Labour participation and employment levels are closely related.
- Monthly analysis reveals fluctuations in unemployment throughout the year.

---

## 📊 Libraries Used

- pandas
- numpy
- matplotlib
- seaborn

---

## 📁 Project Structure

```
DataScience-Task2-UnemploymentAnalysis/
│
├── Unemployment_Analysis.ipynb
├── README.md
├── requirements.txt
├── Unemployment in India.csv
└── images/
    ├── unemployment_distribution.png
    ├── statewise_average.png
    ├── monthly_trend.png
    ├── heatmap.png
    ├── covid_comparison.png
```

---

## ▶️ How to Run

1. Clone this repository.

```bash
git clone https://github.com/your-username/OIBSIP.git
```

2. Navigate to the project folder.

```bash
cd DataScience-Task2-UnemploymentAnalysis
```

3. Install the required libraries.

```bash
pip install -r requirements.txt
```

4. Open the notebook in Jupyter Notebook or Google Colab.

5. Upload the dataset if using Google Colab.

6. Run all notebook cells sequentially.

---

## 📈 Results

The project successfully analyzed unemployment trends across India and provided meaningful insights through data visualization. The comparison between pre-COVID and post-COVID periods highlighted the significant impact of the pandemic on employment.

---

## 🚀 Future Improvements

- Build an interactive dashboard using Streamlit or Power BI.
- Include forecasting models for future unemployment prediction.
- Add district-level unemployment analysis.
- Integrate live government employment datasets.
- Perform advanced time-series forecasting using ARIMA or Prophet.

---

## 👨‍💻 Author

**Satyam Sharma**

MCA (AI & Data Science)

Oasis Infobyte Data Science Internship

---

## 🙏 Acknowledgements

- Oasis Infobyte for providing this internship project.
- Kaggle for the dataset.
- Python Open Source Community.
- Pandas, Matplotlib, and Seaborn documentation.
