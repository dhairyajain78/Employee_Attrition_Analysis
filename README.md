# Employee Attrition Analysis

## Project Overview

This project performs Exploratory Data Analysis (EDA) on an Employee Attrition dataset to identify factors that influence employee turnover. The analysis focuses on understanding employee demographics, job-related factors, and patterns associated with attrition.

## Objectives

- Analyze employee demographics and workforce distribution
- Identify factors contributing to employee attrition
- Explore relationships between salary, age, experience, and attrition
- Examine job satisfaction and work-life balance metrics
- Generate actionable insights for employee retention

## Dataset Information

The dataset contains employee-related information such as:

- Employee Age
- Gender
- Department
- Job Role
- Education
- Monthly Income
- Years at Company
- Job Satisfaction
- Work-Life Balance
- Attrition Status

## Tools and Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Analysis Performed

### Data Cleaning
- Checked for missing values
- Verified data types
- Removed inconsistencies where necessary

### Exploratory Data Analysis
- Distribution analysis of numerical features
- Department-wise employee distribution
- Attrition analysis across different categories
- Salary and experience analysis
- Correlation analysis between variables

### Data Visualization
- Count plots
- Histograms
- Box plots
- Correlation heatmaps
- Comparative charts

## Key Insights

- Identified departments with higher attrition rates.
- Analyzed the impact of job satisfaction on employee retention.
- Explored relationships between salary levels and attrition.
- Examined employee demographics associated with turnover.

## Repository Structure

```text
kaggle-eda-project/
│
├── data/
│   └── raw/
│       └── employee.csv
│
├── notebooks/
│   └── employee_attrition_analysis.ipynb
│
├── README.md
├── requirements.txt
└── .gitignore
```

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/dhairyajain78/kaggle-eda-project.git
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Open Jupyter Notebook:

```bash
jupyter notebook
```

4. Run:

```text
notebooks/employee_attrition_analysis.ipynb
```

## Future Improvements

- Build predictive models for attrition prediction
- Create an interactive dashboard using Power BI or Tableau
- Perform advanced feature engineering
- Compare multiple machine learning algorithms

## Author

**Dhairya Jain**

GitHub: https://github.com/dhairyajain78