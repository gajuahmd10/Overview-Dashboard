This repository provides an overview dashboard for tracking and visualizing the performance of both customers and vendors. It includes KPIs to monitor and compare their progress. Various types of graphs are incorporated for insightful visualizations of their performance metrics, making it easier to identify trends, gaps, and areas for improvement

# Development Process : 
I begin by designing the Power BI data model using ideas from various sources, then connect it to the MySQL database and import only the required tables. Relationships are built between fact and dimension tables to form a star schema. Using **Power Query (M code)**, I perform data cleaning and transformations to optimize performance. I focus on minimizing load time by filtering data early and reducing unnecessary columns. While writing **DAX**, I use **VAR**, parameters, and efficient filters to speed up execution. I also monitor how visuals and filters impact performance, ensuring smooth and responsive dashboards. Overall, the goal is to create a fast, efficient, and well-structured Power BI model

## Customer Dashboard Overview:
This dashboard provides a clear view of **customer performance over time** to support data-driven decision-making. It displays the **total orders from the beginning**, along with total sales, used to calculate the bounce rate. It also tracks **offer usage frequency**, **month-wise sales by category**, and the **product return ratio**. Additionally, it highlights **customer ordering patterns by time** of day and shows the last order date with the corresponding amount, offering a complete overview of customer behavior and engagement

<img width="1382" height="675" alt="Screenshot 2025-10-12 142548" src="https://github.com/user-attachments/assets/ddce0a2d-f7db-4d75-b062-8df5857e288c" />

## Vendor Dashboard Overview:

The Distributor Overview Dashboard provides a comprehensive analysis of distributor performance across different regions and product categories. It tracks key metrics such as total sales, invoices, quantity, and offers to evaluate business growth and efficiency. Monthly and yearly trend visuals help identify performance patterns and **seasonal variations**. The **Category Sales** section highlights top-performing product segments, while the **Stock Summary** delivers detailed insights into product-wise sales, prices, and remaining stock. Overall, this dashboard supports data-driven decision-making by offering a clear view of distributor performance and inventory management.

<img width="1317" height="644" alt="Screenshot 2025-10-12 142445" src="https://github.com/user-attachments/assets/053d5a4e-7ce3-4778-9aa4-a6041b4d0c06" />

