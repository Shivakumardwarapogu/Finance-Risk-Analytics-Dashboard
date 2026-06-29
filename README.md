# 📈 Investment Portfolio Analytics using Python & Power BI

## 📖 Project Overview

This project presents an end-to-end financial analytics solution developed to support investment portfolio decision-making through data-driven insights. By analyzing historical stock market data across multiple industries, the project evaluates investment performance, portfolio risk, and return potential to recommend portfolios aligned with different investor risk profiles.

The solution combines Python-based data analysis, statistical modeling, and interactive Power BI visualizations to transform raw financial data into actionable business insights. It demonstrates the complete analytics lifecycle—from data cleaning and exploratory data analysis (EDA) to portfolio optimization and executive dashboard reporting.

As part of a two-member capstone project, I contributed to data preprocessing, exploratory data analysis, financial performance analysis, business insight generation, and the development of the interactive Power BI dashboard.

### 🎯 Business Objective

To analyze historical stock performance across multiple industry sectors and develop personalized investment recommendations for investors with varying financial goals and risk tolerance, enabling informed and data-driven portfolio decisions.

## 🎯 Business Problem

Investors often face challenges when selecting stocks and constructing portfolios that align with their financial goals and risk tolerance. With hundreds of investment options available across multiple industries, making informed investment decisions requires a structured analysis of historical performance, risk exposure, and return potential.

Traditional investment decisions based solely on intuition or market trends may lead to suboptimal portfolio performance and increased financial risk. Therefore, there is a need for a data-driven approach that evaluates stock behavior, identifies high-performing assets, and balances risk against expected returns.

This project addresses this challenge by analyzing historical stock market data from multiple sectors, measuring key financial performance indicators, and generating personalized portfolio recommendations for investors with different risk profiles. The analysis enables investors to make more informed decisions based on quantitative evidence rather than speculation.

## 👥 Client Scenario

The project was designed to provide investment recommendations for two hypothetical investors with distinct financial objectives and risk tolerance levels.

### Investor 1 – Conservative Investor

A risk-conscious investor seeking stable long-term growth while minimizing portfolio volatility. The objective was to construct a diversified portfolio consisting of relatively lower-risk stocks capable of delivering consistent returns.

### Investor 2 – Aggressive Investor

A growth-focused investor willing to accept higher levels of risk in pursuit of significantly higher returns. The objective was to identify high-performing stocks with strong growth potential and maximize portfolio returns over the investment horizon.

By analyzing stock performance, risk metrics, cumulative returns, and Sharpe ratios, tailored portfolio recommendations were developed for each investor profile.

## 🛠️ Technology Stack

| Technology                | Purpose                                                                                            |
| ------------------------- | -------------------------------------------------------------------------------------------------- |
| **Python**                | Data cleaning, preprocessing, financial analysis, portfolio analysis, and statistical calculations |
| **Pandas**                | Data manipulation and transformation                                                               |
| **NumPy**                 | Numerical computations and financial calculations                                                  |
| **Matplotlib**            | Data visualization and trend analysis                                                              |
| **Seaborn**               | Statistical visualizations and correlation analysis                                                |
| **Plotly**                | Interactive exploratory visualizations                                                             |
| **Jupyter Notebook**      | Exploratory Data Analysis (EDA) and analytical workflow                                            |
| **Power BI**              | Interactive executive dashboard and KPI reporting                                                  |
| **Power Query**           | Data transformation and preparation for dashboard reporting                                        |
| **Microsoft Excel / CSV** | Source dataset for stock market analysis                                                           |


## 📂 Dataset

The project uses historical stock market data covering **24 publicly traded companies** across **five major industries** over a **10-year period (October 2010 – September 2020)**.

For portfolio analysis and investment recommendations, the most recent **five years of data (October 2015 – September 2020)** were analyzed to better reflect contemporary market behavior.

### Industries Included

* ✈️ Aviation
* 💰 Finance
* 🏥 Healthcare
* 💊 Pharmaceuticals
* 💻 Technology

### Key Dataset Attributes

* Stock Symbol
* Date
* Open Price
* High Price
* Low Price
* Close Price
* Trading Volume
* Industry Classification

The dataset enabled comprehensive financial analysis, including return calculations, volatility assessment, correlation analysis, portfolio optimization, and investment recommendation generation.

## 🔍 Methodology

The project followed a structured data analytics workflow to transform raw financial data into actionable investment insights.

### 1. Data Collection

* Imported historical stock market data for 24 companies across five industries.
* Validated dataset quality before analysis.

### 2. Data Cleaning & Preprocessing

* Identified and handled missing values.
* Performed data normalization where appropriate.
* Conducted outlier analysis to identify abnormal market behavior.

### 3. Exploratory Data Analysis (EDA)

* Examined stock price trends over time.
* Compared industry-wise performance.
* Analyzed correlations between stocks.
* Evaluated market behavior during significant events such as the COVID-19 pandemic.

### 4. Financial Analytics

* Calculated Daily Returns
* Calculated Cumulative Returns
* Measured Annualized Returns
* Computed Portfolio Risk
* Calculated Sharpe Ratio
* Compared stock performance against the S&P 500 Index

### 5. Portfolio Construction

* Designed investment portfolios based on different investor risk profiles.
* Balanced expected return against investment risk.
* Generated personalized investment recommendations.

### 6. Dashboard Development

* Developed an interactive Power BI dashboard to present KPIs, portfolio insights, and financial performance in a clear and business-friendly format.

