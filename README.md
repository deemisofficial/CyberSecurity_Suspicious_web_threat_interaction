# CyberSecurity_Suspicious_web_threat_interaction_Anomaly_Detection_Project

## 📘 Overview

This project focuses on detecting suspicious or anomalous web threat interactions using unsupervised learning techniques.

## 📁 Dataset

- 282 interactions
- 16 features including country codes, byte traffic, and time metadata
- No missing values, ensuring a clean processing pipeline

## 🧼 Preprocessing Steps

- Removed duplicate rows
- Converted time columns to datetime format
- One-hot encoding for categorical columns
- Standard scaling of numerical features

## 📊 EDA Highlights

- Country-wise distribution of IP addresses
- Correlation matrix of numerical features
- Boxplots for traffic analysis

## 🤖 Model Used

**IsolationForest** (unsupervised anomaly detection)

- Used to detect outliers potentially linked to cyber threats
- Flagged suspicious interaction records for investigation

## 🔧 Tools & Libraries

- `Python`, `Pandas`, `Seaborn`, `Matplotlib`
- `Scikit-learn`, `Jupyter Notebook`

## 📈 Results

- Flagged anomalous patterns without labeled data
- Scalable baseline for network traffic threat analysis

![network interaction]_(Network_interaction_between_source_and_destination_IPs.jpg)
![web traffic]_(Web_traffic_analysis_over_time.jpg)

## 📎 How to Run

```bash
pip install -r requirements.txt
jupyter notebook suspicious-web-threat-interactions.ipynb

