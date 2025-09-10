# Delivery-Delay-Dashboard-logistics-analysis-
##
📌 Project Overview

This project analyzes delivery performance in logistics using a cleaned dataset and builds an interactive Tableau dashboard.
The dashboard highlights on-time vs delayed deliveries, identifies patterns by city, courier, and product, and provides actionable insights to improve logistics efficiency.
##
🎯 Objectives

Measure on-time vs late deliveries.

Track average delivery delay.

Analyze delays by City, Product, and Courier.

Identify monthly delay trends.

Provide insights through a visual and interactive dashboard.

## 
📊 Dataset Description

The dataset contains order-level details with 10 key columns:

Column Name	Description

Order_ID	(Unique order number)

Product	(Product delivered)

City	(Delivery location)

Courier	[Courier company (e.g., DTDC, Delhivery, Shadowfax)]

Promised_Date	(Date promised to customer)

Delivery_Date	(Actual delivery date)

Delay_Days	Difference between Delivery_Date and Promised_Date)

On_Time_Flag	(On Time / Late indicator)

Delay_Bucket	[Delay category (e.g., 1–2 Days Late)]

Delay_Capped	(Capped value for extreme delays)

## 
🛠️ Data Preparation

Removed missing/duplicate values.

Standardized date formats.

Created calculated fields in Tableau:

Delay_Days = Delivery – Promised Date

On_Time_Flag = IF Delay_Days ≤ 0 THEN “On Time” ELSE “Late” END

% Late Deliveries = Late Orders ÷ Total Orders

Average Delay = AVG(Delay_Days)

## 
📈 Visualizations in Dashboard

1. Delay bucket overview ( bar chart)

2. Delay distribution by courier ( bar chart)

3. Delay disturbution by city

4. heatmap of delivery delay by city and courier

5. Product category delay

6. Delivery Delay Trend over Time

7. Citywise Deliverys statitstics for courier


👉 Tableau Public Link: Click Here
- <a herf="https://public.tableau.com/app/profile/aditi.singh4102/viz/DeliveryDelayDashboard1/Story1?publish=yes">

## 
🔑 Key Insights

 28% of deliveries are late.

[Mumbai and Chennai] has the maximum late deliveries.

[DTDC Courier] shows the highest average delay.

Electronics products (Mobiles, Cameras) face maximum delays.

## 
🚀 Tools & Technologies

Tableau – Data visualization & dashboard building

python -data cleaning

excel/csv - data storage


## Conclusion

The Delivery Delay Dashboard helps logistics managers:

Monitor courier and city performance.

Identify key reasons for delivery delays.

Make better decisions on courier selection & regional logistics planning.









