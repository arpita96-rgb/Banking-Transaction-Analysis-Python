# Banking-Transaction-Analysis-Python
End-to-end banking transaction analysis using Python, SQL, Pandas, NumPy and data visualization.
# Banking Transaction Analysis | Python & SQL

##  Project Overview

The **Banking Transaction Analysis** project focuses on analyzing banking transaction data to understand financial activity, transaction patterns, customer behaviour, and operational trends.

Using Python libraries such as Pandas, NumPy, Matplotlib, and Seaborn, the project follows an end-to-end Exploratory Data Analysis (EDA) workflow, from raw data inspection and cleaning to KPI development and visualization.

The objective is to transform raw transaction records into meaningful insights that can support data-driven business discussions and demonstrate practical data analytics skills.

##  Business Objectives

- Analyze overall banking transaction activity and transaction values.
- Evaluate transaction performance based on transaction status.
- Identify trends across transaction dates, months, weekdays, and hours.
- Compare transaction activity across different banking channels and transaction types.
- Examine customer behaviour and identify repeat and high-value customers.
- Analyze transaction fees, deposits, withdrawals, and account types.
- Explore transaction patterns across cities and merchant categories.
- Identify data-quality issues that may affect analytical results.

##  Technology Stack

| Technology | Purpose |
|---|---|
| Python | Data analysis and processing |
| Pandas | Data manipulation and cleaning |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Jupyter Notebook | Interactive analysis environment |
| MySQL | SQL-based analytical queries |

##  Dataset Description

**Dataset:** `banking_transaction_analysis_raw.csv`

The dataset contains **2,020 records and 17 columns** related to banking transactions.

| Column | Description |
|---|---|
| Transaction_ID | Unique transaction identifier |
| Customer_ID | Unique customer identifier |
| Account_ID | Customer account reference |
| Transaction_Date | Transaction date and time |
| Transaction_Type | Type of transaction |
| Amount_INR | Transaction amount in INR |
| Transaction_Fee_INR | Transaction fee |
| Account_Balance_INR | Recorded account balance |
| Account_Type | Type of bank account |
| Merchant_Category | Merchant category |
| City | City associated with the record |
| Branch | Bank branch |
| Channel | Transaction channel |
| Transaction_Status | Transaction status |
| Device_Type | Device used for the transaction |
| Is_International | International transaction indicator |
| Customer_Age | Customer age |

## Project Workflow

The project follows a structured data analytics process:

**Step 1 – Data Understanding**
- Imported the dataset using Pandas.
- Reviewed dataset dimensions, columns, and data types.
- Examined sample records and descriptive statistics.

**Step 2 – Data Cleaning**
- Identified missing values.
- Checked duplicate transaction identifiers.
- Applied missing-value treatment as implemented in the notebook.
- Reviewed data types and date formats.
- Examined unusual and potentially invalid values.

**Step 3 – Data Transformation**
- Converted transaction dates into datetime format.
- Extracted time-based features such as month, weekday, quarter, and hour.
- Prepared data for transaction and customer-level analysis.

**Step 4 – Exploratory Data Analysis**
- Analyzed transaction types and statuses.
- Evaluated transaction values and fees.
- Explored customer and location-based patterns.
- Compared transaction channels and account categories.

**Step 5 – KPI Development**
- Calculated transaction and customer-level metrics.
- Summarized financial activity.
- Evaluated transaction performance and repeat-customer patterns.

**Step 6 – Data Visualization**
- Created charts and plots to identify trends.
- Compared categories and transaction patterns.
- Presented analytical findings visually.

##  Key Performance Indicators (KPIs)

The analysis explores the following business metrics:

- Total Number of Transactions
- Total Transaction Amount
- Average Transaction Amount
- Total Unique Customers
- Successful Transaction Count
- Failed Transaction Count
- Transaction Success Rate
- Transaction Failure Rate
- Total Transaction Fees
- Deposit and Withdrawal Amounts
- International Transaction Value
- Repeat Customer Count
- Average Transaction Value per Customer
- Top Customers by Transaction Value

*Note: KPI values should be generated from the cleaned dataset and interpreted according to the notebook's calculation logic.*

##  Key Areas of Analysis

| Analysis Area | Business Focus |
|---|---|
| Transaction Analysis | Transaction volume and transaction value |
| Time-Based Analysis | Monthly, daily, and hourly patterns |
| Status Analysis | Successful, failed, and reversed transactions |
| Channel Analysis | UPI, ATM, POS, mobile app, and branch activity |
| Customer Analysis | Repeat customers and high-value customers |
| Financial Analysis | Fees, deposits, and withdrawals |
| Location Analysis | City-wise transaction activity |
| Account Analysis | Transaction behaviour across account types |
| Merchant Analysis | Transaction distribution by merchant category |
| International Analysis | Domestic and international transaction activity |

##  Data Visualizations

The project uses visualizations to communicate analytical findings, including:

- Monthly Transaction Trends
- Transaction Type Distribution
- Transaction Status Distribution
- Transaction Value by Channel
- Daily and Hourly Transaction Trends
- Weekday vs. Weekend Analysis
- Transaction Fees by Transaction Type
- Merchant Category Analysis
- Deposit vs. Withdrawal Analysis
- Domestic vs. International Transactions
- Account Type Analysis
- Top 10 Customers by Transaction Value
- Customer Distribution by City
- Repeat vs. One-Time Customers
- Customer Transaction Behaviour
- City-Wise Transaction Heatmap

##  Repository Structure

```text
Banking_Transaction_Analysis_Complete/
│
├── data/
│   ├── raw/
│   │   └── banking_transaction_analysis_raw.csv
│   └── processed/
│
├── notebooks/
│   └── banking_transaction_analysis.ipynb
│
├── src/
│   └── analysis.py
│
├── docs/
│   ├── data_dictionary.md
│   └── project_summary.md
│
├── outputs/
│   └── figures/
│
├── requirements.txt
├── LICENSE
└── README.md
```

## Project Outcome

This project demonstrates practical experience in:

- Data loading and exploration
- Data cleaning and preprocessing
- Missing-value and duplicate analysis
- Feature engineering
- Exploratory Data Analysis
- Business KPI development
- Customer segmentation and aggregation
- Data visualization
- SQL-based analytical querying

It showcases the ability to work with raw datasets, investigate data-quality issues, perform structured analysis, and communicate findings through meaningful metrics and visualizations.
