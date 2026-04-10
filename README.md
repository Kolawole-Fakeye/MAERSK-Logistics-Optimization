# 🚢 Maersk Logistics: Route Efficiency Optimization
**Project Lead:** Kolawole Fakeye  
**Domain:** Supply Chain / Data Engineering / Logistics  
![Maersk Analysis](Maersk_Delay_Impact_Analysis.png)
## 📌 Project Overview
This project analyzes maritime logistics data to identify fuel consumption patterns across West African trade routes. By calculating **Fuel Consumption per TEU**, the system evaluates operational performance at key regional ports.

## 🛠️ Technical Stack
- **Language:** R (Tidyverse)
- **Methodology:** Multivariate data aggregation and efficiency-ratio modeling.
- **KPIs:** Liters per TEU (Twenty-foot Equivalent Unit) and Port Delay Impact.

## 📊 Key Findings: Lagos vs. Abidjan
The current dataset provides a comparative look at regional efficiency:
* **Lagos:** Demonstrated the **highest operational efficiency** (lowest fuel burn per container) in this specific data cycle.
* **Abidjan:** Identified as the **high-consumption zone**, where higher fuel burn suggests opportunities for infrastructure or process optimization.

## 📂 Repository Contents
- `logistics_optimization.R`: The transformation logic and aggregation script.
- `maersk_logistics_efficiency.csv`: The processed data with efficiency metrics.
- `Maersk_Efficiency_Report.png`: Visualization of fuel consumption across ports.
