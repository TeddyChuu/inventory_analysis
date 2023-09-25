# inventory_analysis
# **Executive Summary**

## Insights

### Sales by Years

- The product that accounted for the highest percentage is "Glow a Flytrap," which was the best-selling item in 2021 and comprised 10.85% of the total inventory. It seems that customers do not prefer flies

### Inventory Turnover

- A rate of 1.97 indicates that "Doughnut lip gloss" is selling almost twice as fast in stock, or in other words, it has been ordered at almost twice the average rate

### Constrasting Revenue

- "Set of 6 soldier skittles" has experienced an increase in sales. When comparing 2020 and 2021, the sales figures have shown significant growth.

### Smart Purchasing

- A low COGS to revenue ratio indicates that an item generates more profit since it has a low cost in comparison to its selling price. This insight can help the company to increase the inventory stock on “WOODLAND CHARLOTTE BAG” to increase its profit

### Inspecting Categories

- Jewelry has no representation in medium value items, and if you try to filter by high value items, the same pattern repeats. This might tell that perhaps this category should be reconsidered.

### Control Declsions

- The "VICTORIAN METAL POSTCARD SPRING" has a high inventory turnover because it generates small revenues. Upon checking the number of units ordered, it can be observed that the quantity is relatively low. This product would achieve greater success if there were more items in inventory

## **Recommendations**

- Increasing the inventory level of product type B might be a good idea, especially since product type A has an inventory level three times higher and a slightly closer to average inventory turnover rate.

# **The Process**

## **Data Cleaning and Transformation**

After carefully investigating the data available; fulfilment, orders and shipment and inventory, some data issues were discovered and this is how they were addressed

- **Table Price** has character error values using Replace values of those error values
- **Table Stock** has a null value in SKU-ID using Replace values to remove unnecessary spaces
- Merge 2 Price and Stock tables
- Continue cleaning character errors in the Category column in the categories table and the Country column in the Orders table

## **Measures Created**

### Sales by Years

- Quantity_2021
- Quantity_2022
- Revenue_2020
- Total_orders

### Inventory Turnover

- Turnover
- Avg_inventory
- Inventory_turnover

### Constrasting Revenue

- Revenue_2021
- percent_revenue_2021
- Revenue_2020
- percent_revenue_2020

### ABC Analysis

- ABC analysis is a tool for categorizing items in a product inventory. It can help improve inventory management and production planning
- ABC analysis categorizes products into three types: High, Medium, and Low based on the revenue they generate
- CP_revenue
- ABC_class
- COGS_Revenue_ratio
