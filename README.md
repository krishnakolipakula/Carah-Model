# CARAH Model for Disease Prediction  
*Harnessing Weather Data and Machine Learning for Agriculture*  

This repository provides a high-level overview of a confidential project leveraging weather sensor data and machine learning to predict disease spread in crops. No code or sensitive data is included to maintain confidentiality.  

---

## 🌟 Overview  
The **CARAH Model for Disease Prediction** is an advanced machine learning-based system developed to analyze weather data and predict the spread of crop diseases. By leveraging multi-sensor inputs like temperature and humidity, the model identifies critical trends, calculates infection severity, and visualizes potential risks. This project empowers stakeholders with actionable insights to manage crop health effectively and mitigate potential losses.  

---

## ✨ Key Features  
- **Dynamic Data Processing**:  
   - Imported, cleaned, and transformed raw weather sensor data, optimizing it for model training and analysis.  
   - Added custom features such as hourly coefficients and timestamps for fine-grained insights.  
- **Humid Period Analysis**:  
   - Determined humid periods by calculating hourly humidity thresholds using custom algorithms.  
   - Introduced innovative techniques to reset and track humidity metrics dynamically over time.  
- **Machine Learning-Driven Predictions**:  
   - Developed algorithms to calculate incubation curves and infection severity levels, tailored to specific crop conditions.  
   - Assessed potential infection risks based on predefined thresholds, correlating weather conditions with disease spread.  
- **Interactive Visualization**:  
   - Utilized Plotly to create intuitive, color-coded incubation curves highlighting infection severity.  
   - Mapped timestamps, slopes, and severity levels for better interpretability and decision-making.  
- **Scalable Framework**:  
   - Processed datasets with 2,500+ rows, demonstrating scalability for large-scale agricultural data analysis.  

---

## 🛠️ Technologies Used  
- **Programming Language**: Python  
- **Data Processing**: Pandas, NumPy  
- **Visualization Tools**: Plotly  
- **Machine Learning Techniques**: Custom algorithms tailored for data thresholds, incubation periods, and infection predictions  

---

## 🔄 Project Workflow  
1. **Data Preparation**:  
   - Imported weather sensor data and applied data cleaning techniques.  
   - Dropped irrelevant columns and added time-based features for enhanced insights.  
2. **Feature Engineering**:  
   - Created metrics such as humid periods and average temperatures using thresholds and dynamic calculations.  
   - Implemented innovative methods for identifying daily and hourly humidity variations.  
3. **Infection Severity Analysis**:  
   - Mapped temperature averages and humid hours against a severity table to determine infection risks.  
   - Automated severity flagging and tracked patterns over time using timestamps.  
4. **Visualization and Reporting**:  
   - Plotted incubation curves to highlight severity trends using color-coded severity levels.  
   - Exported results into CSV files for further analysis and stakeholder reporting.  

---

## 🚀 Advanced Highlights  
- **Optimized Infection Prediction**: Reduced potential infection starting points to fewer than 100, significantly enhancing prediction accuracy.  
- **Real-Time Insights**: Enabled real-time tracking and analysis of severity flags, helping stakeholders respond proactively.  
- **Scalable Solution**: Designed a framework to handle large datasets while maintaining high accuracy and performance.  
- **Automated Reporting**: Generated CSV files with severity levels, timestamps, and insights for downstream applications.  

---

## 🔒 Confidentiality Notice  
This is a **confidential project**. No source code, raw data, or sensitive details have been shared in this repository. The content is strictly a high-level overview for educational and professional demonstration purposes.  

---

## ⚠️ Disclaimer  
All project details are strictly confidential. This repository includes generalized, non-sensitive information and methodologies for illustrative purposes only.  


## Disclaimer  
The data and details related to this project are strictly confidential. This repository contains only non-sensitive, high-level information for educational purposes.

