# Financial-Performance-Dashboard
Financial Performance Analysis Dashboard using Python and Power BI

# 📊 Financial Performance Analysis Dashboard

## 📌 Project Overview

This project focuses on analyzing the financial performance of companies using financial datasets such as Profit & Loss, Balance Sheet, and Cash Flow statements. The raw datasets were cleaned, transformed, and analyzed using Python, and interactive dashboards were developed in Power BI to generate meaningful business insights.

The project helps users understand:

* Revenue and profit trends over time
* Company-wise financial performance
* Debt and leverage patterns
* Profitability and growth analysis
* Financial health indicators

---

# 🎯 Objectives

* Clean and preprocess raw financial datasets
* Perform Exploratory Data Analysis (EDA)
* Create financial KPIs and metrics
* Build interactive Power BI dashboards
* Generate business insights from financial data
* Analyze profitability, growth, and leverage trends

---

# 🛠️ Tools & Technologies Used

| Tool         | Purpose                           |
| ------------ | --------------------------------- |
| Python       | Data Cleaning & Analysis          |
| Google Colab | Development Environment           |
| Pandas       | Data Manipulation                 |
| NumPy        | Numerical Computation             |
| Matplotlib   | Data Visualization                |
| Seaborn      | Exploratory Data Analysis         |
| Power BI     | Dashboard Development             |
| GitHub       | Project Hosting & Version Control |

---

# 📂 Dataset Information

The project uses multiple financial datasets.

## 1. Profit & Loss Dataset

Used for:

* Revenue Analysis
* Profit Analysis
* EPS Analysis
* Profitability Analysis

Key information includes:

* Sales
* Expenses
* Operating Profit
* Net Profit
* EPS
* Dividend-related metrics

---

## 2. Balance Sheet Dataset

Used for:

* Asset Analysis
* Liability Analysis
* Debt Analysis
* Financial Strength Assessment

Key information includes:

* Equity Capital
* Reserves
* Borrowings
* Assets
* Liabilities
* Investments

---

## 3. Cash Flow Dataset

Used for:

* Cash Flow Analysis
* Liquidity Assessment
* Free Cash Flow Evaluation

Key information includes:

* Operating Activities
* Investing Activities
* Financing Activities
* Free Cash Flow

---

# 🧹 Data Cleaning Process

The raw datasets required preprocessing before analysis.

## Data Cleaning Steps

### Step 1: Load Datasets

```python
import pandas as pd
```

### Step 2: Explore Data

```python
df.head()
df.info()
df.describe()
```

### Step 3: Check Missing Values

```python
df.isnull().sum()
```

### Step 4: Standardize Data

* Cleaned text values
* Removed unnecessary spaces
* Standardized fiscal year formats

### Step 5: Data Type Conversion

```python
astype()
```

### Step 6: Handle Missing Values

* Identified null values
* Applied appropriate cleaning techniques

### Step 7: Export Cleaned Data

```python
df.to_csv()
```

The cleaned datasets were exported and used for EDA and Power BI dashboard development.

---

# 📈 Exploratory Data Analysis (EDA)

EDA was performed using Pandas, Matplotlib, and Seaborn to understand patterns, trends, and relationships within the financial data.

## Analysis Performed

### Profit & Loss Analysis

* Sales Trends
* Profit Trends
* Revenue Comparison
* Profitability Assessment

### Balance Sheet Analysis

* Asset Growth
* Liability Growth
* Borrowings Analysis
* Reserve Analysis

### Cash Flow Analysis

* Operating Cash Flow
* Investing Cash Flow
* Financing Cash Flow
* Free Cash Flow

### Company-Level Analysis

* Company Performance Comparison
* Financial Trend Evaluation
* Growth Pattern Identification

---

# 📊 Power BI Dashboards

The cleaned datasets were imported into Power BI and used to build three interactive dashboards focused on financial performance, debt analysis, and profitability trends.

---

# Dashboard 1: Financial Performance Dashboard

## Purpose

Provides a comprehensive overview of company financial performance across multiple fiscal years.

## Key Performance Indicators (KPIs)

* Total Sales
* Total Profit
* Total Assets
* Total Expenses
* Free Cash Flow

## Visualizations

### Sales Trend by Fiscal Year

Displays sales performance across years.

