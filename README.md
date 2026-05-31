# Financial-Performance-Dashboard
Financial Performance Analysis Dashboard using Python and Power BI

# 📊 Financial Performance Analysis Dashboard

## 📌 Project Overview

This project analyzes the financial performance of major Indian companies using Profit & Loss, Balance Sheet, and Cash Flow data. The data was cleaned, transformed, analyzed, and visualized using Python and Power BI to generate meaningful business insights.

The dashboard helps users understand:

- Revenue and profit trends over time
- Company-wise financial performance
- Asset and liability distribution
- Cash flow performance
- Financial health indicators

---

# 🎯 Objectives

- Clean and preprocess raw financial datasets
- Perform Exploratory Data Analysis (EDA)
- Create financial KPIs and metrics
- Build an interactive Power BI dashboard
- Generate business insights from financial data

---

# 🛠️ Tools & Technologies Used

| Tool | Purpose |
|--------|---------|
| Python | Data Cleaning & Analysis |
| Google Colab | Development Environment |
| Pandas | Data Manipulation |
| Power BI | Dashboard Creation |
| GitHub | Project Hosting |

---

# 📂 Dataset Information

The project uses multiple financial datasets:

### 1. Profit & Loss Data
Contains:
- Sales
- Expenses
- Operating Profit
- Net Profit
- EPS
- Dividend Payout

### 2. Balance Sheet Data
Contains:
- Equity Capital
- Reserves
- Borrowings
- Total Assets
- Total Liabilities
- Investments

### 3. Cash Flow Data
Contains:
- Operating Activity
- Investing Activity
- Financing Activity
- Net Cash Flow
- Free Cash Flow

---

# 🧹 Data Cleaning Process

The raw datasets contained:

- Missing values
- Inconsistent fiscal year formats
- Duplicate records
- Incorrect data types
- Unnecessary columns

### Cleaning Steps Performed

### Step 1: Load Data
```python
import pandas as pd
```

### Step 2: Inspect Dataset
```python
df.head()
df.info()
df.describe()
```

### Step 3: Handle Missing Values
```python
df.isnull().sum()
```

### Step 4: Standardize Fiscal Year
Converted values such as:

```
Mar-23
Dec-23
Sep-23
```

into:

```
2023
```

### Step 5: Convert Data Types
```python
astype()
```

### Step 6: Remove Unnecessary Columns

Columns with little analytical value were removed.

### Step 7: Export Cleaned Data

```python
df.to_csv()
```

---

# 📈 Exploratory Data Analysis (EDA)

EDA was performed to understand:

- Sales trends
- Profit trends
- Asset growth
- Liability growth
- Cash flow patterns

### Key Analysis Conducted

### Profit & Loss Analysis

- Total Sales
- Total Profit
- Profit Growth

### Balance Sheet Analysis

- Total Assets
- Total Liabilities
- Debt-to-Equity Ratio

### Cash Flow Analysis

- Operating Cash Flow
- Free Cash Flow
- Net Cash Flow

---

# 📊 Power BI Dashboard

The cleaned datasets were imported into Power BI and used to build an interactive dashboard.

---

## Dashboard KPIs

### KPI Cards

- Total Sales
- Total Profit
- Total Assets
- Total Expenses
- Free Cash Flow

---

## Dashboard Visuals

### Line Charts

#### Total Sales by Fiscal Year

Shows sales growth trend over time.

#### Total Profit by Fiscal Year

Shows profit growth trend over time.

---

### Bar Charts

#### Top Companies by Profit

Displays highest profit-generating companies.

#### Top Companies by Assets

Displays companies with the highest asset values.

---

### Slicers

- Company Filter
- Fiscal Year Filter

Allows dynamic dashboard interaction.

---

# 📌 Financial Measures Created

### Total Sales

```DAX
Total Sales =
SUM(eda_profitandloss[sales])
```

### Total Profit

```DAX
Total Profit =
SUM(eda_profitandloss[net_profit])
```

### Total Assets

```DAX
Total Assets =
SUM(eda_balancesheet[total_assets])
```


### Free Cash Flow

```DAX
Free Cash Flow =
SUM(eda_cashflow[free_cash_flow])
```

---

# 📈 Key Insights

### Revenue Growth

Most companies show a consistent increase in sales over the years.

### Profit Growth

Several companies demonstrate strong profit growth trends.

### Asset Expansion

Leading companies have significantly increased their asset base.

### Cash Flow Performance

Positive operating cash flow indicates healthy business operations.

### Financial Stability

Many companies maintain strong balance sheets with manageable liabilities.

---

# 📷 Dashboard Preview

Add your dashboard screenshot here.

Example:

```
images/dashboard.png
```

Then display it:

```markdown
![Dashboard Screenshot](images/dashboard.png)
```

---


---

# 🚀 How to Run This Project

### Clone Repository

```bash
git clone https://github.com/yourusername/Financial-Performance-Dashboard.git
```

### Install Dependencies

```bash
pip install pandas numpy matplotlib
```

### Run Notebook

Open:

```
Data_Cleaning.ipynb
```

or

```
EDA.ipynb
```

in Google Colab or Jupyter Notebook.

---

# 📚 Skills Demonstrated

- Data Cleaning
- Data Preprocessing
- Exploratory Data Analysis
- Financial Data Analysis
- DAX Measures
- Data Visualization
- Dashboard Design
- Business Intelligence
- Power BI
- Python
- GitHub Project Management

---

# 👩‍💻 Author

### Richa Kumari

Final-Year Engineering Student

LinkedIn:
https://www.linkedin.com/in/richa-kumari-81548331a


---

# ⭐ If you found this project useful, please give it a star on GitHub.
