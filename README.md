# AtliQ Business Insights 360

## Overview

**AtliQ Hardware**, a rapidly expanding company specializing in computers and accessories, faced unexpected losses after launching its store in America. Recognizing the need for advanced analytics to gain a competitive edge, AtliQ decided to implement Power BI for insights into finance, sales, marketing, and supply chain operations. This project delivers a comprehensive analytics solution to empower data-driven decision-making across the organization.

This project was completed as part of the **Codebasics Power BI Course**, which provided comprehensive guidance and practical insights into building analytics solutions.
## Explore the live dashboard here - [Dashboard Link](https://app.powerbi.com/view?r=eyJrIjoiYjdlM2MzZmQtYzc3MS00NzZmLWIyZDItMDM5Yjg3MjA0NzdkIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)
## Project Presentation On Linkedin - [Presentation Link](https://www.linkedin.com/posts/trishul-krishna_dataanalyst-dataanalyticsproject-codebasicsbootcamp-activity-7273011730329346048-qAEW?utm_source=share&utm_medium=member_desktop)

---

## Objectives

1. Enable stakeholders to make informed decisions across finance, sales, marketing, and supply chain domains.
2. Leverage Power BI to visualize and analyze data for actionable insights.
3. Develop a robust data model to ensure efficient report performance.

---


## Datasets

### **gdb041**
- **dim_customer**: Contains static customer details.
- **dim_market**: Static data on market segments.
- **dim_product**: Product details.
- **fact_forecast_monthly**: Forecasted customer needs for better warehouse management and cost reduction.
- **fact_sales_monthly**: Contains actual sold quantities, replacing forecast values.

### **gdb056**
- **freight_cost**: Costs associated with freight.
- **gross_price**: Gross pricing details.
- **manufacturing_cost**: Production cost details.
- **pre_invoice_deductions**: Deductions applied before invoicing.
- **post_invoice_deductions**: Deductions applied after invoicing.

---

## Data Processing Workflow

1. **Data Extraction**: Data imported from MySQL into Power BI.
2. **Data Cleaning**: Removed inconsistencies and ensured data quality.
3. **Data Modeling**: Followed the Snowflake schema for optimal performance.
4. **Data Analysis**: Built insights using calculated columns, DAX measures, and visualizations.

### Importance of Data Modeling

Data modeling is a critical step that underpins the success of visualizations and ensures report efficiency. Without proper modeling, analysis and reporting can become cumbersome and error-prone.
![BI360 DataModel](https://github.com/user-attachments/assets/b53bbe45-ec40-48c1-a4ef-73d4d744f0fc)

---

## Power BI Dashboard Overview

The dashboard consists of six interactive pages:

1. **Home Page**: Landing page with navigation buttons to access different insights.
![Home Page](https://github.com/user-attachments/assets/52cd8972-54f9-4490-b3c3-bea2ba871f12)

2. **Finance Page**:
   - Profit and Loss statements.
   - Top and Bottom Products and Customers by Net Sales.
   - Budgeting and cost control insights.
     ![Finance View](https://github.com/user-attachments/assets/c6919c8e-3700-422a-9fd0-f1f65e59e48f)

3. **Sales Page**:
   - Customer performance by Net Sales.
   - Gross Margin and Gross Margin %.
   - Revenue trends and market share analysis.
![Sales View](https://github.com/user-attachments/assets/9c867cdc-bdb4-494b-b505-34d530418b0e)

4. **Marketing Page**:
   - Segment performance by Gross Margin % and Net Profit %.
   - Customer engagement and brand visibility metrics.
![Marketing View](https://github.com/user-attachments/assets/e7b47f26-5db2-4970-bf51-1f82c2e896fd)

5. **Supply Chain Page**:
   - Forecast accuracy and Net error metrics.
   - Inventory and supplier performance analysis.
![Supply Chain View](https://github.com/user-attachments/assets/a92fe7cf-82ee-48a7-aa2d-e0d5d55d0598)

6. **Executive Page**:
   - High-level KPIs like Net Sales, Gross Margin %, and Net Profit %.
   - Performance by channel and sub-region.
   - Highlights of top customers and products.
![Executive View](https://github.com/user-attachments/assets/78340070-6182-4abd-b250-5f8205b1e17c)

---

## Key Features and Skills Learned

- **Power BI Features**: Calculated columns, DAX measures, bookmarks, custom tooltips, dynamic titles, and conditional formatting.
- **Data Tools**: Power BI Desktop, DAX Studio (file size optimization), MySQL.
- **Business Metrics**: Gross Margin %, Net Profit %, COGS, YTD, YTG, and more.
- **Best Practices**: Snowflake schema modeling, clean and efficient visual design, and dynamic report navigation.

---

## Tools Used

- **Power BI**: Visualization and reporting.
- **SQL**: Data extraction and preparation.
- **DAX**: Custom measures and calculated columns.
- **DAX Studio**: Performance optimization.

---



## Conclusion

This project demonstrates the power of analytics in addressing business challenges and improving profitability. By leveraging Power BI, AtliQ Hardware is now equipped to make informed decisions, answer key business questions, and maintain a competitive edge in the market.

---