### Profit Trend by Fiscal Year

Shows changes in profitability over time.

### Top Companies by Profit

Ranks companies based on total profit generated.

### Top Companies by Assets

Highlights companies with the largest asset base.

### Interactive Filters

* Company Filter
* Fiscal Year Filter

## Business Value

* Tracks financial performance
* Identifies top-performing companies
* Enables company comparison
* Supports financial decision-making

---

# Dashboard 2: Debt & Leverage Monitor

## Purpose

Analyzes company debt levels and leverage-related financial indicators.

## Key Performance Indicators (KPIs)

* Total Borrowings
* Total Reserves
* Debt-to-Equity Ratio
* Total Assets

## Visualizations

### Borrowings Trend Analysis

Shows how company borrowings change over time.

### Borrowings vs Reserves Comparison

Compares debt obligations against available reserves.

### Company-wise Borrowings

Ranks companies according to borrowing levels.

### Assets vs Borrowings Analysis

Evaluates the relationship between assets and borrowings.

### Interactive Filters

* Company Filter
* Fiscal Year Filter

## Business Value

* Identifies highly leveraged companies
* Evaluates financial stability
* Supports risk analysis
* Monitors debt growth trends

---

# Dashboard 3: Profitability & Growth Analysis

## Purpose

Evaluates profitability, operational efficiency, and company growth trends.

## Key Performance Indicators (KPIs)

* Total Profit
* Total Sales
* Profit Margin (%)
* Average EPS

## Visualizations

### Top 10 Companies by Sales

Highlights the highest revenue-generating companies.

### Profit Trend Over Years

Tracks operating profit performance across fiscal years.

### Sales vs Operating Profit Analysis

Scatter plot used to analyze the relationship between revenue and profitability.

### Sales vs Expenses Comparison

Compares revenue and expenses to evaluate operational efficiency.

### Interactive Filters

* Company Filter
* Fiscal Year Filter

## Business Value

* Identifies profitable companies
* Evaluates operational performance
* Analyzes growth trends
* Supports profitability assessment

---

# 📈 Data Modeling

Power BI relationships were created to connect multiple financial datasets and enable cross-filtering across reports.

## Benefits

* Unified financial analysis
* Consistent filtering across dashboards
* Improved reporting accuracy
* Efficient KPI calculations using DAX measures

---

# 📊 Key Insights Generated

* Financial performance can be tracked through revenue and profit trends.
* Revenue growth varies significantly across companies.
* Debt and reserve analysis helps identify financially stable organizations.
* Asset and liability information provides insights into financial strength.
* Profit margin and EPS metrics support profitability comparisons.
* Interactive dashboards enable detailed company-level analysis.

---

# 📁 Project Structure

```text
Financial-Performance-Analysis
│
├── raw
│   └── Raw Financial Datasets
│
├── cleaned
│   └── Cleaned Financial Datasets
│
├── EDA files
│   └── EDA Datasets
│
├── Notebook
│   ├── Data Cleaning Notebook.ipynb
│   └── EDA Notebook.ipynb
│
├── power bi
│   ├── Financial Performance Dashboard.pbix
│   ├── Debt & Leverage Monitor.pbix
│   └── Profitability & Growth Analysis.pbix
│
└── README.md
```

---

# 🚀 How to Run This Project

## Clone Repository

```bash
git clone https://github.com/Richa26kumari/Financial-Performance-Dashboard.git
```

## Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn
```

## Open Notebooks

Run:

```text
Data Cleaning Notebook.ipynb
```

or

```text
EDA Notebook.ipynb
```

using Google Colab or Jupyter Notebook.

## Open Power BI Dashboards

Open the `.pbix` files using Power BI Desktop.

---

# 📚 Skills Demonstrated

* Data Cleaning
* Data Preprocessing
* Exploratory Data Analysis (EDA)
* Financial Data Analysis
* Data Visualization
* Dashboard Design
* Business Intelligence
* Power BI
* DAX Measures
* Data Modeling
* Python
* GitHub Version Control

---

# 👩‍💻 Author

### Richa Kumari

Final-Year Engineering Student

**LinkedIn:** https://www.linkedin.com/in/richa-kumari-81548331a

---

⭐ If you found this project interesting, feel free to explore the repository and connect with me on LinkedIn.
