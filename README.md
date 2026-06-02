Meesho E-commerce Operations & Sales Analysis
📌 Project Overview
This project analyzes Meesho's operational data to identify bottlenecks in the supply chain and understand customer dissatisfaction trends. By examining 1,500+ orders, this dashboard provides insights into how geography and hub density affect delivery speed and product return rates.

📈 Key Research Areas
Delivery Performance: Analyzing the correlation between Local Hub Density and Delivery Time.

Return Analysis: Identifying the primary reasons for returns (e.g., "Late Delivery" vs. "Poor Quality") across different product categories like Apparel and Electronics.

Regional Sales: Mapping revenue and shipping costs across North, South, East, West, and Central India.

Customer Satisfaction: Evaluating the relationship between price points, delivery speed, and product ratings.

🛠️ Tech Stack
Power BI: Data modeling, DAX for delivery day calculations, and interactive visualizations.

Excel / CSV: Data source containing order IDs, regional data, and logistics metrics.

📁 Repository Contents
meeshoanalysisis.pbix: The Power BI project file with all visualizations.

MeeshoData.csv: The dataset used for the analysis (Order details, shipping costs, and return status).
<img width="2335" height="1465" alt="image" src="https://github.com/user-attachments/assets/720c8ee5-8eb3-491f-ac8d-5e07e00b06e7" />

# Meesho Project

Brief description of what this repository/project does.

## Database Setup

This project uses a MySQL database named `meesho`. Follow the steps below to set up the database locally.

### Prerequisites
* MySQL Server installed and running.
* Command Line / Terminal access.

### Installation Steps

1. **Log into your MySQL server:**
```bash
   mysql -u root -p
2.Create the database:
CREATE DATABASE meesho;
   EXIT;
Import the schema and data:
Navigate to the directory containing the .sql backup file and run the following command in your terminal:
mysql -u root -p meesho < meesho_meesho_orders.sql


