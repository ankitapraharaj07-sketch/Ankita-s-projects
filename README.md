# Ankita-s-projects
# 📊 Finance Data Science Projects

A collection of data science projects applying machine learning and statistical 
analysis to real-world finance problems.

## 🛠️ Tech Stack
Python · Pandas · NumPy · Scikit-learn · YFinance · 
Matplotlib/Seaborn · Jupyter Notebook · SQLite3 · Plotly 

---

## 📁 Projects

### 1. AAPL Stock Price Visualization
`project_1.ipynb`

**What it does:** Retrieves Apple Inc. (AAPL) daily stock price data for 2025 
via the Yahoo Finance API and visualizes the closing price trend over time.
**Techniques:** yfinance API, pandas time-series handling, matplotlib visualization
**Key output:** Interactive closing-price chart exported as PNG

### 2. Transaction Fraud Detection with SQL Feature Engineering
`project_2.ipynb`

**What it does:** Builds a fraud detection pipeline on synthetic transaction 
data, using SQL window functions to engineer per-user behavioral features 
(historical spend patterns), then trains a Random Forest classifier to flag 
fraudulent transactions.
**Techniques:** SQLite, SQL window functions, Random Forest, stratified 
train-test split, imbalanced classification evaluation
**Key result:** 98% accuracy overall; 100% precision / 30% recall on fraud 
cases — highlighting the precision-recall tradeoff common in imbalanced 
fraud detection tasks.

### 3. Financial News Sentiment vs. Stock Price Correlation
`project_3.ipynb`

**What it does:** Applies NLP sentiment analysis to financial news headlines 
about AAPL and visualizes the relationship between daily aggregated sentiment 
and stock price movement using a dual-axis chart.
**Techniques:** VADER sentiment analysis (NLP), data aggregation, dual-axis 
matplotlib visualization
**Key result:** Demonstrated a visual correlation between negative/positive 
news sentiment and same-day price movement on a sample AAPL dataset.
**Note:** Uses illustrative/mock headline and price data to demonstrate the 
methodology.

### 4. Credit Risk Scoring Model
`project_4.ipynb`

**What it does:** Builds a credit risk scorecard that predicts loan default 
probability from applicant financial data (income, debt-to-income ratio, 
missed payments, credit utilization) and converts model output into a 
traditional 300–850 FICO-style credit score.
**Techniques:** Logistic Regression, feature scaling, probability calibration, 
ROC-AUC evaluation
**Key result:** Achieved ROC-AUC of 0.80 — a strong discriminative score for 
a credit risk model.

### 5. Automobile Sales & Recession Impact Dashboard (Parts 1 & 2)
`project_5_part1.ipynb`, `project_5_part2.ipynb`

**What it does:** Analyzes how economic recessions affect automobile sales 
(1980–2023) — covering GDP, unemployment, consumer confidence, seasonality, 
and advertising spend — then builds an interactive Dash web dashboard letting 
users explore yearly or recession-period statistics dynamically.
**Techniques:** Exploratory data analysis (matplotlib, seaborn), multi-variate 
correlation analysis, interactive dashboard development (Dash, Plotly Express)
**Key result:** Delivered a fully interactive, deployable BI dashboard — 
not just static analysis — with dynamic dropdown-driven visualizations.
**Note:** Built using a public automobile sales dataset from an IBM Skills 
Network course.


---

## 🚀 How to Run
1. Clone the repo: `git clone https://github.com/ankitapraharaj07-sketch/Ankita-s-projects.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Open notebooks in Jupyter or Google Colab

## 📌 Notes
Built as part of my ongoing learning in applying data science to finance. 
Feedback and suggestions welcome!
