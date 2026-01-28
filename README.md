# AtliQ-Supply-Chain-Analysis

## Project Overview
End-to-end Power BI dashboard analyzing AtliQ Mart's supply chain performance across orders, service levels (OT/IF/OTIF), and order lines. Focuses on identifying bottlenecks in delivery, fulfillment, and key customers to optimize operations and meet targets. Built for Codebasics challenge (Oct 2022).

## 🛠️ Tools Used

**Skills, Tools & Techniques Used**  
▶️ **Power BI Desktop & Service** – dashboard development & publishing for supply chain KPIs  
▶️ **Power Query (ETL)** – data cleaning, order transformation, and shaping for OT/IF/OTIF metrics  
▶️ **Data Modelling** – table relationships & star-schema for customers/cities/orders integration  
▶️ **DAX** – custom measures for OT (59.03%), IF (52.78%), OTIF (29.02%), LIFR (65.96%), VOFR  
▶️ **Time-Based Analysis** – daily/monthly trends vs targets, performance gap tracking  
▶️ **Interactive Reporting** – slicers for Year/Month/City/Customer, cross-filtering & drill-downs  
▶️ **Data Visualization** – KPI cards, trend lines, scatter plots, service level analysis charts  
▶️ **Business Analysis (Supply Chain KPIs)** – OTIF gaps, customer retention risks, optimization insights  

## 📈 Key Metrics Tracked
- **Orders**: Total 32K, Ontime 19K (59.03%), Infull 17K (52.78%), OTIF 9.2K (29.02%)  
- **Order Lines**: 57K lines, LIFR 65.96%, VOFR 96.59%, delayed days analysis  
- **Targets gaps**: OT -31.43% vs 86%, IF -31% vs 76.5%, OTIF -56% vs 66%  

## 🏠 Home Page
- Central navigation hub for the entire Supply Chain Challenge report  
- High-level KPIs: 32K total orders, OTIF 29.02% (vs 65.91% target), LIFR 65.96%  
- Clean design with filters for Year/Month/City/Customer/Category for supply chain execs  

## 📘 Orders Overview
- Orders by city (Ahmedabad/Vadodara/Surat), category (Dairy 25K double Food/Beverages), top customers (53% from 6 key stores)  
- Performance: OT/IF/OTIF by city/customer/month (May/Aug slight improvements)  
- Daily/monthly trends showing consistent sub-target levels  

## 💰 Performance Overview
- Trend analysis of OT (57-67%), IF (50-60%), OTIF (25-37%) vs targets over time  
- City-wise: Ahmedabad 29.33% OTIF, Surat 30.07%  
- Monthly deep dive: May/Aug 2022 best but still far from targets  

## 📉 Service Level Analysis
- Customer scatter: Acclaimed Stores/Coolblue/Lotus Mart low OT/IF/OTIF (~15-16%)  
- Alerts: Sorefoz (Ahmedabad), Info Stores (Surat), Elite/Vijay (Baroda) poor fulfillment  
- Identifies stockout risks and replenishment needs  

## 🎯 Business Value
- **Operations**: Pinpoint underperformers (key customers at risk of contract loss)  
- **Supply Chain**: Optimize delivery (75% late for top customers by 2-3 days)  
- **Management**: Data-driven fixes for OTIF gaps, prioritize Dairy/top cities/customers  

## 📌 Key Takeaways
- Dairy orders dominate; average metrics 30-50% below targets daily/monthly  
- Key customers (Acclaimed/Lotus/Coolblue) drive 53% orders but poor service risks churn  
- Delayed lines (75% late for priors); focus replenishment in Ahmedabad/Surat/Baroda  
- May/Aug improvements signal potential with targeted interventions  

## 🚀 Conclusion
This Supply Chain Challenge project showcases Power BI expertise in DAX, modeling, and storytelling for logistics. It turns raw order data into insights exposing OTIF failures, customer risks, and optimization paths—directly boosting supply chain efficiency and retention.
