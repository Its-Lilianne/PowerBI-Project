# Mavin Toy Store Business Analysis

# Introduction
This Business Intelligence (BI) analysis focuses on Maven Toy Store, a leading toy retail chain in Mexico. The dataset encompasses extensive sales and inventory data, including product details, store locations, daily sales transactions, and stock levels across multiple outlets.

### Project Overview
This analysis evaluates sales and inventory data from Maven Toy Store, a toy retail chain in Mexico. Using Microsoft Power BI, key insights were derived on product profitability, store performance, seasonal trends, and inventory management. Findings revealed that Toys and Electronics drive the highest profits, with Downtown stores performing best. Sales peak between March and July, while October sees the lowest revenue. Inventory analysis indicates stock will last 15-17 days. Recommendations include optimising inventory, investing in high-performing locations, and addressing seasonal sales fluctuations to enhance profitability and business growth.


![image alt](https://github.com/Its-Lilianne/PowerBI-Project/blob/a5d370dfe673b0f7eb79ef51773b402564115920/Maven%20Toy%20Store%20--%20Dashboad.png)


### Table of Contents

- [Introduction](#introduction)
- [Project Overview](#project-overview)
- [Objective](#objectives)
- [Key Business Questions](#key-business-questions)
- [Tools and Methodologies](#tools-and-methodologies)
- [Data Processing ](#data-processing)
- [Data Modelling](#data-modelling)
- [Key Insights](#key-insights)
- [Summary & Recommendations](#summary-&-recommendations)
- [References](#references)


### Objectives
The primary goal of this analysis is to generate actionable insights into Maven Toy Store's overall sales performance and profitability by evaluating: 
- Store location performance 
- Seasonal sales trends 
- Product profitability and sales effectiveness 
- Provide recommendations to optimise business strategies.

 
### Key Business Questions 
1. Which product categories yield the highest profits, and how do these trends vary across different store locations?
2. Are there identifiable seasonal sales patterns?
3. What is the company's current market reach in terms of store distribution and geographic presence?
4. What is the total inventory value, and how long can it sustain current sales levels?
5. Which stores perform best and worst in terms of revenue and profitability?


### Tools and Methodologies 
*Tool Used:* *Microsoft Power BI* [Website](https://www.microsoft.com/en-us/power-platform/products/power-bi)



### Techniques
The following BI techniques and concepts were applied:
1. Data Cleaning & Transformation using Power Query
2. Data Modelling to establish structured relationships between tables
3. DAX Implementation for advanced calculations and metrics
4. Data Visualisation for interactive and insightful dashboards
5. Comprehensive Project Documentation for clear reporting of insights



## Data Processing 

### Data Importation and Cleaning 
Importation Process: Data was ingested using Power BI’s Excel connector. 

#### Cleaning Steps: 
- Promoted headers for consistent column naming. 
- Converted ID columns from whole numbers to text (as they serve as unique identifiers rather than numerical values). 
- Added calculated fields for total product cost, total product price, and profit in the sales dataset. 
- Corrected data types to ensure consistency. 
- Trimmed redundant store names in the Stores Table for clarity. 
- Created a Dates Table using CALENDARAUTO() to facilitate temporal analysis, extracting year, quarter, month, and day attributes.


## Data Modelling 
Effective data modelling structures raw data into an analytical framework, allowing seamless relationship-building between tables. In this project, Power BI automatically identified table relationships, forming a **star schema model**: 

1. **Fact Table:** Sales Table, Inventory
2. **Dimension Tables:** Products, Stores, and Dates

![image alt](https://github.com/Its-Lilianne/PowerBI-Project/blob/fcfebb7961875bf33593792cbc3ae8a0f735fe18/Maven%20Toy%20Store%20--%20Relationship%20Model.png)



## Key Insights

### Product Analysis 
1. **Which product categories generate the highest profits?**
- Toys are the most profitable, contributing $1.08M (26.89%) of total profits. 
- Electronics follow closely with $1M (25%). 
- Sports & Outdoor products generate the lowest profit at $500K.

2. **Are these profit trends location-dependent?**
- Electronics dominate in Airport and Commercial locations. 
- Toys perform best in Downtown and Residential areas.
 
3. **Top Performing Products**
**Highest Profit-Generating Products:**
- Colorbuds - $835K 
- Action Figure - $348K 
- Lego Bricks - $298K 
- Deck of Cards - $252K 
- Glass Marbles - $190K

4. **Most Sold Products**
  - Colorbuds - 104K units (23.5%)
  - Play-Doh Can - 103K units (23.2%)
  - Barrel O’Slime - 91K units
  - Deck of Cards - 84K units
  - Magic Sand - 61K units

![image alt]()

 **Notably, Play-Doh can rank high in sales volume but not in profitability.**
