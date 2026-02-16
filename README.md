# Ferns & Petals (FNP) Sales Analysis  
### End-to-End Data & Business Analytics Project using Microsoft Excel (Power Query + Power Pivot)

## Project Summary

This project analyzes transactional sales data from Ferns & Petals (FNP), an occasion-based e-commerce gifting company operating across multiple Indian cities.

The objective was to perform end-to-end analysis — from raw data extraction to executive dashboard delivery — and generate actionable business insights related to revenue performance, product contribution, seasonal demand, customer behavior, and operational efficiency.

The entire solution was built using Microsoft Excel, leveraging:

- Power Query (ETL & Data Transformation)
- Power Pivot (Data Modeling)
- Pivot Tables & Charts
- Slicers for interactivity
- KPI Cards for executive reporting

This project simulates the workflow of a Business/Data Analyst working with operational sales data.

---

## Business Questions Addressed

1. What is the total revenue generated?
2. What is the average order-to-delivery time?
3. How does monthly sales performance fluctuate?
4. Which products generate the highest revenue?
5. What is the average customer spending?
6. Which cities contribute the highest number of orders?
7. How does revenue vary across occasions?
8. Does higher order quantity impact delivery time?

---

## Data Preparation & Modeling

### Data Cleaning (Power Query)

- Removed duplicate and inconsistent records  
- Standardized date formats  
- Derived calculated fields:
  - Delivery Duration (Delivery Date – Order Date)
  - Order Month
  - Occasion segmentation
- Ensured correct data types for modeling  

The dataset was transformed into an analysis-ready format before loading into the data model.

---

### Data Modeling (Power Pivot)

- Built relational model between Orders, Products, Customers, and Dates
- Created DAX measures including:
  - Total Revenue
  - Total Orders
  - Average Customer Spend
  - Average Delivery Time
  - Revenue by Occasion
  - Revenue by Category

Using Power Pivot allowed Excel to function as a BI tool rather than a flat spreadsheet.

---

## Key Insights

### Overall Performance (2023)

- Total Orders: 990  
- Total Revenue: ₹5,86,176  
- Average Customer Spend: ₹4,652  
- Average Delivery Time: 5.72 Days  

Revenue per customer indicates strong bundled-product purchasing behavior.

---

### Revenue by Occasion

- Highest Revenue: Anniversary & Raksha Bandhan
- Strong Contribution: Holi
- Relatively Lower: Diwali & Valentine’s Day

Relationship-driven occasions generate stronger revenue than high-volume commercial festivals.

---

### Revenue by Category

- Top Category: Soft Toys
- Moderate: Sweets, Colors
- Lowest: Mugs

Customers prefer emotionally symbolic products over utility items.

---

### Monthly Sales Trend

Sales spikes observed during:
- February
- June
- December

Noticeable dip around April.

Demand is event-driven and seasonal.

---

### Top 5 Products by Revenue

Bundled gift sets dominate revenue contribution, reinforcing the effectiveness of curated packaging strategies.

---

### Top Cities by Orders

Order distribution shows strong participation from Tier-2 and Tier-3 cities.

Regional market penetration is significant and scalable.

---

## Operational Analysis – Order Quantity vs Delivery Time

Average delivery time remains approximately 5.72 days across the dataset.

Preliminary observation suggests delivery duration is relatively stable; however, a deeper statistical correlation analysis between order quantity and delivery time would further validate supply chain scalability.

---

## Tools & Technologies Used

- Microsoft Excel  
- Power Query  
- Power Pivot  
- DAX Measures  
- Pivot Tables  
- Interactive Dashboard Design  

---

## Skills Demonstrated

- End-to-end data cleaning and transformation  
- Data modeling using Power Pivot  
- KPI creation using DAX  
- Business problem translation into analytical outputs  
- Interactive dashboard development  
- Insight generation for strategic decision-making  

---

## Future Enhancements

- Statistical correlation (Order Quantity vs Delivery Time)
- Profit margin analysis
- Customer segmentation
- Demand forecasting
- Migration to Power BI
