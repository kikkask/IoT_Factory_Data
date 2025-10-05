# 🏭 IoT Factory Data Dashboard

A powerful real-time dashboard for monitoring **industrial IoT machine data**, designed to analyze performance, energy consumption, maintenance patterns, and operator efficiency over time.  
Built to simulate a real smart factory environment, this project uses synthetic data generated from multiple IoT sensors.

---

## 🧠 Overview

This dashboard provides a **comprehensive view of factory operations**, allowing engineers and managers to monitor equipment health, detect anomalies, and optimize production efficiency.

It visualizes data such as:

- Machine operational status (ON / OFF / FAULT / MAINTENANCE)  
- Average temperature, pressure, and vibration  
- Energy consumption (kWh)  
- Production count  
- Faults by operator  
- Utilization rate and maintenance time

---

## 📊 Key Metrics Displayed

| Metric | Description |
|--------|--------------|
| **Pressure Bar** | Current average pressure of all machines. |
| **Average °C** | Average temperature of machines in operation. |
| **Faults** | Total number of machine faults detected. |
| **Production Count Today** | Total production units processed in the current day. |
| **Maintenance Alerts** | Number of alerts triggered due to maintenance flags. |
| **Average Vibration** | Real-time vibration signal from sensors (mm/s). |
| **Faults per Operator** | Ranking of operators based on number of faults handled. |
| **Utilization** | Percentage of time machines were active. |
| **Time in Maintenance** | Percentage of time machines were under maintenance. |
| **Energy Consumed (kWh)** | Total energy used by all machines in the period. |

---

## 🧩 Data Sources

The dataset used for this dashboard is **synthetically generated** to emulate real IoT factory conditions.

- Sensor readings every 10 minutes for 5 machines.
- Includes temperature, vibration, energy, current, voltage, and production data.

---

## ⚙️ Tech Stack

- **Power BI** – Dashboard visualization  
- **Python (pandas, numpy, faker)** – Data simulation and preprocessing  
- **CSV datasets** – Stored locally for reproducibility  
- **Markdown** – Documentation and GitHub presentation  

---

## 🚀 Features

✅ Real-time machine monitoring  
✅ Energy and performance analytics  
✅ Operator performance insights  
✅ Predictive maintenance potential  
✅ Modular dataset design (easy to expand)  

---

## 🧠 Future Enhancements

- Integration with **Azure IoT Hub** or **AWS IoT Core**  
- Real-time streaming using **Kafka or MQTT**  
- Predictive model for failure detection  
- Anomaly detection using **machine learning**  

---

## 👨‍💻 Author

Developed by **Lucas Brito**  
📧 Contact: sirbritolucas@gmail.com  
🔗 [LinkedIn]([https://linkedin.com](https://www.linkedin.com/in/lu-cas-brito)) · [GitHub](https://github.com)

---

## 🪄 License

This project is released under the **MIT License** — free for educational and non-commercial use.

---

