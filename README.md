# Customer Shopping Behavior Analysis

## Overview

This project focuses on analyzing customer shopping behavior using Python, SQL, and Power BI to uncover key business insights and support data-driven decision-making. The workflow includes data loading, cleaning, exploratory data analysis (EDA), SQL-based querying, dashboard development, and presentation of findings through reports and slides.

---

## Dataset

The dataset contains customer shopping information, including demographics, purchasing behavior, product preferences, subscription status, payment methods, and other relevant attributes.

**Key Features:**

* Customer ID
* Age
* Gender
* Product Category
* Purchase Amount
* Payment Method
* Subscription Status
* Shipping Type
* Location
* Review Rating
* Discount Applied

---

## Tools & Technologies

| Tool                            | Purpose                        |
| ------------------------------- | ------------------------------ |
| Python                          | Data loading, cleaning, EDA    |
| Pandas                          | Data manipulation              |
| NumPy                           | Numerical operations           |
| Matplotlib / Seaborn            | Data visualization             |
| PostgreSQL / MySQL / SQL Server | Data storage and querying      |
| Power BI                        | Interactive dashboard creation |
| Gamma                           | Presentation (PPT) creation    |
| Microsoft Word                  | Project report documentation   |

---

## Project Workflow

### 1. Data Loading

* Imported the dataset into Python.
* Examined dataset structure and data types.
* Identified missing values and inconsistencies.

### 2. Data Cleaning

* Removed duplicates.
* Handled missing values.
* Standardized column names and formats.
* Corrected data quality issues.

### 3. Exploratory Data Analysis (EDA)

* Analyzed customer demographics.
* Evaluated purchasing trends.
* Identified top-performing product categories.
* Examined customer spending patterns.
* Generated visualizations for business insights.

### 4. SQL Analysis

* Imported cleaned data into SQL database.
* Executed analytical queries to:

  * Calculate sales metrics.
  * Identify customer segments.
  * Analyze subscription behavior.
  * Evaluate category performance.
  * Generate business KPIs.

### 5. Power BI Dashboard

Developed an interactive dashboard featuring:

* Sales Overview
* Customer Demographics
* Product Category Analysis
* Subscription Insights
* Shipping Preferences
* Interactive Filters and Slicers

### 6. Reporting & Presentation

* Created a detailed project report summarizing findings.
* Designed a professional presentation using Gamma to communicate key insights and recommendations.

---

## Dashboard Highlights

Key metrics displayed in the dashboard include:

* Total Sales
* Total Customers
* Average Purchase Value
* Subscription Distribution
* Category-wise Revenue
* Gender-wise Analysis
* Shipping Type Analysis
* Customer Rating Insights

---

## Key Findings

* Identified the highest revenue-generating product categories.
* Discovered customer segments with the highest spending behavior.
* Evaluated the impact of discounts on purchase decisions.
* Analyzed subscription trends and customer retention patterns.
* Revealed regional and demographic purchasing preferences.

---

## Project Structure

```text
Customer_Shopping_Behavior_Analysis/
│
├── Dataset/
│   └── customer_shopping_data.csv
│
├── Python/
│   ├── data_cleaning.ipynb
│   ├── eda.ipynb
│   └── visualizations.ipynb
│
├── SQL/
│   └── analysis_queries.sql
│
├── PowerBI/
│   └── Customer_Shopping_Dashboard.pbix
│
├── Report/
│   └── Project_Report.docx
│
├── Presentation/
│   └── Gamma_Presentation.pdf
│
└── README.md
```

---

## How to Run

### Python Analysis

1. Clone the repository.
2. Install required libraries:

```bash
pip install pandas numpy matplotlib seaborn
```

3. Open the Jupyter notebooks.
4. Run all cells sequentially.

### SQL Analysis

1. Import the cleaned dataset into PostgreSQL, MySQL, or SQL Server.
2. Execute the SQL scripts located in the `SQL` folder.
3. Review query outputs and generated insights.

### Power BI Dashboard

1. Open the `.pbix` file in Power BI Desktop.
2. Refresh the data source if required.
3. Explore dashboard visuals using interactive filters.

---

## Business Impact

This project demonstrates an end-to-end data analytics workflow, transforming raw customer data into actionable insights through data cleaning, SQL analysis, visualization, dashboard development, and business reporting. The findings can help organizations improve customer engagement, optimize product offerings, and support strategic decision-making.

---

## Author

**Abhishek Mukherjee**

