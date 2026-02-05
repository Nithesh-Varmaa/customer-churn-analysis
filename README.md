# customer-churn-analysis
# Customer Churn Analysis

## Objective
This project analyzes customer behavior to identify factors contributing to customer churn and predicts customers who are likely to leave.  
The project follows an end-to-end data analytics workflow using SQL, Python, Power BI, and Excel.

## Dataset
- **IBM Telco Customer Churn Dataset**
- Source: Kaggle
- Includes customer demographics, services, billing details, and churn information.

> Raw data is stored locally and excluded from version control using `.gitignore`.

## Tools & Technologies

### Data Querying
- SQL (SQLite)

### Data Analysis & Modeling
- Python
- Pandas, NumPy
- Matplotlib
- Seaborn
- Scikit-learn

### Visualization & Reporting
- Power BI (interactive dashboards)
- Microsoft Excel (pivot tables & summaries)

### Version Control
- Git
- GitHub

## Project Workflow
1. Download dataset from Kaggle
2. Load raw data into SQL database
3. Perform data querying and aggregation using SQL
4. Clean and preprocess data using Python
5. Perform exploratory data analysis (EDA)
6. Build churn prediction models
7. Export processed data
8. Create dashboards in Power BI
9. Summarize insights using Excel

## Project Structure
customer-churn-analysis/
│
├── data/
│ ├── raw/ # Original dataset (ignored by git)
│ └── processed/ # Cleaned data
│
├── sql/
│ └── churn_analysis.sql
│
├── notebooks/
│ └── eda_python.ipynb
│
├── src/
│ └── preprocessing.py
│
├── powerbi/
│ └── churn_dashboard.pbix
│
├── excel/
│ └── churn_analysis.xlsx
│
├── README.md
└── .gitignore

## Key Outcomes
- Identified key churn drivers
- Built churn prediction model
- Developed interactive Power BI dashboard
- Delivered business-ready insights
