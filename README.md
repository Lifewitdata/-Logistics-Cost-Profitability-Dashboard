# 📦 Logistics Cost & Profitability Dashboard

## 📌 Project Overview
This project analyzes logistics delivery data to identify cost drivers, profitability trends, and operational efficiencies.  
The insights can help logistics companies optimize delivery costs, increase profit margins, and improve route efficiency.

## 🎯 Objectives
- Calculate delivery costs, rider payouts, and revenue by city and route.
- Identify high-cost routes and cities with low margins.
- Analyze delivery distance patterns and their effect on profitability.
- Create visualizations for decision-making dashboards.

## 🗂 Dataset
- **Rows:** 194,818  
- **Columns:** 8 (`order_id`, `delivery_date`, `route_id`, `city`, `delivery_cost`, `rider_payout`, `revenue`, `distance_km`)
- **Sample Data:**

| order_id | delivery_date | route_id | city      | delivery_cost | rider_payout | revenue | distance_km |
|----------|--------------|----------|-----------|--------------|--------------|---------|-------------|
| 1        | 2024-04-12   | 159      | Delhi     | 118.62       | 81.16        | 202.29  | 17.70       |
| 2        | 2024-12-14   | 158      | Kolkata   | 53.61        | 32.46        | 92.57   | 20.91       |
| 3        | 2024-09-27   | 169      | Hyderabad | 60.83        | 39.86        | 69.50   | 21.63       |
| 4        | 2024-04-16   | 133      | Kolkata   | 72.83        | 56.08        | 104.48  | 23.67       |
| 5        | 2024-03-12   | 133      | Hyderabad | 71.22        | 50.47        | 119.12  | 12.02       |

---

## 📊 Key Results

### 1️⃣ Average Cost & Margin by City
| city      | avg_cost | avg_margin |
|-----------|----------|------------|
| Bengaluru | 80.21    | 29.66      |
| Kolkata   | 79.90    | 29.65      |
| Chennai   | 80.39    | 29.64      |
| Mumbai    | 79.87    | 29.63      |
| Delhi     | 79.83    | 29.60      |
| Hyderabad | 79.88    | 29.56      |

### 2️⃣ High-Cost Routes (Top 10 by Avg Cost per Delivery)
*Identified using a Tableau Top N parameter filter.*

---

## 🛠 Tools & Technologies
- **Python:** pandas, numpy, matplotlib, seaborn
- **Jupyter Notebook:** Data cleaning, processing, and analysis

---



---


