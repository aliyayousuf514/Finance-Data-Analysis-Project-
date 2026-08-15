# 📊 Stock Market Data Analysis & EDA

## 📌 Project Overview

This project focuses on analyzing historical stock market data of major technology companies using Python.

The objective of this project is to understand stock price movements, daily returns, trading activity, volatility, and relationships between different technology stocks through statistical analysis and data visualization.

The selected companies for this analysis are:

- 🍎 Apple Inc. (AAPL)
- 📦 Amazon.com Inc. (AMZN)
- 🎬 Netflix Inc. (NFLX)

---

## 🎯 Project Objectives

The main objectives of this project are:

- Collect historical stock market data
- Perform data checking and preprocessing
- Analyze stock prices using descriptive statistics
- Visualize closing price trends
- Analyze trading volume
- Calculate daily stock returns
- Analyze stock risk and volatility
- Perform Pearson correlation analysis
- Visualize relationships using a correlation heatmap
- Draw conclusions from the analysis

---

## 📂 Dataset

The historical stock market data was collected using the **yFinance** Python library.

The dataset contains daily stock market information including:

- Date
- Open Price
- High Price
- Low Price
- Close Price
- Trading Volume

The analysis covers the period:

**January 2024 – December 2024**

Each selected company contains approximately **252 trading-day records**.

---

## 🛠️ Technologies & Libraries Used

- **Python**
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical calculations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualization and heatmap
- **yFinance** – Historical stock market data
- **Jupyter Notebook** – Development environment

---

## 🔍 Analysis Performed

### 1. Data Collection

Historical stock data for AAPL, AMZN, and NFLX was collected using `yFinance`.

### 2. Data Preprocessing

The dataset was checked for:

- Missing values
- Data types
- Number of records
- Column names
- Data consistency

No major missing-value issues were found in the collected data.

### 3. Descriptive Statistical Analysis

The following statistics were calculated:

- Mean closing price
- Median closing price
- Minimum closing price
- Maximum closing price
- Standard deviation

### 4. Stock Price Visualization

Line charts were created to analyze closing price movements of:

- AAPL
- AMZN
- NFLX

The analysis showed that all three stocks experienced fluctuations while generally following an increasing trend during the selected period.

### 5. Trading Volume Analysis

Trading volume was visualized over time to identify:

- High-volume trading days
- Sudden spikes
- Unusual changes in trading activity

### 6. Daily Return Analysis

Daily stock returns were calculated using the formula:

```text
Daily Return =
(Today's Closing Price - Previous Day's Closing Price)
/
Previous Day's Closing Price
Daily return graphs were created to understand daily gains and losses.

7. Risk & Volatility Analysis

Standard deviation of daily returns was used to measure stock volatility.

Company	Standard Deviation
AAPL	0.014123
AMZN	0.017706
NFLX	0.018589

NFLX showed the highest volatility, while AAPL was the most stable.

8. Correlation Analysis

Pearson correlation was used to analyze the relationship between the selected companies.

	AAPL	AMZN	NFLX
AAPL	1.00	0.65	0.80
AMZN	0.65	1.00	0.90
NFLX	0.80	0.90	1.00

The strongest relationship was found between AMZN and NFLX (0.90).

The weakest relationship was between AAPL and AMZN (0.65).

📈 Key Findings
All three stocks showed fluctuations throughout the selected period.
Overall, AAPL, AMZN, and NFLX showed an increasing trend.
NFLX had the highest volatility with a standard deviation of 0.018589.
AAPL was the most stable stock with a standard deviation of 0.014123.
AMZN and NFLX had the strongest positive correlation (0.90).
AAPL and AMZN had the weakest correlation (0.65).
Several unusual spikes in trading volume were observed during the period.
📊 Visualizations

The project includes visualizations for:

Closing Price Trends
Trading Volume
Daily Stock Returns
Correlation Heatmap
📁 Project Structure
Stock-Market-Data-Analysis/
│
├── 📓 Stock_Market_Analysis.ipynb
├── 📊 Financial_Data.csv
├── 📄 Final_Report.pdf
└── 📖 README.md
📝 Final Report

A detailed Final Analysis Report was prepared containing:

Introduction
Methodology
Descriptive Statistics
Stock Price Analysis
Daily Return Analysis
Volatility Analysis
Correlation Analysis
Visualizations
Final Conclusions
🎥 Project Walkthrough

A video walkthrough of the complete project was also recorded to demonstrate the data collection, analysis, visualizations, and findings.

💡 Conclusion

This project provided practical experience in analyzing real-world financial data using Python.

The analysis demonstrated how statistical techniques and visualization can be used to understand stock performance, risk, volatility, and relationships between different companies.

Overall, NFLX showed the highest volatility, while AAPL was the most stable among the selected stocks. The correlation analysis also showed strong positive relationships between the selected technology companies.

👩‍💻 Author

Aliya Yousuf

Aspiring Data Analyst | Python | Data Analysis | Data Visualization
