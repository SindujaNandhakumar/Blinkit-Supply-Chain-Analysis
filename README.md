# Blinkit-Supply-Chain-Analysis

📌 Overview

In the fast-paced world of quick commerce, supply chain efficiency plays a critical role in ensuring customer satisfaction, delivery speed, and inventory optimization. This project focuses on Blinkit, a leading instant delivery platform in India, and evaluates its supply chain performance using real transactional datasets covering:

    Orders

    Inventory

    Products

    Order items

    Customers

    Deliveries

The goal is to extract actionable insights and identify key patterns across product movement, inventory behavior, and delivery performance that can help improve supply chain responsiveness.

🎯 Objectives

This analysis aims to address critical business questions:

    Which product categories are driving the most sales?

    How efficiently is inventory managed relative to demand?

    Where and why are delivery delays occurring?

    What areas of supply chain operations require improvement?

🛒 Key Analytical Areas
1. Top-Selling Product Categories

    Categories such as Pet Care, Household Care, Pharmacy, Personal Care, and Baby Care consistently lead in sales.

    Conversely, Fruits & Vegetables and other food items lag in demand, indicating a preference for non-perishable essentials.

2. Inventory vs Demand Analysis

    Inventory levels were analyzed over time, assuming an initial stock of zero due to the lack of historical data.

    Stock on hand was computed cumulatively based on received and outgoing quantities.

    In March 2023, nearly all product categories breached their maximum stock levels—likely due to poor forecasting or over-ordering.

🔍 Key Insights:

    Average demand typically aligns with minimum stock levels, suggesting "just-in-time" replenishment practices.

    Inventory often exceeds maximum thresholds without matching demand, leading to overstock and potential waste.

    High stock without corresponding demand results in storage inefficiencies and financial loss.

⚠️ Areas of Concern
🔄 Static Stock Policies

    Min/Max thresholds were static and did not adapt to demand changes, seasons, or promotions.

    Demand forecasting and dynamic threshold setting could significantly improve inventory turnover.

🧃 Perishable Product Risk

    Categories like Dairy, Fruits & Vegetables, and Snacks may have suffered from waste due to:

        Lack of expiry tracking

        Overstocking without proper rotation (FIFO/LIFO)

        Absence of depletion strategies like promotions or purchase limits

📈 Visualizations

This analysis is supported by Tableau dashboards to visualize:

    🔹 Top-selling products by category

    🔹 Monthly demand trends year over year

    🔹 Inventory movement vs min/max thresholds

    🔹 Damaged/Received stock ratios

    🔹 Deliveries Over Month
    

These visuals allow stakeholders to interactively explore problem areas and identify opportunities for improvement.

**Delivery Performance Dashboard**:

![image](https://github.com/user-attachments/assets/ee99ccce-26ae-4a14-8383-8d175fe37bfb)



**Product and Inventory Dashboard**:

![image](https://github.com/user-attachments/assets/5d692960-9666-42f6-90ec-2f045cc55b52)


