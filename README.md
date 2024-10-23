# Mini_project
**Mini Project:** Finance Sector Data Processing with Python, ETL, and SQL

**Project Overview:** This project simulates an ETL (Extract, Transform, Load) process in the finance sector using Python and SQL. You will work with a sample financial dataset, performing the following steps:

**Set Up Database Tables**
- Create necessary tables in a PostgreSQL database.
- Load raw data from CSV files into the database tables.

**Data Transformation**
- Perform data transformations using pandas, including filtering, joining tables, and aggregating data.
-  Store the transformed data back into the database and export it as a new CSV file.

**Data Extraction and Statistical Analysis**
- Extract the transformed data from the database.
- Generate basic statistical insights from the extracted data.

**Step-by-Step Instructions:**

**1. Database Setup**
  **Tools Required:** PostgreSQL, pgAdmin, or any other SQL management tool.
  
  **Tables to Create:**
  
Customers: Customer ID, Name, Age, Gender, Address, Account Type.
Transactions: Transaction ID, Customer ID (Foreign Key), Transaction Date, Amount, Transaction Type (Deposit/Withdrawal).
Account_Info: Account ID, Customer ID (Foreign Key), Account Balance, Interest Rate, Account Status.
  
**Data Ingestion:**

  Load data from the provided CSV files into these tables using SQL COPY command or any other method.

**2. Data Transformation Using Python (pandas)**

**Filtering:**

Extract records for customers with account balances over $10,000.

**Joining:**

Combine data from Customers and Transactions to create a detailed view of customer transaction history.

**Aggregation:**

Calculate the total amount of deposits and withdrawals for each customer.

**Saving Transformed Data:**

Load the transformed data back into a new table in the database called Customer_Transactions_Summary.
Save the transformed data as a CSV file.

**3. Data Extraction and Statistical Analysis**

  **Extract Data:**  

  Query the Customer_Transactions_Summary table to retrieve the data.
  
  **Statistical Insights:**
  
  Generate basic statistics such as the average account balance, total transactions per customer, and the distribution of transaction types.
  
  **Output:**
  
  Save the statistics as a report (e.g., a CSV or text file).
  
  **Sample Data (Finance Sector):**
  
You can create or download sample datasets for Customers,Transactions ,and Account_Info . Ensure that they include a variety of entries representing different financial scenarios.

**Deliverables:**

  - SQL scripts for table creation and data loading.
    
  - Python scripts for data transformation and extraction.
    
  - CSV files containing the original data and the transformed results
    
  - A report containing the generated statistical insights.
    
**Assessment Criteria:**

  - Correctness of SQL queries and database table setup.
    
  - Effective use of pandas for data transformation.
    
  - Ability to integrate Python with SQL for ETL tasks.
    
  - Quality and accuracy of the generated statistical report.
    
  - Code quality, including proper documentation and readability.
    
This project provides a practical application of Python, SQL, and ETL processes, allowing trainees to work on real-world financial data scenarios and enhancing their skills in data management and analysis
