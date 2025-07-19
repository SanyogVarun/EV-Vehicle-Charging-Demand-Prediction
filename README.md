# EV Adoption Forecasting 🚗⚡

As electric vehicle (EV) adoption surges, urban planners must anticipate infrastructure needs—particularly the deployment of EV charging stations. Poorly planned infrastructure can result in bottlenecks, reduced user satisfaction, and slower progress toward sustainability goals.

## 📌 Problem Statement

Using the electric vehicle dataset, which includes information on EV populations, vehicle types, and historical registration data, this project aims to develop a regression model to forecast future EV adoption. For instance, the model should predict the number of electric vehicles expected in upcoming years based on historical trends.

## 🎯 Goal

Build a regression-based forecasting model that accurately predicts future EV adoption trends using factors like:

- Historical EV growth patterns
- Vehicle types (BEVs, PHEVs, etc.)
- Regional and county-level data

The model should assist policymakers and planners in making data-driven infrastructure decisions.

## 📊 Dataset Overview

The dataset represents monthly vehicle registration counts maintained by the Washington State Department of Licensing (DOL), spanning from **January 2017 to February 2024**.

**Key Attributes:**
- `Date`: Month-end timestamp of registration (e.g., 2017-01-31 to 2024-02-29)
- `County`: Washington State county where the vehicle is registered
- `State`: Geographical location associated with the vehicle record
- `Vehicle Primary Use`: Describes usage type—Passenger (83%) or Truck (17%)
- `Battery Electric Vehicles (BEVs)`: Vehicles powered solely by onboard batteries
- `Plug-In Hybrid Electric Vehicles (PHEVs)`: Vehicles partially powered by onboard batteries
- `Electric Vehicle (EV) Total`: Total of BEVs + PHEVs
- `Non-Electric Vehicle Total`: All non-electric vehicle registrations
- `Total Vehicles`: Total number of all vehicle registrations in the county
- `Percent Electric Vehicles`: Percentage of EVs compared to non-EVs

📂 **Dataset Link:** [Kaggle - Electric Vehicle Population Size 2024](https://www.kaggle.com/datasets/sahirmaharajj/electric-vehicle-population-size-2024/data)

## 🧠 Technologies & Tools (planned)

- Python (pandas, scikit-learn, matplotlib/seaborn)
- Jupyter Notebook or Google Colab
- Regression Algorithms (Linear Regression, Random Forest, etc.)
- Time Series Analysis (optional, depending on modeling approach)
- Data Visualization Tools

## 🚀 Expected Outcome

A robust regression model capable of forecasting:
- The number of electric vehicles in the near future (e.g., 2025, 2026…)
- EV adoption rates by region (county-wise)
- Insights into trends by vehicle type (BEV vs PHEV)

This model will serve as a valuable tool for smart city planning and EV infrastructure optimization.

---

Feel free to contribute!
