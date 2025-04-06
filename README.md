# 📊 Meir Hospital Data Analysis – Hackathon Project

## Overview
This project was developed during a hackathon focused on improving **human resource management** in hospitals through data-driven insights. We analyzed operational data from **Meir Hospital** and used **Prophet**, Meta’s open-source time-series forecasting tool, to identify patterns and forecast future workload distribution across rooms and shifts.

## 🚀 Goal
Enable smarter staffing decisions by:
- Identifying high-demand rooms and peak activity times
- Recognizing patterns in different assignment types (e.g., blood tests, cleaning)
- Forecasting future assignment volumes to support proactive human resource planning

## 🛠️ Tools & Technologies
- **Python**
- **Pandas, Matplotlib, Seaborn** – for data processing and visualization
- **Prophet by Meta** – for time-series forecasting
- **Jupyter Notebook** – for exploratory analysis and modeling

## 📈 Key Insights
- **Room 107** is consistently the busiest, suggesting a need for more dedicated staff.
- **Blood tests** and **cleaning tasks** are the most frequent assignments across all rooms.
- Activity is highest during the **morning shift (07:00–15:00)** and decreases throughout the day.
- Using Prophet, we forecasted the expected number of assignments per room over the **next 6 months**, allowing staff to anticipate busy periods.

## 🔮 Forecasting with Prophet
We used Prophet to:
- Break down historical data into **trend**, **seasonality**, and **holiday effects**
- Create forward-looking forecasts of room-specific task volumes
- Generate easy-to-understand visualizations of expected workload trends

These forecasts help hospital managers allocate resources more efficiently, avoiding overwork and improving service quality.
