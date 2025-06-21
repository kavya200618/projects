# projects
# HR Analytics – Predicting Employee Attrition

## Project Overview

This project aims to identify and analyze the key factors that lead to employee attrition using data analytics and visualization. Employee attrition is a significant challenge for many organizations, as it leads to increased hiring costs, reduced productivity, and knowledge loss. By leveraging real-world HR data, this project uncovers patterns and trends that can help HR departments make informed decisions to retain talent.

The primary goal is to gain insights from historical employee data and present those insights using a dynamic and interactive Power BI dashboard. The insights derived can support HR teams in creating effective employee retention strategies.

---

## Objectives

- Analyze employee attrition using historical HR data.
- Identify key factors influencing employee resignation.
- Visualize trends such as attrition by department, gender, income, and job roles.
- Create a Power BI dashboard for HR managers to explore patterns interactively.
- Suggest actionable strategies for reducing attrition.

---

## Tools and Technologies Used

- **Python (Google Colab):** Data cleaning, exploration, and analysis.
- **Pandas:** Data manipulation and preparation.
- **Matplotlib and Seaborn:** Data visualization in Python.
- **Power BI:** Interactive dashboard creation.
- **Jupyter Notebook:** Running and testing EDA steps.
- **GitHub:** Version control and project documentation.

---

## Dataset

- **Name:** IBM HR Analytics Employee Attrition & Performance
- **Source:** [Kaggle Dataset Link](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)
- **Format:** CSV
- **Features:** Age, Department, MonthlyIncome, DistanceFromHome, OverTime, JobSatisfaction, Attrition, etc.

---

## Steps Followed

### 1. Data Loading and Preprocessing
- The dataset was loaded into Google Colab.
- Checked for null values, data types, and inconsistencies.
- Cleaned and prepared the dataset for analysis.

### 2. Exploratory Data Analysis (EDA)
- Visualized attrition distribution by department, gender, job role, income, and overtime status.
- Identified key insights such as the impact of overtime and income on attrition.
- Created correlation heatmaps to understand relationships between numeric features.

### 3. Data Export
- The cleaned dataset was exported from Colab and downloaded as `hr_cleaned.csv`.

### 4. Power BI Dashboard
- Imported the cleaned dataset into Power BI Desktop.
- Created visuals including:
  - Attrition by department and job role
  - Attrition count and percentage
  - Monthly income distribution by attrition
  - Slicers for gender, department, and overtime
- Styled the dashboard with interactive filters and clean layout.

---

## Key Insights

- Employees working overtime are more likely to leave the company.
- Departments like Sales and Research & Development have higher attrition.
- Lower monthly income is linked to higher attrition rates.
- Job roles such as Sales Executive and Laboratory Technician showed higher resignation patterns.
- Younger employees and those with less job satisfaction tend to quit more often.

---

## Files in this Repository

| File Name                           | Description                                      |
|------------------------------------|--------------------------------------------------|
| `HR_Analytics_Project_Report_Kavya.docx` | Final 2-page internship report                     |
| `hr_cleaned.csv`                   | Cleaned HR dataset used for visualization         |
| `hr_dashboard.pbix`               | Power BI dashboard showing interactive visuals   |
| `EDA_HR_Analytics.ipynb` (optional) | Notebook containing Python EDA steps             |

---

## Future Improvements

- Implement a machine learning model to predict attrition risk.
- Include employee engagement and survey data for deeper insights.
- Deploy the dashboard to the cloud for live business use.

---

## Author

**Kavya Chalichemala**  
B.Tech Computer Science Engineering  
Vel Tech Rangarajan Dr. Sagunthala R&D Institute of Science and Technology  
Email: chalichemalakavya@gmail.com

---

## License

This project is for academic and educational purposes only. Dataset credit belongs to IBM and Kaggle contributors.
