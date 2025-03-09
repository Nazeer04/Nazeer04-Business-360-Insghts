# AtliQ Business Pulse 360
# BI-360 Power BI Dashboard
## Business Insights 360 Project Report for AtliQ Hardwares

### Project Overview
AtliQ Hardware has experienced rapid growth in recent years. To maintain a competitive edge and drive strategic decision-making, the company has embraced Power BI for advanced data analytics. This project focuses on delivering actionable insights across key business areas—Finance, Sales, Marketing, and Supply Chain—enabling stakeholders to make informed, data-driven decisions with greater efficiency.

[Live Power BI Report Link]https://app.powerbi.com/view?r=eyJrIjoiMmU0MTg0YTktZDk4My00NmZmLWE1YTAtM2ZhODNkOWRmNjI1IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9
-----

## Tech Stacks
- **SQL**
- **Power BI Desktop**
- **Excel**
- **DAX Language**
- **DAX Studio** (for report optimization)
- **Project Charter File**
- **Power BI Service**

-----

## Power BI Techniques Learned
- Identifying key business questions before starting analysis.
- Ensuring data validation for accuracy and consistency.
- Implementing best practices in data modeling for optimized performance.
- Creating calculated columns and measures using DAX functions.
- Using the DIVIDE function to prevent division-by-zero errors.
- Creating a date table using M language for time intelligence.
- Using bookmarks to switch between visuals.
- Implementing page navigation with buttons for better interactivity.
- Adding dynamic titles that update based on applied filters.
- Integrating KPI indicators to highlight key performance metrics.
- Applying conditional formatting with icons or background colors for better insights.
- Deploying reports to Power BI Service for seamless access.
- Setting up a personal gateway for automated data refresh.
- Creating a Power BI App for enhanced collaboration via workspaces and access permissions.

----

## Business Terminology
- **Gross Price**
- **Pre-invoice Deductions**
- **Post-Invoice Deductions**
- **Net Invoice Sale**
- **Gross Margin**
- **Net Sales**
- **Net Profit**
- **COGS** - Cost of Goods Sold
- **YTD** - Year to Date
- **YTG** - Year to Go
- **Direct Retailers**
- **Distributors**
- **Consumers**

----

**Company Background** 

AtliQ Hardware has grown rapidly and expanded globally, selling computers and accessories through:

**Retailers**  
**Direct Sales**  
**Distributors**

Recently, the company faced unexpected losses after opening a store in America based on intuition instead of data. Meanwhile, competitors used analytics to make smarter decisions.

To stay competitive, AtliQ Hardware is now building an analytics team to make data-driven decisions and gain valuable business insights.

---------

**Project Kickoff: Setting the Foundation**

During the project kickoff, it is essential to clarify all aspects of the project, including:
- The objective of building the Power BI dashboard.
- Success metrics for the project.
- Project timeline and deadlines.
- Stakeholder expectations for previews before the final release.
- Fears or concerns stakeholders have about the project.
- The purpose of the dashboard and who will be using it.
- Stakeholder expectations and possible risks.
- Required resources and data for dashboard development.
- Stakeholder input on dashboard design and views.

--------

## Dataset Understanding
Understanding the dataset is critical for accurate analysis. The dataset contains:

- **Dimension Table**: Static data such as customer and product details.
- **Fact Table**: Transactional data for sales and forecasting.

-------

### Key Tables
- **dim_customer**: Contains customer information across 27 markets and two platforms (Brick & Mortar, E-commerce).
- **dim_market**: Contains market details across 27 markets, seven sub-zones, and four regions.
- **dim_product**: Product data across divisions (Peripherals, PC, Networking, etc.).
- **fact_forecast_monthly**: Forecasting customer demand to improve satisfaction and reduce warehouse costs.
- **fact_sales_monthly**: Sales data, structured similarly to the forecast table, but with actual sales values.
- **freight_cost**: Travel and other costs per market.
- **gross_price**: Gross prices by product code.
- **manufacturing_cost**: Manufacturing costs by product and year.
- **pre_invoice_deductions**: Pre-invoice deductions percentage for customers.
- **post_invoice_deductions**: Post-invoice deductions and additional deductions.

--
## Importing Data into Power BI
The dataset is sourced from a MySQL database. The data is imported into Power BI by providing the database access credentials.

----
## Data Modeling
Data modeling forms the foundation of the Power BI report. Poor data modeling can negatively impact report performance. In this project, we followed the **Snowflake Data Modeling Method** to ensure efficiency and scalability.

![DATA MODEL]
(https://github.com/user-attachments/assets/d8824228-8a0b-4fae-9750-025894b60251)

----

## Dashboard Design
Based on the received mockups, the team designed various views and created necessary measures for the dashboard:

## Home View: 
A landing page with navigation buttons for all views.

![HOME](https://github.com/user-attachments/assets/f53436a0-6edc-4717-8b51-c4b2a3f6d220)

## Info:

![INFO](https://github.com/user-attachments/assets/2e6913ec-ad4e-487f-9956-c10d1533a367)

## Finance View: 
Key financial metrics and insights.

![FINANCE](https://github.com/user-attachments/assets/0bc44378-125b-4bf4-beb7-831a7354288f)

## Sales View:
Sales performance across markets and channels.

![SALES](https://github.com/user-attachments/assets/af93fb0d-dfcf-4ce9-ad65-45d4951f94bc)

## Marketing View:
Marketing KPIs and campaign performance.

 ![MARKETING](https://github.com/user-attachments/assets/d5b37814-97be-49b5-bcb8-9296f7e313c1)
 
## Supply Chain View: 
Insights into the supply chain and inventory management.

![SUPPLY CHAIN](https://github.com/user-attachments/assets/4d036fff-d5c4-443a-90c1-255422b3ab1a)

-bcb8-9296f7e313c1)

## Executive View: 
High-level executive summary of business performance.

![EXECUTIVE](https://github.com/user-attachments/assets/ed0a124f-5744-42c9-b462-9c6e1ee5331c)

## Support:

![SUPPORT](https://github.com/user-attachments/assets/590d6f72-ad36-4d2c-8f45-60073ded884a)

## Project Outcome
This dashboard will help AtliQ Hardware make informed decisions based on data. It answers several critical business questions and supports deeper analysis in areas like Finance, Sales, Marketing, and Supply Chain.

---

### Contact
For any questions or suggestions, feel free to [contact me on LinkedIn]









