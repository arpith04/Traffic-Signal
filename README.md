# 🚦 Traffic Signal Optimization Analytics Dashboard

## 📊 Overview
This project analyzes traffic flow, signal timing, and operational performance across multiple intersections to identify inefficiencies and optimize signal control.

The goal is to simulate a real-world urban traffic scenario and provide data-driven insights to reduce congestion, improve traffic flow, and enhance intersection efficiency.

---

## 🧠 Key Business Questions
- When does traffic congestion peak during the day?
- Are current signal timings (red/green) optimized for traffic demand?
- Which intersections experience the highest delays?
- Do longer red signals lead to increased waiting times?
- How do traffic incidents impact speed and congestion?

---

## 📈 Dashboard Preview
![Dashboard](https://github.com/arpith04/Traffic-Signal/blob/main/images/Traffic%20Signal%20Dashboard.jpg)

---

## 🔍 Key Insights
- Peak congestion occurs during evening hours (around **7 PM**)  
- **INT_101** consistently shows higher wait times, indicating suboptimal signal timing  
- Longer red signal durations are associated with increased delays  
- Traffic incidents significantly reduce average speed and increase wait time  

---

## 💡 Recommendations
- Adjust signal timings dynamically based on peak traffic periods  
- Optimize red/green cycles at high-delay intersections (e.g., INT_101)  
- Implement adaptive traffic control systems for better flow management  
- Monitor and respond quickly to incidents to minimize disruption  

---

## 🛠️ Tools & Technologies
- **SQL** – data querying and analysis  
- **Python (Pandas, NumPy)** – synthetic data generation  
- **Power BI** – dashboard design and visualization  

---

## 📁 Dataset
The dataset is **synthetically generated** to simulate real-world traffic conditions across multiple intersections.

It includes:
- Traffic flow data (vehicle count, speed)
- Signal timing (red and green durations)
- Waiting time at intersections
- Traffic incident indicators

---

## 🚀 Project Highlights
- Built an end-to-end analytics pipeline from data generation to visualization  
- Analyzed relationships between signal timing and congestion  
- Identified inefficiencies in traffic management using data-driven insights  
- Designed an interactive dashboard for operational decision-making  

---

## ▶️ How to Run
1. Run the Python script in `scripts/` to generate synthetic datasets  
2. Load CSV files from `data/` into Power BI  
3. Open the dashboard file in `dashboard/`  

---

## 📌 Future Improvements
- Integrate real-world traffic datasets  
- Apply predictive modeling for congestion forecasting  
- Implement real-time traffic monitoring and alerts  
