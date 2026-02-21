# 📊 Mutual Fund Data Analysis using Web Scraping & EDA

## 📌 Project Overview

This project focuses on collecting real-world mutual fund data using web scraping and performing Exploratory Data Analysis (EDA) to understand the relationship between risk, returns, ranking, and ratings.

The objective is to transform raw financial data into meaningful insights that support data-driven investment decisions.

---

## 🎯 Objectives

- Scrape mutual fund data from Groww platform
- Clean and preprocess financial datasets
- Handle missing values and outliers
- Analyze risk–return trade-offs
- Study ranking credibility
- Identify performance patterns across fund categories

---

## 📊 Dataset Overview

- Total Records: 1429 Mutual Funds
- Numerical Features: 10
- Categorical Features: 7
- Target Variables: Rank, Rating

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- BeautifulSoup
- Requests
- Jupyter Notebook

---

## 🔎 Project Workflow

### 1️⃣ Web Scraping
- Extracted mutual fund data
- Handled pagination
- Parsed percentage fields
- Structured raw data into CSV format

### 2️⃣ Data Cleaning
- Converted 1Y, 3Y, 5Y returns from percentage strings to numeric
- Median imputation for missing values
- Removed duplicate records
- Retained meaningful financial outliers

### 3️⃣ Exploratory Data Analysis
- Distribution analysis (KDE & skewness)
- Risk vs Return comparison
- Category-wise performance analysis
- Correlation analysis
- Ranking validation

---

## 📈 Key Insights

- Return distributions are positively skewed due to a small number of high-performing funds.
- Commodities provide the highest returns but with high volatility.
- Debt funds offer stability with lower returns.
- Volatility decreases over longer investment horizons.
- Strong inverse relationship between risk-adjusted return and rank validates ranking methodology.

---

## ⚠️ Limitations

- No macroeconomic variables included
- No benchmark comparison
- Static snapshot (no time-series modeling)
- Expense ratio not considered

---

## ▶️ How to Run

1. Clone the repository:

git clone https://github.com/TEJAKESARAPU/mutual-fund-eda-analysis.git

2. Install dependencies:

pip install -r requirements.txt

3. Open Jupyter Notebook:

jupyter notebook

4. Run notebooks in order:
   - groww_data_scraping.ipynb
   - groww_data_cleaning.ipynb
   - groww_eda_analysis.ipynb

---

## 👤 Author

Teja Kesarapu  
Email: tejakesarapu@gmail.com  
LinkedIn: https://linkedin.com/in/tejakesarapu  
GitHub: https://github.com/TEJAKESARAPU

---

⭐ If you found this project useful, consider giving it a star!
