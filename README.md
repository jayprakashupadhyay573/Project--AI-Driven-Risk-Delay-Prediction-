# AI-Driven Risk & Delay Prediction for Logistics Operations

## Overview

This project is a **machine learning–based logistics risk prediction system** that predicts the probability of delivery delays in supply chain operations.
The system analyzes operational factors such as **traffic congestion, weather conditions, and route risk levels** to estimate whether a shipment is likely to be delayed.

The model is trained using historical logistics data and deployed using a **Flask web application** that allows users to input operational parameters and receive real-time delay risk predictions.

---

## Problem Statement

Logistics companies often face delivery delays due to unpredictable operational factors such as traffic congestion, weather conditions, and route disruptions.
These delays increase operational costs and reduce customer satisfaction.

This project demonstrates how **machine learning can help predict potential delivery risks before they occur**, enabling proactive decision-making.

---

## Key Features

* Logistics dataset preprocessing and cleaning
* Feature engineering for operational risk analysis
* Exploratory Data Analysis (EDA)
* Machine learning model training using **Random Forest**
* Model serialization using **Joblib**
* Flask web application for prediction interface
* Real-time risk prediction based on user inputs

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Flask
* Matplotlib / Seaborn
* Joblib

---

## Project Structure

```
Project
│
├── app.py                     # Flask web application
├── main.ipynb                 # Data analysis and model training
├── rf.pkl                     # Trained Random Forest model
├── le.pkl                     # Label encoder
├── dynamic_supply_chain_logistics_dataset.csv
│
└── templates
    └── index.html             # Prediction interface
```

---

## Machine Learning Workflow

Data Collection
→ Data Cleaning
→ Feature Engineering
→ Exploratory Data Analysis
→ Model Training (Random Forest)
→ Model Saving
→ Flask Web Application
→ Delay Risk Prediction

---

## Example Use Case

A logistics company transporting goods from **Mumbai to Delhi** may face unexpected delays due to traffic congestion and weather disruptions.

By entering operational parameters into this system, the model can **predict the probability of delivery delays**, allowing the logistics team to adjust routes or schedules proactively.

## Future Improvements

* Real-time logistics data integration
* Deployment on cloud infrastructure
* Interactive dashboard for logistics analytics
* Deep learning–based prediction models

## Project Demonstration
Screenshots of the web interface and prediction results are included below.
1.<img width="1097" height="706" alt="Random forest 1" src="https://github.com/user-attachments/assets/a0b0f746-1279-4278-b6bc-5afb511f468a" />
2. <img width="1552" height="911" alt="randam forest 2" src="https://github.com/user-attachments/assets/86f7368e-975c-4326-96be-35f590ec7cff" />





## Author
Jay Prakash Upadhyay
B.Tech CSBS – oist
