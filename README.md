# 📊 Stock Market Data Analysis & Exploratory Data Analysis (EDA)
📌 Project Overview

This project focuses on analyzing historical stock market data of three major technology companies using Python.

The main purpose of this project is to understand stock price movements, trading volume, daily returns, risk, volatility, and the relationship between different stocks through statistical analysis and data visualization.

The companies selected for this project are:

Apple Inc. (AAPL)
Amazon.com Inc. (AMZN)
Netflix Inc. (NFLX)

The historical stock market data was collected using the yFinance Python library for the period from January 2024 to December 2024.

 🎯 Project Objectives

The main objectives of this project are:

Collect historical stock market data using Python
Check and preprocess the collected data
Perform descriptive statistical analysis
Analyze closing price trends
Analyze trading volume
Calculate daily stock returns
Analyze stock risk and volatility
Perform Pearson correlation analysis
Create data visualizations
Create a correlation heatmap
Interpret the results and draw conclusions
📂 Dataset

The historical stock market data was collected using the yFinance library.

The dataset contains the following information:

Date – Trading date
Open – Opening stock price
High – Highest price during the day
Low – Lowest price during the day
Close – Closing stock price
Volume – Number of shares traded
Companies Selected
Company	Ticker
Apple Inc.	AAPL
Amazon.com Inc.	AMZN
Netflix Inc.	NFLX

The analysis contains approximately 252 daily trading records for each company during the selected period.

🛠️ Technologies and Libraries Used
Python
Pandas
NumPy
Matplotlib
Seaborn
yFinance
Jupyter Notebook
Library Purpose

Pandas – Data manipulation and analysis

NumPy – Numerical calculations

Matplotlib – Data visualization

Seaborn – Statistical visualization and correlation heatmap

yFinance – Historical stock market data collection

Jupyter Notebook – Project development and analysis

🔍 Methodology
1. Data Collection

Historical daily stock market data for AAPL, AMZN, and NFLX was collected using the yFinance Python library.

The selected period was:

January 1, 2024 – January 1, 2025

2. Data Preprocessing

The collected datasets were checked and prepared before analysis.

The following preprocessing steps were performed:

Checked the number of rows and columns
Checked column names
Checked data types
Checked for missing values
Reviewed the first five records
Verified the required stock market columns

No missing values were found in the collected datasets.

📊 Analysis Performed
3. Descriptive Statistical Analysis

Descriptive statistics were calculated for the closing prices of all three companies.

The following measures were calculated:

Mean closing price
Median closing price
Minimum closing price
Maximum closing price
Standard deviation

These statistics were used to compare the price levels and variation of the selected stocks.

4. Closing Price Trend Analysis

Line charts were created to visualize the daily closing prices of AAPL, AMZN, and NFLX.

The charts were used to understand:

Stock price movements
Increasing and decreasing periods
Overall stock trends
Differences between the selected companies

The three stocks experienced fluctuations throughout the selected period while generally showing an increasing trend.

5. Trading Volume Analysis

Trading volume was analyzed to understand changes in trading activity over time.

A line chart was created to identify:

High-volume trading days
Sudden increases in trading volume
Unusual changes in trading activity
Differences in trading activity between companies

The analysis showed several noticeable spikes in trading volume during the selected period.

💹 6. Daily Return Analysis

Daily stock returns were calculated using the following formula:

Daily Return = (Today's Closing Price - Previous Day's Closing Price) / Previous Day's Closing Price

Daily returns were calculated for AAPL, AMZN, and NFLX.

A line graph was created to visualize daily return movements.

The daily return analysis showed that stock returns frequently moved above and below zero, indicating both daily gains and losses.

⚠️ 7. Risk and Volatility Analysis

Standard deviation of daily returns was used to measure stock volatility.

The results were:

Company	Standard Deviation
AAPL	0.014123
AMZN	0.017706
NFLX	0.018589
Findings
NFLX had the highest volatility with a standard deviation of 0.018589.
AMZN had a standard deviation of 0.017706.
AAPL had the lowest volatility with a standard deviation of 0.014123.

Therefore, NFLX was the riskiest stock, while AAPL was the most stable stock among the three companies.

🔗 8. Correlation Analysis

Pearson correlation was used to analyze the relationship between the closing prices of AAPL, AMZN, and NFLX.

The correlation matrix was:

	AAPL	AMZN	NFLX
AAPL	1.00	0.65	0.80
AMZN	0.65	1.00	0.90
NFLX	0.80	0.90	1.00

A Seaborn heatmap was created to visualize the correlation matrix.

📈 Findings
AMZN and NFLX had the strongest relationship with a correlation value of 0.90.
AAPL and AMZN had the weakest relationship with a correlation value of 0.65.
All three companies showed positive correlations.
A high positive correlation indicates that two stocks generally tend to move in the same direction.
Key Findings

The main findings of the project are:

AAPL, AMZN, and NFLX experienced fluctuations throughout the selected period.
All three stocks generally showed an increasing trend during the selected period.
NFLX had the highest volatility with a standard deviation of 0.018589.
AAPL was the most stable stock with the lowest standard deviation of 0.014123.
AMZN and NFLX had the strongest positive correlation of 0.90.
AAPL and AMZN had the weakest correlation of 0.65.
Several noticeable spikes were observed in trading volume.
Daily returns showed both positive and negative movements.

📝 Conclusion

This project provided practical experience in analyzing real-world financial data using Python.

The analysis covered stock price trends, trading volume, daily returns, volatility, and correlation between three major technology companies.

Based on the volatility analysis, NFLX was the riskiest stock because it had the highest standard deviation of daily returns. AAPL was the most stable stock because it had the lowest standard deviation.

The correlation analysis showed positive relationships between all three companies. The strongest relationship was found between AMZN and NFLX with a correlation of 0.90, while the weakest relationship was between AAPL and AMZN with a correlation of 0.65.

Overall, this project demonstrates how Python, statistical analysis, and data visualization can be used to analyze financial data and extract meaningful insights from stock market information.

📁 Project Files

The GitHub repository contains the following files:

Stock_Market_Analysis.ipynb – Complete Jupyter Notebook containing data collection, preprocessing, analysis, calculations, and visualizations.
Financial_Data.csv – Dataset used for the stock market analysis.
Final_Report.pdf – Final project report containing methodology, analysis, results, findings, and conclusion.
README.md – Project documentation.
Project Structure
Stock-Market-Data-Analysis/
│
├── Stock_Market_Analysis.ipynb
├── Financial_Data.csv
├── Final_Report.pdf
└── README.md
🎥 Project Walkthrough

A video walkthrough of the complete project was recorded to demonstrate the data collection process, preprocessing, statistical analysis, visualizations, volatility analysis, correlation analysis, and final findings.

👩‍💻 Author

Aliya Yousuf

Aspiring Data Analyst | Python | Data Analysis | Data Visualization

⭐ Skills Demonstrated

Python • Pandas • NumPy • Matplotlib • Seaborn • yFinance • Exploratory Data Analysis • Statistical Analysis • Data Visualization • Financial Data Analysis
