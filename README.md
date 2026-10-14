# PowerBI-task5-
# Healthcare Data Analysis Dashboard

## 📌 Project Overview

The **Healthcare Data Analysis Dashboard** is a Power BI project designed to analyze healthcare admission data and generate meaningful insights through interactive visualizations and reports. It helps explore patient demographics, hospital admissions, medical conditions, billing amounts, and insurance providers.

## 🎯 Objectives

- Analyze healthcare admission records.
- Study patient demographics, including age and gender.
- Analyze admissions by hospital, doctor, medical condition, and admission type.
- Explore billing amounts and insurance providers.
- Identify monthly admission trends and patterns.
- Present healthcare insights using interactive dashboards.

## 🛠️ Tools and Technologies

- Microsoft Power BI Desktop
- Power Query
- Data Modeling
- DAX (Data Analysis Expressions)
- Data Visualization

## 🗂️ Data Model

The project uses the following tables:

| Table Name | Description |
|---|---|
| **DimPatient** | Patient details, including name, age, gender, and blood type. |
| **DimDoctor** | Doctor information. |
| **DimHospital** | Hospital information. |
| **DimDate** | Date details, including year, month, and quarter. |
| **FactAdmission** | Healthcare admission records and related details. |
| **healthcare_dataset2** | Source dataset used for data transformation. |

## 📊 Key Analysis

The dashboard provides insights into the following areas:

- **Total Admissions:** Overall number of healthcare admission records.
- **Monthly Admission Trends:** Changes in admissions over time.
- **Patient Demographics:** Distribution of patients by age and gender.
- **Medical Conditions:** Analysis of admissions by medical condition.
- **Hospital Analysis:** Comparison of admissions across hospitals.
- **Doctor Analysis:** Examination of doctor-related admission records.
- **Billing Analysis:** Analysis of healthcare billing amounts.
- **Insurance Analysis:** Distribution of admissions by insurance provider.
- **Admission Type:** Analysis of different admission categories.
- **Test Results:** Exploration of patient test result categories.

## ⚙️ Data Processing

The project involves the following steps:

1. Import the healthcare dataset into Power BI.
2. Clean and transform data using Power Query.
3. Create dimension and fact tables.
4. Establish relationships between the tables.
5. Create measures using DAX where required.
6. Develop interactive visualizations and dashboards.
7. Analyze healthcare data to identify useful patterns and trends.

## 📁 Project Structure

```text
Healthcare-Data-Analysis/
│
├── PowerBI-5.pbix
├── healthcare_dataset2.csv
└── README.md
```

*Note: The CSV file is included in the structure only if it is available in the repository.*

## 🚀 How to Open the Project

1. Download or clone this repository.
2. Install [Microsoft Power BI Desktop](https://powerbi.microsoft.com/desktop/).
3. Open the `PowerBI-5.pbix` file.
4. If required, update the source file path in Power Query.
5. Refresh the dataset if the source data is available.
6. Explore the dashboard and interact with the visualizations.

## 💡 Project Outcomes

- Improved understanding of healthcare admission patterns.
- Clear insights into patient demographics and medical conditions.
- Better visibility into hospital, doctor, and insurance-related data.
- Effective analysis of healthcare billing amounts.
- Interactive reporting through Power BI dashboards.

## 🏁 Conclusion

This project demonstrates the use of Microsoft Power BI for healthcare data analysis. By combining data cleaning, data modeling, DAX, and interactive visualizations, the dashboard transforms healthcare admission records into meaningful insights that support data-driven analysis.


