# 📦 FedEx Logistics Analysis using Python

## 📊 Project Overview

This project analyzes logistics and shipment data to evaluate delivery performance, cost efficiency, and operational trends. The goal is to identify inefficiencies, compare shipment strategies, and provide actionable insights for optimizing logistics operations.

---

## 🎯 Objectives

* Analyze **delivery delay** and **lead time**
* Compare **shipment modes** based on cost, speed, and reliability
* Identify **top-performing vendors**
* Evaluate **country-wise delivery performance**
* Understand the relationship between **cost and delivery speed**

---

## 🛠 Tools & Technologies

* **Python** (Pandas, NumPy)
* **Matplotlib & Seaborn** (Data Visualization)
* **Jupyter Notebook**

---

## 📁 Dataset Description

The dataset contains logistics shipment records including:

* Shipment mode (Air, Ocean, Truck, Air Charter)
* Delivery and scheduled dates
* Freight cost and shipment weight
* Vendor and country information

---

## 📈 Key KPIs

* **On-Time Delivery Rate (%)**
* **Average Lead Time (Days)**
* **Delivery Delay (Days)**
  *(Negative = Early Delivery | Positive = Late Delivery)*
* **Cost per KG**

---

## 📊 Analysis & Visualizations

### 🔹 Cost Analysis

* Compared shipment modes based on **cost per KG**
* Identified **Air Charter as the most expensive option**

### 🔹 Lead Time Analysis

* Evaluated delivery speed across shipment modes
* Found **Truck as the fastest and most efficient mode**

### 🔹 Delivery Delay Analysis

* Measured delay using delivery vs scheduled date
* Highlighted differences between **early and late deliveries**

### 🔹 Trend Analysis

* Analyzed **monthly delivery performance**
* Identified fluctuations in operational efficiency over time

### 🔹 Vendor Performance

* Identified:

  * **Top 10 cost-efficient vendors**

### 🔹 Country-wise Heatmap 🔥

* Visualized delivery delay across countries and shipment modes
* Highlighted **regional differences in performance**

---

## 💡 Key Insights

1. **Ocean shipments** are the most cost-efficient (~$20/kg) but have the **highest delays** and very high lead time (~176 days), making them suitable only for non-urgent shipments.

2. **Air Charter** is the fastest option but extremely expensive (~$180/kg), delivering significantly earlier than scheduled. Best suited for urgent and high-priority shipments.

3. **Air shipments** provide the best balance between cost (~$35/kg) and reliability, delivering mostly on time or slightly early.

4. **Truck shipments** are the most cost-effective (~$14/kg) with the lowest lead time (~55 days), making them ideal for regional and cost-sensitive logistics.

5. **Vendor analysis** shows strong variation in cost and performance, indicating that selecting the right vendor can significantly optimize logistics efficiency.

6. Most deliveries occur **earlier than scheduled**, indicating generally efficient logistics operations, but some regions and shipment modes still show consistent delays.

---

## 🚀 Conclusion

This project demonstrates how data analysis can improve logistics decision-making by balancing **cost, speed, and reliability**. The findings help in selecting optimal shipment modes and vendors based on business requirements.

---

## 👨‍💻 Author

**Dipesh Nagar**
Aspiring Data Analyst | Python | SQL | Power BI
