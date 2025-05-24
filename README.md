# Distributed AI System using Apache Spark and Databricks 
<div style="display: flex; justify-content: center; align-items: center; gap: 20px;">
  <img src="https://github.com/user-attachments/assets/8aa68212-ae25-453d-993a-97621883411c" alt="datab" height="200"/>
  <img src="https://github.com/user-attachments/assets/c509184d-aa12-401b-b047-21e0222e9b9b" alt="spark" height="200"/>
</div>



This project demonstrates the implementation of a distributed AI system using **Apache Spark** and **Databricks** for scalable data processing, analysis, and machine learning model training on a large dataset.

##  Abstract

With the rapid growth of big data, traditional data processing frameworks struggle to provide scalable solutions. This project addresses the challenge by leveraging **Apache Spark** for distributed computing and **Spark MLlib** for training machine learning models. The system is deployed and managed using **Databricks**, a cloud-based platform that enhances collaboration and performance.

---
##  Databricks Notebook

> [View the complete notebook here](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/1817369059134613/2745061134785558/6554414668808537/latest.html)

---
##  Technologies Used

- Apache Spark
- PySpark
- Spark SQL
- Spark MLlib
- Databricks
- DBFS (Databricks File System)
- Matplotlib, Seaborn (for visualizations)
- Python 3.x

---

##  Project Overview

###  Key Objectives:
- Build a distributed database system using Spark SQL
- Perform data preprocessing on a large dataset
- Execute analytical queries
- Train and evaluate machine learning models with Spark MLlib
- Leverage Databricks for ease of deployment and scalability

###  Workflow:

1. **Setup and Data Loading**
   - Configured Apache Spark on Databricks
   - Loaded an open-source Employee dataset

2. **Data Preprocessing**
   - Data cleaning, filtering, and partitioning
   - Transformed data for distributed storage

3. **Distributed Database Implementation**
   - Created database using Spark SQL
   - Stored data in Spark DataFrames

4. **Query and Data Analysis**
   - Executed Spark SQL queries
   - Performed exploratory data analysis (EDA) and visualizations

5. **AI Model Training**
   - Trained a Random Forest classifier using Spark MLlib
   - Evaluated model with `MulticlassClassificationEvaluator`

![image](https://github.com/user-attachments/assets/d8ebec52-5bbb-458c-94a9-af08a38c26e5)
---

##  Visualizations

-  Bar Chart  
-  Pie Chart  
-  Histogram  
-  Box Plot  
-  Scatter Plot  
-  Heatmap  
-  Pair Plot  
-  Violin Plot  
-  KDE Plot

![image](https://github.com/user-attachments/assets/c0969c7b-43b5-4570-a1e2-ae04e5e95876)

![image](https://github.com/user-attachments/assets/c52757db-9f1b-4118-ab77-7c7d0600c130)

![image](https://github.com/user-attachments/assets/4a85dacf-801d-4a34-97c3-0bd30958efa8)


---

##  Results

| Metric                   | Value             |
|--------------------------|------------------|
| Model Used              | Random Forest     |
| Evaluation Metric       | Accuracy          |
| Accuracy Score          | 70%               |
| Prediction Success      | Yes               |
| Processing Speed        | Improved via Spark |
| Query Performance       | Optimized with Spark SQL |

---

