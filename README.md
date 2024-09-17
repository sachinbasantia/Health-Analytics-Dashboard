# Health Data Analysis on OCD Patients

This repository contains an analysis of OCD (Obsessive-Compulsive Disorder) patient data, which includes demographic and clinical information. The dataset used for this analysis is sourced from Kaggle, and the project utilizes SQL for data analysis and Power BI for visualization.

## Dataset

- **Source**: The dataset is publicly available on Kaggle. It can be accessed [here](https://www.kaggle.com/datasets/ohinhaque/ocd-patient-dataset-demographics-and-clinical-data/).
- **Description**: The dataset provides detailed information on OCD patients, including demographics (age, gender, education level) and clinical data (severity, onset of OCD, and treatment history).

## Tools Used

1. **SQL**: Used for data extraction, cleaning, and complex querying to derive insights from the dataset.
2. **Power BI**: Used for creating visualizations and dashboards to represent the data and findings.

## Project Overview

The project aims to:
- Analyze the demographic distribution of OCD patients.
- Investigate clinical patterns, including age of onset, severity, and treatment approaches.
- Identify any correlations between demographic factors and clinical outcomes.
- Visualize key trends and insights using Power BI dashboards.

## Key Features

- **Data Cleaning**: Managed missing or inconsistent data using SQL queries.
- **SQL Scripts**: The SQL queries used for analysis can be found in the `SQL_queries` folder. You can run these scripts on any SQL-compatible database environment.
- **Power BI Dashboards**: Created interactive visualizations to explore patterns in OCD patient demographics and clinical history.

## Power BI Dashboard

The Power BI file (`OCD_Patient_Analysis.pbix`) is included in the repository. You can open it in Power BI to explore the visualizations.

## SQL Queries Performed

1. Count & percentage of females vs males diagnosed with OCD & average obsession score by gender.
2. Count of patients by ethnicity and their respective average obsession score.
3. Number of people diagnosed with OCD month-over-month (MoM).
4. Most common obsession type (count) & its respective average obsession score.
5. Most common compulsion type (count) & its respective average obsession score.

## Results

- The analysis revealed key insights into OCD patient demographics and clinical treatment patterns, including:
  - The male-to-female ratio of patients is nearly equal.
  - African ethnicity has the lowest OCD scores and diagnosis rates.
  - The most common types of compulsions are **washing** and **counting**.

## Dataset License

Please refer to the dataset's [Kaggle page](https://www.kaggle.com/datasets/ohinhaque/ocd-patient-dataset-demographics-and-clinical-data) for license and usage rights.

