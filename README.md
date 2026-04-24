✈️ Big Data Analytics for Airline Delay Prediction

📌 Overview

This project applies big data analytics techniques to analyze and predict airline delays using Apache Spark and MongoDB. It follows a complete data pipeline, including data ingestion, preprocessing, distributed processing, visualization, and machine learning to extract meaningful insights from large-scale flight data.

🎯 Objectives

Analyze large-scale airline data to identify delay patterns
Build a scalable big data processing pipeline
Predict flight delays using machine learning models
Provide actionable insights for improving airline performance

🧠 Key Features

End-to-end big data pipeline implementation
Distributed data processing with Apache Spark
NoSQL data storage using MongoDB
Feature engineering for delay prediction
Machine learning models for classification
Interactive and static data visualizations

📂 Dataset

Source: Kaggle (US Bureau of Transportation Statistics)
Size: ~5GB (processed sample: ~1.8GB)
Records: ~17.9 million flights
Attributes: 29 features including delays, carriers, routes, and timings

⚙️ Tech Stack
🔹 Programming
Python
🔹 Big Data Tools
Apache Spark (Databricks)
MongoDB Atlas
🔹 Libraries
PySpark
Pandas, NumPy
Matplotlib
🔹 Machine Learning
Logistic Regression
Decision Tree

🔄 Project Pipeline

Data Ingestion
Load large-scale airline dataset into Databricks
Data Storage
Store structured flight data in MongoDB (NoSQL)
Data Cleaning
Handle missing values and duplicates
Convert time formats
Feature Engineering
Create delay categories
Generate binary target variable (late vs on-time)
Exploratory Data Analysis
Airline performance comparison
Seasonal delay trends
Delay cause analysis
Machine Learning
Train classification models
Evaluate using accuracy, precision, recall, and AUC
Visualization
Charts for trends, delays, and distributions

📊 Key Insights

Departure delay strongly predicts arrival delay (correlation: 0.86)
December and June show highest delay rates
Major airports (ORD, ATL, DFW) experience high congestion
Late aircraft and carrier delays are the biggest contributors

🤖 Model Performance

Model	              Accuracy	 Precision	Recall	AUC
Logistic Regression	0.9338	   0.9324    	0.9338	0.9672
Decision Tree      	0.9328	   0.9313   	0.9328	0.4073

✅ Logistic Regression performed best overall

🏗️ Architecture

Data Source: Kaggle dataset
Storage: MongoDB (NoSQL)
Processing: Apache Spark (Databricks)
ML Models: Spark MLlib
Visualization: Matplotlib & Databricks
🚀 Future Improvements
Integrate real-time data using APIs (weather, air traffic)
Use advanced models (Random Forest, Gradient Boosting)
Deploy model as REST API
Enable real-time streaming with Spark + MongoDB
