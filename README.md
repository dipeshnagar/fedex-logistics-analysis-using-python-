# fedex-logistics-analysis-using-python-
📦 Logistics & Shipment Performance Analysis
📊 Project Overview

This project focuses on analyzing logistics and shipment data to evaluate delivery performance, cost efficiency, and operational trends. The analysis helps identify key factors affecting delivery delays and provides insights for optimizing shipment strategies.

🎯 Objectives

Analyze delivery delay and lead time
Compare shipment modes based on cost and performance
Identify top-performing vendors
Evaluate regional delivery patterns (country-wise)
Understand the relationship between cost and delivery speed
🛠 Tools & Technologies
Python (Pandas, NumPy)
Matplotlib & Seaborn (Data Visualization)

📁 Dataset Description

The dataset contains logistics shipment records including:

Shipment mode (Air, Ocean, Truck, Air Charter)
Delivery dates and scheduled dates
Freight cost and weight
Vendor and country information

📊 Visualizations & Analysis

🔹 Cost Analysis
Compared shipment modes based on cost per KG
Identified Air Charter as the most expensive option
🔹 Lead Time Analysis
Evaluated delivery speed across shipment modes
Found Truck as the fastest and most efficient mode
🔹 Delivery Delay Analysis
Calculated delay using:
Negative → Early delivery
Positive → Late delivery
🔹 Trend Analysis
Analyzed monthly delivery performance
Identified fluctuations in operational efficiency over time
🔹 Vendor Performance
Identified:
Top 10 fastest vendors
🔹 Country-wise Heatmap 🔥
Visualized delivery delay across countries and shipment modes

💡 Key Insights

1) Ocean is low-cost ($20.66/kg) but highly unreliable with consistent delays (8–10 days) and very high lead time (176 days),suitable only for non-urgent shipments, with rare exceptions like Zambia performing early.

2) Air Charter is the fastest but extremely expensive (~$180/kg), delivering significantly early (20–40 days), but with high variability, making it ideal only for urgent, high-priority deliveries.

3) Air offers the best balance of reliability and cost ($35.65/kg), delivering mostly on time or slightly early, making it suitable for time-sensitive shipments.

4)Truck is the most cost-efficient ($14.19/kg) with the lowest lead time (~55 days), making it the best option for regional and cost-sensitive logistics.
Vendor analysis shows strong cost variation, indicating that selecting the right vendors can significantly reduce overall logistics cost.
Overall, shipment mode selection should be strategy-driven, balancing cost, speed, and reliability based on business needs and geography.

🚀 Conclusion

This project demonstrates how data analysis can be used to optimize logistics operations by balancing cost and delivery efficiency. The insights can help businesses make better decisions regarding shipment methods and vendor selection.
