# customer_shopping_behaviour
It's a data analytics driven project which shows the shopping behaviour of customers of an e-commerce company using python, sql and power BI. 
# Data Analytics Project: End-to-End Data Analysis
## Overview
This project demonstrates an end-to-end data analytics workflow, from data loading and cleaning to SQL analysis, dashboard development, and reporting.
The goal is to transform raw data into meaningful insights using Python, SQL, Power BI, and PowerPoint. The project highlights data preparation, exploratory data analysis (EDA), querying, visualization, and business reporting skills.

## Dataset
- **Dataset Name:** Customer Shopping Behavior
- **Format:** CSV / Excel / Database
- **Description:** The dataset contains information used to identify trends, patterns, and insights relevant to the business problem.

## Tools & Technologies
- **Python:** Data loading, cleaning, and exploratory data analysis
- **Pandas & NumPy:** Data manipulation and preprocessing
- **SQL:** Data querying and analysis using PostgreSQL, MySQL, or SQL Server
- **Power BI:** Interactive dashboard development
- **PowerPoint:** Presentation and reporting of key findings
- **Jupyter Notebook:** Python-based analysis and documentation

## Project Workflow
### 1. Data Loading
- Imported the dataset into Python using Pandas.
- Inspected the dataset structure, columns, and data types.
- Checked the number of rows and columns.
### 2. Exploratory Data Analysis (EDA)
- Analyzed descriptive statistics and data distributions.
- Identified trends, patterns, and potential outliers.
- Used charts and visualizations to explore relationships between variables.
### 3. Data Cleaning
- Handled missing and duplicate values.
- Corrected data types and inconsistent formats.
- Standardized column names and categorical values.
- Prepared the dataset for further analysis.
### 4. SQL Analysis
- Loaded the cleaned data into a relational database.
- Wrote SQL queries to filter, aggregate, and analyze data.
- Used `GROUP BY`, `JOIN`, `ORDER BY`, and aggregate functions where appropriate.
- Extracted insights to answer relevant business questions.
### 5. Power BI Dashboard
- Connected Power BI to the prepared dataset.
- Created charts, KPI cards, and interactive filters.
- Designed a dashboard to communicate key trends and performance indicators.
- Organized visuals for easy interpretation by business stakeholders.
### 6. Reporting
- Summarized key findings and insights.
- Prepared a PowerPoint presentation highlighting the analysis.
- Documented the methodology, observations, and potential recommendations.

## Dashboard
The Power BI dashboard provides a visual summary of the analysis, including relevant KPIs, trends, comparisons, and interactive filters.
**Dashboard Preview:** 
<img width="1322" height="742" alt="image" src="https://github.com/user-attachments/assets/8a89da26-05f7-4a1e-b3d2-6821d2862710" />

## Results & Key Insights
The analysis aims to identify meaningful patterns and support data-driven decision-making.
Key findings include:
- **Trend Analysis:** Identify important changes and patterns over time.
- **Category Comparison:** Compare results across different groups or categories.
- **Business Recommendations:** Suggest actions based on the findings.

## Project Structure
customer_shopping_behavior/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   └── exploratory_data_analysis.ipynb
│
├── sql/
│   └── analysis_queries.sql
│
├── dashboard/
│   └── dashboard.pbix
│
├── reports/
│   └── project_report.pptx
│
├── images/
│   └── dashboard_preview.png
│
├── requirements.txt
└── README.md
```

## How to Run
### Prerequisites
Install Python and the required libraries. You will also need access to your chosen SQL database and Power BI Desktop to reproduce the complete workflow.
### Step 1: Clone the Repository
```bash
git clone <your-repository-url>
cd data-analytics-project
```
### Step 2: Create a Virtual Environment (Optional)

```bash
python -m venv venv
```

Activate the environment:
**Windows**
```bash
venv\Scripts\activate
```

**macOS/Linux**
```bash
source venv/bin/activate
```

### Step 3: Install Dependencies

```bash
pip install -r requirements.txt
```

Example `requirements.txt`:

```text
pandas
numpy
matplotlib
seaborn
jupyter
sqlalchemy
psycopg2-binary
pymysql
pyodbc
```

Install only the database driver appropriate for your setup.

### Step 4: Run the Python Analysis

```bash
jupyter notebook
```

Open the notebook in the `notebooks/` directory and execute the cells in order.

### Step 5: Run the SQL Queries

- Set up your selected database.
- Import the cleaned dataset into a table.
- Update the database connection settings.
- Execute the queries in `sql/analysis_queries.sql`.

### Step 6: Open the Power BI Dashboard

Open `dashboard.pbix` in Power BI Desktop, configure the data source, and refresh the dataset.

### Step 7: Review the Report

Open the PowerPoint presentation in the `reports/` directory to review the findings and recommendations.

## Future Improvements

- Automate data cleaning and refresh workflows.
- Add more advanced statistical analysis.
- Integrate additional datasets.
- Improve dashboard interactivity and performance.
- Develop automated reporting and data pipelines.

## Conclusion

This project showcases practical data analytics skills across the complete analytical lifecycle, including Python programming, data cleaning, SQL querying, business intelligence, visualization, and reporting.

It demonstrates how raw data can be transformed into structured analysis and actionable business insights.

## Author

Gali Kiran Venkat

- GitHub: github.com/Kiranvenkatgali
- LinkedIn: linkedin.com/in/kiran-v-609461225/

---

*This project was developed for learning, portfolio development, and demonstrating practical data analytics capabilities.*
