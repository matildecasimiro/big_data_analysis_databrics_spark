# Big Data Analysis with Apache Spark

This project showcases the use of **Apache Spark** and **Databricks** to perform large-scale data processing, exploratory analysis, machine learning, clustering, graph analytics, and real-time streaming across multiple datasets.

## Overview

The project explores three different real-world use cases using Spark's distributed computing capabilities:

*  **Student Performance Analysis** – student segmentation and network analysis
*  **Music Popularity Prediction** – machine learning models to predict song popularity
*  **Loan Approval Prediction** – loan approval classification and real-time streaming analytics

The objective was to demonstrate how Spark can be used to efficiently process large datasets and build scalable analytical solutions.

## Technologies

* Apache Spark
* PySpark
* Spark SQL
* Spark MLlib
* Spark Streaming
* GraphFrames
* Databricks

## Key Highlights

### Student Performance Analysis

* Exploratory Data Analysis (EDA)
* K-Means clustering for student segmentation
* GraphFrames network analysis
* Identification of student groups based on academic and social characteristics

### Music Popularity Prediction

* End-to-end machine learning pipelines
* Hyperparameter tuning with cross-validation
* Logistic Regression, Random Forest, and Gradient Boosted Trees
* Best model achieved an AUC of approximately 60%

### Loan Approval Prediction

* Classification models for loan approval prediction
* Logistic Regression, Random Forest, Gradient Boosted Trees, and SVM
* Best model achieved an AUC of approximately 95%
* Real-time analytics using Spark Streaming

## Repository Structure

```text
.
├── data/
│   ├── student_performance.csv
│   ├── spotify_data.csv
│   └── loan_approval.csv
│
├── notebooks/
│   ├── Student_Performance_Analysis.ipynb
│   ├── Music_Popularity_Prediction.ipynb
│   └── Loan_Approval_Prediction.ipynb
│
└── README.md
```


> Developed in Databricks using Apache Spark. The notebooks were exported to `.ipynb` format to enable direct viewing and navigation on GitHub.
