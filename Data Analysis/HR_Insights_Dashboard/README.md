# HR Insights Dashboard
 
## Table of Contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Cleansing/Preparation](#data-cleansingpreparation)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Results/Findings](#resultsfindings)
- [Recommendations](#recommendations)
- [Limitations](#limitations)
- [References](#references)
- [Contact Information](#contact-information)

  
### Project Overview
This comprehensive HR dashboard project aims to offer an in-depth view of the human resources landscape within a healthcare industry setting. By aggregating and analyzing pertinent HR employee data, our objective is to provide actionable insights into various aspects of workforce management and performance.

The dashboard will encompass a range of key HR metrics, including employee demographics, performance evaluations, training and development progress, and more. Through intuitive data visualizations and interactive features, users will be able to delve into the details of employee data, identify trends, and make informed decisions to optimize HR strategies.

One notable feature of this dashboard is its capability to drill down into individual employee profiles, providing a granular view of each employee's data. This functionality enables HR professionals and managers to gain deeper insights into individual performance, engagement levels, and areas for improvement, facilitating more personalized HR management and decision-making.

Ultimately, this comprehensive HR dashboard serves as a powerful tool for HR professionals and decision-makers within the healthcare industry, enabling them to effectively manage and optimize their workforce, drive employee engagement, and enhance organizational performance.

![Screenshot (1)](https://github.com/codeWithPatricia/HR_Insights_Dashboard/assets/33192304/e4da68df-01fe-461c-8526-4b6c753af17f)
![Screenshot (4)](https://github.com/codeWithPatricia/HR_Insights_Dashboard/assets/33192304/09d3c959-9c00-4772-99e4-86b8a78501bf)

### Data Sources
- HR Analytics Data: The primary dataset used for this analysis is the "HR Analytics Data (Uncleaned Version).csv" file, containing detailed information about each employees in the company.

- Employee Data: The primary dataset used for this analysis is the "HR employee data.csv" file, containing employee name and employee unique number.

### Tools
- Excel- Data Cleansing (I created a cleansed version) [Download Here](https://www.microsoft.com/en-us/microsoft-365/previous-versions/microsoft-excel-2013)
- PowerBI - Data Cleansing & Creating reports (I used powerBI for Data cleansing) [Download Here](https://powerbi.microsoft.com/en-us/downloads/)
- Powerpoint-Background design [Download Here](https://www.microsoft.com/en/microsoft-365/powerpoint?market=af)

### Data Cleansing/Preparation
In this Inital data preparation phase, we performed the following tasks:
- Data loading and inspection.
- Data cleansing and formatting.

### Exploratory Data Analysis
EDA involved exploring the Employee Detail data to answer key questions, such as:
- Number of employee based on gender, Active Worker?
- Employee due for promotion and Retrenchment?
- Gender by department?
- Job Role by Satifaction?
- Employees distance from office?
- Number of Overtime Worker? 
- Employees Total working Years?

### Data Analysis
Include some intersting code/features worked with
```

ImageURL = 
    IF('All Measures'[SelectedGender]= "Female", "https://cdn-icons-png.flaticon.com/512/3220/3220315.png ",
    IF('All Measures'[SelectedGender] = "Male","https://cdn-icons-png.flaticon.com/512/7178/7178489.png ", 
    "https://cdn-icons-png.flaticon.com/512/9841/9841566.png "))

```
### Results/Findings
The analysis results are summarized as follows:
- The Company's Sales have been steadily increasing over the past year, with a noticeable peak during the hoilday season.
- Product Category A is the best-performing category in terms of sales and revenue.
- Customer segments with high lifetime value (LIV) should be targeted for marketing efforts.

### Recommendations
Based on the analysis, we recommend the following actions:
- Implement strategies to address the gender disparity in promotions, ensuring equitable opportunities across all departments.
- Explore options to improve employee satisfaction levels, potentially through surveys or feedback mechanisms.
- Consider initiatives to support employees who commute from distant locations, such as flexible work arrangements or transportation assistance.
- Evaluate the factors contributing to overtime work and explore solutions to promote a healthy work-life balance.
- Develop retention strategies to retain experienced employees who have contributed significantly to the company's success over the years.

### Limitations
- Text was added to the specified columns (Job Involvement, Job Level, Total working Years) to provide additional context or categorization.
- New columns (Retirement, Promotion Status) were introduced to capture additional information related to retirement status and promotion eligibility.
- Changes in columns (Job satisfaction, Performance Rating, Distance from office) data types were implemented to ensure consistency and improve interpretability of the data.
- These modifications were made to enhance the usability and comprehensiveness of the dataset for analysis and decision-making purposes.

### References
1. [how to document your data analysis projects on github](https://herdataproject.com/how-to-document-your-data-analysis-projects-on-github/)


---
## Contact Information
<a href="mailto:iheonyekachukwu@gmail.com" target="blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/gmail/gmail-icon.svg" alt="blender" width="40" height="40"/> </a> 

---
# Don't forget to leave a star ⭐️

