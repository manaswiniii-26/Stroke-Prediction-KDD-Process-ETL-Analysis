# Stroke-Prediction-KDD-Process-ETL-Analysis
📋 Overview

This project demonstrates a complete Knowledge Discovery in Databases (KDD) and ETL (Extract, Transform, Load) workflow using multiple datasets related to stroke prediction. It showcases how raw data is transformed into actionable insights through systematic cleaning, integration, transformation, and visualization.

🚀 Project Objectives

Integrate three different datasets containing demographic, medical, and lifestyle information.

Perform data wrangling and ETL operations to create a unified, analysis-ready dataset.

Apply KDD steps — including data selection, preprocessing, transformation, and interpretation.

Generate visual analytics to identify relationships between risk factors and stroke occurrences.

Derive conclusions and insights for potential predictive modeling.

🧩 Process Workflow

Data Extraction:

Collected three datasets from reliable sources related to patient demographics, medical history, and lifestyle factors.

Data Transformation:

Handled missing values, standardized data types, and encoded categorical features.

Normalized numeric features and merged datasets using appropriate keys.

Data Loading:

Created a final integrated dataset ready for downstream analytics or machine learning.

KDD Steps:

Data cleaning → Integration → Transformation → Visualization → Knowledge Extraction → Evaluation.

🏗️ Data Mart Design (Star Schema)

The project’s final structure is modeled as a Star Schema, supporting efficient analytical querying and data exploration.
This schema separates measurable events (facts) from descriptive attributes (dimensions), aligning with industry-standard data warehousing practices.

🧩 Schema Overview

Fact Table: Fact_Stroke_Prediction

Contains stroke-related facts and foreign keys linking to dimension tables.

Dimension Tables:

Dim_Demographic — captures patient demographics.

Dim_Medical_Lab — includes medical indicators like glucose and cholesterol.

Dim_Cardiac — stores cardiovascular attributes such as blood pressure and heart rate.

Dim_Lifestyle — details lifestyle factors including work type and smoking status.

📊 Visual Analysis

Comparative visualizations across age groups, BMI, glucose levels, and heart conditions.

Correlation heatmaps and distribution plots to uncover patterns influencing stroke likelihood.

🧾 Conclusion

The study emphasizes how systematic ETL and KDD approaches enable meaningful insights from raw healthcare data. The findings can aid further predictive modeling and data-driven medical decision-making.

🛠️ Technologies Used

Python

Pandas, NumPy, Matplotlib, Seaborn

Jupyter Notebook
