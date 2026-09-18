# Doctor-Visit-Analytics-Data-Cleaning-Visualization-ML-Cost-Prediction
An end-to-end Python-based data science solution built in Google Colab to optimize clinical workflows, analyze patient queue metrics, and forecast medical visit costs using Machine Learning.

## 📌 Project Overview
Modern healthcare facilities struggle with unmonitored patient wait times, unpredictable visit costs, and inefficient staff allocation. The **Healthcare Analytics & Operational Optimization Pipeline** addresses these operational bottlenecks by converting raw patient data into actionable clinical intelligence.

This project implements a full data science lifecycle:
1. **Data Generation & Flaw Injection:** Simulates realistic patient records with intentional real-world data flaws (nulls, duplicates, outliers).
2. **Data Cleaning & Governance:** Programmatically sanitizes categorical values, imputes missing data, and filters invalid numeric ranges.
3. **Interactive EDA Dashboards:** Visualizes department loads, wait-time distributions by insurance, and age demographics using Plotly.
4. **Predictive Modeling:** Trains a **Random Forest Regressor** to predict `Visit_Cost` and evaluates relative feature importance.
5. **Data Interpretation & Action:** Automatically generates executive-level operational recommendations based on output metrics.
