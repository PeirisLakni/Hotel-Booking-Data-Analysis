## Hotel Booking Analytics: ETL, Segmentation & Forecasting

### Project Overview

This project focuses on analyzing hotel booking data to extract meaningful insights, identify customer segments, and forecast future demand. The study follows a complete data analytics pipeline including ETL (Extract, Transform, Load), Exploratory Data Analysis (EDA), Clustering, and Forecasting, supported by proper version control using Git.

The objective is to support data-driven decision-making in hotel operations such as demand planning, pricing strategies, and customer management.

### Dataset
	•	Source: Kaggle
	•	Dataset: Hotel Booking Demand Dataset
	•	Link: https://www.kaggle.com/datasets/saadharoon27/hotel-booking-dataset

The dataset contains booking information for resort and city hotels, including:
	•	Booking details (lead time, arrival date, stay duration)
	•	Customer information (adults, children, country)
	•	Booking outcomes (cancellations, ADR, reservation status)

### Tools & Technologies used:
	•	Python (Pandas, NumPy)
	•	Data Visualization (Matplotlib, Seaborn)
	•	Machine Learning (Scikit-learn)
	•	Time Series Modeling (Statsmodels)
	•	Git & GitHub

### Workings:
## ETL
	•	Cleaned missing values and removed inconsistencies
	•	Handled outliers using IQR
	•	Created new features (total guests, total nights, total cost)
	•	Saved processed dataset

## Exploratory Data Analysis
	•	Analyzed booking trends, cancellations, and customer patterns
	•	Created visualizations (heatmaps, line charts, boxplots)
	•	Identified key insights on demand and revenue

## Clustering
	•	Applied K-Means and Hierarchical clustering
	•	Identified customer segments (e.g., high-value, frequent cancellers)
	•	Provided business insights for targeting and optimization

## Forecasting
	•	Built ARIMA model to predict booking trends
	•	Evaluated using MAE and RMSE
	•	Supported demand planning and pricing decisions

## GitHub Repository Structure

```text
hotel-booking-analytics/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   ├── 01_etl.ipynb
│   ├── 02_eda.ipynb
│   ├── 03_clustering.ipynb
│   └── 04_forecasting.ipynb
│
├── src/
│   ├── etl.py
│   ├── eda.py
│   ├── clustering.py
│   └── forecasting.py
│
├── outputs/
│   ├── figures/
│   ├── models/
│   └── reports/
│
├── README.md
├── requirements.txt
