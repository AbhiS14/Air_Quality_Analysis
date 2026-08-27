# 🌍 Delhi Air Quality Analysis using PySpark

## 📌 Project Overview

This project focuses on analyzing a large-scale **Delhi Air Quality Time Series Dataset** using **Python and Apache PySpark**.

The objective was to gain practical experience in processing and analyzing large datasets using PySpark DataFrames and to perform basic data transformation, aggregation, filtering, and ETL operations.

## 🔍 Project Highlights

In this project, I:

- Loaded and explored **1.2+ million air-quality records** using PySpark.
- Examined the dataset schema, columns, and data types.
- Identified unique environmental and pollution parameters.
- Filtered and sorted pollution readings based on specific conditions.
- Calculated **average and maximum pollution values**.
- Performed **location-wise pollution analysis**.
- Analyzed pollution values across different hours.
- Created a **Pollution Severity** category based on defined thresholds:
  - High → `Values > 300`
  - Medium → `100–300`
  - Low → `< 100`
- Identified highly polluted records and locations.
- Performed basic data cleaning, including duplicate removal.
- Generated statistical summaries.
- Exported highly polluted records into a CSV file.
- Created a **location-wise environmental monitoring report** containing:
  - Average Pollution
  - Maximum Pollution
  - Total Records

## 🛠️ Technologies & Tools

- Python
- Apache PySpark
- Google Colab
- GitHub
- CSV

## 📊 Key PySpark Concepts Practiced

`Spark DataFrames` · `select()` · `filter()` · `distinct()` · `groupBy()` · `agg()` · `mean()` · `avg()` · `max()` · `count()` · `orderBy()` · `when()` · `otherwise()` · `dropDuplicates()` · `describe()` · `write.csv()`

## 📈 Insights

The analysis provided a basic comparison of pollution readings across different monitoring locations and environmental parameters. It also helped identify high-value pollution readings, understand hourly variations, and generate a location-wise summary for potential environmental monitoring and dashboard development.

> **Note:** The pollution thresholds used in this project are task-specific classification rules and should not be interpreted as official AQI or regulatory standards. Since the dataset contains multiple parameters with different units, aggregated pollution values should also be interpreted carefully.

## 📸 Project Screenshots

Screenshots of selected PySpark outputs from Google Colab are included in the `images/` folder to demonstrate the analysis and results.

## 📁 Repository Structure

```text
Delhi-Air-Quality-PySpark/
│
├── Air_Quality_Analysis.ipynb
├── README.md
└── images/
