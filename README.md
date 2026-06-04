# 🍕 Pizza Sales Analysis Dashboard

📌 **Project Objective**   
To design and develop a **Pizza Sales Dashboard in Power BI** using sales data (Jan 2015 – Dec 2015), supported by SQL queries, to deliver insights into **total revenue, orders, pizzas sold, category/size performance, and best/worst sellers**.  

The dashboard helps business stakeholders monitor **Sales KPIs, Daily & Monthly Order Trends, Category/Size Contribution, and Product-Level Performance**, enabling **Data-Driven Decisions** for marketing, inventory, and operations.  

--- 

📊 **Live Dashboard**  
I created **two interactive dashboards** in Power BI:  
- **Home Section** – Sales KPIs, daily/monthly trends, category/size breakdown  
- **Best/Worst Sellers Section** – Top & bottom pizzas by revenue, quantity, and orders. 
- **Note:** The dashboard size is comparatively larger than usual. For the best experience, reduce the view to **70%** in Power BI Service — this way you can clearly see all visuals and enjoy exploring the dashboard.
  
🔗 You can explore it **Live** here: [View Dashboard](https://app.powerbi.com/view?r=eyJrIjoiZWY0ZmViMmItNzlhZS00YjVhLTljNDktY2U3ZWRmYjg2N2IzIiwidCI6ImNhZDFhYWU2LTc3MjEtNGE2Yy05ZWM3LWY1MWQ4YTJkYjY5NiJ9)  

---

📊 **Dashboard Overview**  
### 🏠 Home Section  
![Home Section](https://github.com/KamalNayanTiwary/Pizza-Sales-Analysis-Dashboard/blob/main/Snapshot%20of%20the%20Dashboard%20(Home).png)  

The **Home Section** provides a complete **business snapshot** with high-level KPIs, time-based trends, and category/size breakdowns.  

- **Top-Level KPIs**  
  - 💰 **Total Revenue:** 817.86K (overall sales performance)  
  - 📦 **Total Pizzas Sold:** 49,574 (demand volume)  
  - 🛒 **Total Orders:** 21,350 (unique transactions)  
  - 📊 **Avg Order Value:** 38.31 (spend per order)  
  - 🍕 **Avg Pizzas per Order:** 2.32 (customer buying behavior)  

- **Daily & Monthly Trends**  
  - 📅 Orders peak on **Friday & Saturday evenings**, highlighting weekend demand.  
  - 📆 Monthly analysis shows **July and January** as the highest-performing months.  
  - 🕒 Seasonal trends indicate **holiday spikes** and **weekend-driven consumption patterns**.  

- **Category Performance**  
  - 🍕 **Classic:** 26.91% of total sales (top-performing segment)  
  - 🍕 **Supreme:** 25.46%  
  - 🥗 **Veggie:** 23.96%  
  - 🧀 **Paneer:** 23.68%  
  - Insight: All categories perform **consistently**, but Classic dominates slightly.  

- **Size Performance**  
  - 🟢 **Large pizzas:** 45.89% of total sales (clear customer favorite)  
  - 🟡 **Medium pizzas:** second-highest contributor.  
  - 🔵 **Small & Extra Large:** contribute less but capture niche demand.  

---

### ⭐ Best/Worst Sellers Section  
![Best Sellers Section](https://github.com/KamalNayanTiwary/Pizza-Sales-Analysis-Dashboard/blob/main/Snapshot%20of%20the%20Dashboard%20(B-W-Seller).png)  

The **Best & Worst Sellers Section** highlights product-level performance for decision-making around promotions, menu optimization, and inventory planning.  

- **Best-Selling Pizzas**  
  - 💰 **By Revenue:** *The Thai Paneer Pizza* – 43K  
  - 📦 **By Quantity Sold:** *The Classic Deluxe Pizza* – 2.5K sold  
  - 🛒 **By Orders:** *The Classic Deluxe Pizza* – 2.3K orders  
  - Insight: Deluxe & Paneer-based pizzas are **Customer Favorites** across metrics.  

- **Worst-Selling Pizzas**  
  - 💰 **By Revenue:** *The Brie Carre Pizza* – 12K  
  - 📦 **By Quantity Sold:** *The Brie Carre Pizza* – 490 sold  
  - 🛒 **By Orders:** *The Brie Carre Pizza* – 480 orders  
  - Insight: *Brie Carre* consistently underperforms, suggesting need for **Menu Review**.  

---

📄 **SQL Queries**  
You can check the detailed SQL queries I wrote for KPIs, trends, and best/worst sellers here:  
➡️ [Pizza Sales SQL Queries (PDF)](https://github.com/KamalNayanTiwary/Pizza-Sales-Analysis-Dashboard---SQL-and-Power-BI/blob/main/PIZZA%20SALES-SQL%20Queries%20by%20Kamal.pdf)

---

🚨 **Business Problem**  
Pizza chains need clear visibility into **sales performance, category contributions, and product-level insights**. Without analysis, it becomes difficult to:  

- Track **total revenue, orders, and pizzas sold**  
- Identify **busiest days & months** for operations planning  
- Compare **pizza categories and sizes** by sales contribution  
- Analyze **best & worst selling pizzas** by revenue, quantity, and orders  
- Improve **customer targeting and menu optimization**  

---

❓ **Key Questions (KPIs)**  
Based on customer requirements, the following questions were answered via SQL + Power BI:  

- What is the **total revenue, total pizzas sold, and average order value**?  
- What are the **daily and monthly order trends**?  
- How much do different **pizza categories & sizes contribute** to sales?  
- Which are the **top 5 pizzas by revenue, quantity, and orders**?  
- Which are the **bottom 5 pizzas by revenue, quantity, and orders**?  
- What are the **busiest days & months** for pizza sales?  

---

⚙️ **Process**  

- **Data Import**: Loaded the raw pizza sales dataset into **MS SQL Server**.  
- **SQL Analysis**: Wrote SQL queries in SSMS to calculate KPIs and generate insights:  
  - Total Revenue, Avg Order Value, Total Orders, Avg Pizzas/Order  
  - Daily & Monthly Order Trends  
  - % Sales by Category & Size  
  - Top & Bottom 5 Pizzas (Revenue, Quantity, Orders)  
- **Data Export**: Exported the query results from MS SQL Server for reporting and visualization.  
- **Power BI Dashboard**:  
  - Built KPI cards for sales metrics.  
  - Visualized trends (daily, monthly) with bar & line charts.  
  - Used pie/donut charts for category & size contribution.  
  - Highlighted best/worst sellers with bar charts.  
- **Design & Interactivity**: Added slicers for **Pizza Category** and **Date Range** to make the dashboard fully interactive.  

---

🔎 **Project Insights**  

- **Peak Demand**: Sales spike on **weekends** and during **July & January**.  
- **Category Split**: Classic pizzas dominate, but all categories perform relatively evenly.  
- **Size Preference**: Large pizzas drive almost **half of total revenue**.  
- **Best Performer**: *The Thai Paneer Pizza* leads in revenue.  
- **Weak Performer**: *The Brie Carre Pizza* performs lowest in all metrics.  

---

✅ **Final Conclusion**  

- **Marketing Strategy**: Run targeted campaigns during weekends & peak months.  
- **Product Mix**: Promote Classic and Supreme categories for steady growth.  
- **Size Focus**: Large pizzas should remain the flagship offering.  
- **Menu Optimization**: Consider reworking or replacing underperforming pizzas like Brie Carre.  
- **Customer Insights**: Paneer & Deluxe variants resonate strongly with buyers.  

---

🛠️ **Tech Stack**  
- **MS SQL Server** – Data storage & querying  
- **SQL Server Management Studio (SSMS)** – Query writing & data export  
- **Power BI** – Dashboard design & visualization  

---

👨‍💻 **Author & Contact**  
**Kamal Nayan Tiwary**  
**Data Analyst**  

📧 Email: **kamalnayantiwary73@gmail.com**  
🔗 [LinkedIn](https://www.linkedin.com/in/kamal-nayan-tiwary-2022-2026-/)  

