# 🗽 NYC TLC Taxi Trip Analysis – Location & Route-Based Insights

This project is a data analysis case study using the NYC TLC (Taxi and Limousine Commission) dataset, with a focus on **pickup/dropoff locations**, **routes**, and **revenue performance**. It was developed as part of a capstone project to practice data cleaning, visualization, and insight generation for stakeholders.

---

## 📦 Dataset

- **Source**: [NYC Taxi & Limousine Commission Trip Record Data](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page)
- **Period**: January 2023
- **Format**: CSV
- **Size**: ~60K+ rows
- **Key Columns**: `lpep_pickup_datetime`, `lpep_dropoff_datetime`, `PU_Zone`, `DO_Zone`, `fare_amount`, `trip_distance`, `total_amount`, etc.

---

## 🎯 Problem Statement

Stakeholders need insight into:

1. Which **zones and routes** generate the most trips and revenue?
2. How do travel patterns vary across **hour of day** and **day of week**?
3. How can the company optimize **fleet allocation and pricing**?

---

## 🔍 Project Objectives

- Clean and prepare the TLC trip data
- Analyze travel behavior based on **location and route**
- Visualize results using **Plotly (Python)** and **Tableau**
- Provide business recommendations based on findings

---

## 🛠️ Tools Used

- Python (Pandas, Plotly, NumPy)
- Tableau Public
- Jupyter Notebook
- Git & GitHub

---

## 📁 Project Structure

📦 nyc-tlc-trip-analysis
│
├── data/
│ └── nyc_taxi_jan2023.csv
│
├── notebooks/
│ └── NYC_TLC_Trip_Analysis.ipynb # Main analysis notebook
│
├── tableau/
│ └── nyc_tlc_dashboard.twbx # Tableau dashboard
│
├── images/
│ └── charts/ # Key visualizations (optional)
│
└── README.md

yaml
Copy
Edit

---

## 📊 Key Visualizations

- 🔝 Top 10 Pickup & Dropoff Zones
- 🔁 Most Frequent and Profitable Routes
- 📈 Daily Revenue Trends (line chart)
- 🕒 Pickup Patterns by Hour and Day
- 🚩 Anomalous Trips (long duration, short distance)
- 💼 Route-based Business Recommendations

---

## 💡 Business Recommendations

- 🚕 Prioritize fleet deployment in high-volume zones (JFK, Midtown, East Harlem)
- 🕐 Adjust operational hours based on hourly pickup peaks
- 💰 Apply dynamic pricing on routes with high avg. revenue/trip
- 🧭 Investigate long-duration, short-distance trips for efficiency
- 🧩 Use route heatmaps to plan dispatching & shift schedules

---


🙋 Author
Alfriando C. Vean
📫 [LinkedIn](https://www.linkedin.com/in/alfriandocvean/)
📧 alfriandocv@gmail.com

📃 License
MIT License – feel free to use and adapt with credit.
