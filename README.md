# E-Commerce-Sales-Analysis
This project is a complete end-to-end *E-Commerce Sales Analysis Dashboard* developed in *Microsoft Power BI* to transform raw transactional sales data into meaningful business intelligence and strategic insights.
#  E-Commerce Sales Analysis Dashboard | Power BI Project

<p align="center">
  <b>An Interactive Business Intelligence Solution for Revenue, Profitability, Regional Sales, Customer Segmentation, and Operational Performance Analysis</b>
</p>

---

#  Project Overview

This project is a complete end-to-end *E-Commerce Sales Analysis Dashboard* developed using *Microsoft Power BI* to transform raw transactional sales data into actionable business intelligence insights.

The dashboard was designed to help analyze and monitor:

- Revenue Performance
- Profitability
- Customer Segments
- Product Performance
- Regional Orders
- Shipping Analysis
- Return Analysis
- Monthly Sales Trends
- Geographic Revenue Distribution

The project combines *advanced data modeling, **custom DAX calculations, **time intelligence functions, and **interactive visualizations* to create a professional analytical reporting solution.

This dashboard allows decision-makers to quickly identify trends, evaluate business performance, monitor KPIs, and explore operational insights through interactive filtering and drill-down analysis.

#  Project Objectives

The main objective of this project was to build a professional business intelligence dashboard capable of:

- Monitoring overall sales and profit performance
- Tracking regional order distribution
- Understanding customer segment contribution
- Analyzing product sub-category performance
- Measuring return impact on profitability
- Exploring revenue trends over time
- Creating dynamic and interactive reporting experiences
- Applying professional BI data modeling techniques

---

# Tools & Technologies Used

| Technology | Purpose |
|---|---|
| Microsoft Power BI | Dashboard Development |
| Power Query | Data Cleaning & Transformation |
| DAX (Data Analysis Expressions) | KPI & Measure Calculations |
| Data Modeling | Relationship Management |
| Star Schema | Fact & Dimension Modeling |
| Snowflake Schema | Product Hierarchy Normalization |

---

#  Data Preparation & Transformation

Before building the dashboard, the dataset was cleaned and transformed using *Power Query*.

## Data Preparation Tasks Performed

- Removed unnecessary columns
- Cleaned inconsistent values
- Organized date fields
- Standardized product hierarchy
- Structured customer and regional information
- Prepared fact and dimension tables
- Optimized relationships for analytical performance

The transformation process ensured better dashboard efficiency and cleaner reporting logic.

---

#  Data Modeling & Schema Design

A professional business intelligence data model was designed to improve analytical performance and maintain clean relationships between datasets.

---

#  Star Schema Implementation

A *Star Schema* structure was implemented to create efficient relationships between the central fact table and supporting dimension tables.

## Fact Table
- Sales Table

## Dimension Tables
- Dim Date
- Dim Region
- Return Table

### Benefits Achieved
- Faster dashboard performance
- Simplified analytical calculations
- Better filtering behavior
- Improved scalability

---

#  Snowflake Schema Implementation

A *Snowflake Schema* approach was used for product hierarchy normalization.

## Product Hierarchy Tables
- Dim Product
- Dim Category
- Dim Sub-Category

### Benefits Achieved
- Reduced data redundancy
- Better hierarchy management
- Improved category-level analysis
- Organized product structure

---

#  DAX Measures & KPI Development

Custom DAX measures were created to calculate financial metrics, operational KPIs, profitability analysis, and return analysis.

The dashboard includes several calculated measures that dynamically respond to filters and slicers.

---

#  KPI Measures Created

| KPI | Description |
|---|---|
| Total Revenue | Overall generated sales revenue |
| Total Profit | Net business profit |
| Total Cost | Total operational/product cost |
| Total Orders | Number of customer orders |
| Total Quantity | Quantity of products sold |
| Total Products | Number of products available |
| Returned Revenue | Revenue affected by returned products |
| Returned Profit | Profit loss due to returns |
| Returned Cost | Cost associated with returns |
| Profit Margin % | Overall profitability percentage |

---

#  Time Intelligence Functions

Advanced Time Intelligence calculations were implemented using the *Dim Date Table*.

## Time-Based Features Implemented

- Monthly Revenue Tracking
- Revenue Trend Analysis
- Quarterly Analysis
- Yearly Performance Analysis
- Start of Month Calculations
- Week-Based Analysis
- Dynamic Date Filtering

These calculations help analyze how business performance changes over time.

---

#  Dashboard Pages & Analysis

The dashboard contains multiple analytical pages with interactive navigation and filtering capabilities.
each page contain two buttons one is a navigation button which allow us directly go to homepage another
is a default button which clear out all the filters of that page.
---

#  Homepage
![pbi1](images/pbi1.jpg)
The homepage acts as the main navigation interface for the entire dashboard.

## Features Included

- Interactive navigation buttons
- E-commerce themed dashboard design
- Clean UI/UX layout
- Multi-page routing structure

## Navigation Sections

- Executive Dashboard
- Regional Order Dashboard
- Sales Dashboard

---


#  Executive Dashboard Analysis
![pbi2](images/pbi2.jpg)
The Executive Dashboard provides a high-level overview of business performance and operational KPIs.

---

## KPI Cards Included

- Total Quantity
- Total Orders
- Total Products
- Total Revenue
- Total Profit

---

## Visualizations Used

###  Donut Charts

#### Shipping Mode Analysis
Analyzes revenue contribution by shipping methods:

- Standard Class
- First Class
- Second Class

#### Customer Segment Analysis
Analyzes order distribution by customer type:

- Consumer
- Corporate
- Home Office

---

###  Profit by Continent Analysis

A column chart was used to analyze profitability across continents.

## Continents Analyzed

- North America
- Europe
- Asia
- Australia
- Africa
- South America

This helps identify which regions contribute the most profit to the business.

---

###  Product Sub-Category Summary Table

A detailed summary table was created to analyze:

- Total Products
- Total Orders
- Total Quantities
- Total Cost
- Total Revenue
- Total Profit

for each product sub-category.

This helps identify high-performing and low-performing product groups.

---

###  Interactive Date Slicer

Dynamic date filtering was implemented to allow flexible analysis across different time periods.

Users can interactively explore business performance over custom date ranges.

---

#  Regional Order Dashboard
![pbi3](images/pbi3.jpg)
The Regional Order Dashboard focuses on geographic and regional sales analysis.

This page helps analyze where orders and revenue are generated globally.

---

#  Regional Insights Included

---

##  Top 5 Cities by Orders

A bar chart was created to analyze cities generating the highest number of orders.

### Top Performing Cities
- New York City
- Los Angeles
- Philadelphia
- San Francisco
- Santo Domingo

This helps identify strong-performing urban markets.

---

##  Revenue by Country Map

A geographic map visualization was implemented to display global revenue distribution.

The map helps analyze:
- Country-wise revenue generation
- Regional business concentration
- Geographic sales patterns

---

##  Order Priority Distribution

A donut chart was used to analyze order priorities.

### Priority Levels
- Critical
- High
- Medium
- Low

This helps understand operational order management patterns.

---

##  Continent Slicer

Interactive continent-level filtering was implemented.

### Available Filters
- Africa
- Asia
- Australia
- Europe
- North America
- South America

This enables region-specific analysis.

---

#  Sales Dashboard Analysis
![pbi4](images/pbi4.jpg)
The Sales Dashboard focuses on detailed financial and profitability analysis.

This page helps evaluate operational efficiency and revenue trends.

---

#  Financial KPI Cards

The dashboard includes several financial performance indicators:

- Total Cost
- Returned Cost
- Total Revenue
- Returned Revenue
- Total Profit
- Returned Profit
- Profit Margin %

These KPIs provide a complete overview of business profitability.

---

# Revenue Trend Analysis

An area chart was created to analyze revenue movement over time.

## Insights Generated
- Monthly revenue fluctuations
- Growth patterns
- Seasonal performance
- Sales consistency

This helps monitor long-term business performance.

---

#  Monthly KPI Summary Table

A detailed monthly financial analysis table was created containing:

- Total Cost
- Returned Cost
- Total Revenue
- Returned Revenue
- Total Profit
- Returned Profit
- Profit Margin %

This enables detailed month-by-month performance tracking.

---

#  Product Name Slicer

Interactive product-level filtering was implemented using a product slicer.

Users can dynamically filter dashboard visuals by:
- Product Name
- Product Categories
- Product Sub-Categories

This improves drill-down analysis capabilities.
Sales & Business Insights Analysis

Overview

This dashboard analysis evaluates product category performance based on:

* Revenue
* Profit
* Profit Margin
* Returned Revenue
* Monthly Revenue Trend

The goal is to identify:

* High-performing categories
* Low-performing categories
* Operational risks
* Growth opportunities
* Strategic business solutions


Executive Business Insights & Strategic Recommendations

1. Accessories Category

Business Condition

* Moderate revenue generation
* Stable but average profit margin
* Consistent monthly demand
* Returns are manageable

Business Insight

Accessories are functioning as a stable support category rather than a growth driver. The category contributes steady sales but lacks aggressive profitability growth.

Business Resolution

* Introduce bundled offers with higher-ticket items
* Use impulse marketing strategies
* Increase average order value through upselling
* Launch seasonal accessory campaigns

Strategic Recommendation

Focus on:

* Cross-selling
* Low-cost digital ads
* Product bundles



2. Appliances Category

Business Condition

* Strong revenue performance
* Good overall profitability
* Higher operational cost observed
* Revenue trend shows strong market demand

Business Insight

Appliances are one of the primary revenue-generating categories. However, operational expenses and return-related costs may reduce long-term profitability.

Business Resolution

* Optimize supplier negotiation
* Reduce logistics cost
* Improve product quality control
* Enhance customer support to reduce returns

Strategic Recommendation

Scale this category aggressively while improving operational efficiency.

3. Art Category

Business Condition

* Low revenue contribution
* Weak profitability
* Lower demand consistency

Business Insight

Art products appear to have limited market demand and weaker conversion performance compared to other categories.

Business Resolution

* Reposition products for premium audiences
* Use social media storytelling marketing
* Reduce slow-moving inventory
* Focus on niche customer targeting

Strategic Recommendation

Maintain limited inventory and operate through targeted campaigns instead of mass marketing.

4. Binders Category

Business Condition

* Extremely low revenue
* Low profit contribution
* Weak market growth trend

Business Insight

Binders show signs of underperformance and inefficient inventory utilization.

Business Resolution

* Reduce stock quantity
* Bundle with office supplies
* Offer bulk corporate discounts
* Improve B2B targeting

Strategic Recommendation

Avoid overinvestment. Position as a complementary product category.


5. Bookcases Category

Business Condition

* High revenue generation
* Strong market demand
* Moderate profit margin
* Operational cost remains high

Business Insight

Bookcases demonstrate healthy customer demand and strong sales consistency but profitability can still improve.

Business Resolution

* Optimize shipping & packaging
* Improve warehouse efficiency
* Introduce premium variants
* Focus on high-margin designs

Strategic Recommendation

Expand premium product lines to improve margins.


6. Chairs Category

Business Condition

* One of the strongest revenue categories
* Good sales consistency
* Profit fluctuations observed

Business Insight

Chairs are a core business category with strong customer demand but inconsistent profitability due to pricing or operational inefficiencies.

Business Resolution

* Dynamic pricing strategy
* Supplier cost optimization
* Reduce return rates through quality assurance
* Promote ergonomic premium products

Strategic Recommendation

Scale aggressively while monitoring profit stability.

7. Copiers Category

Business Condition

* Very high profit margin
* Strong profitability despite smaller sales volume

Business Insight

Copiers appear to be a high-margin premium category generating strong returns.

Business Resolution

* Increase premium customer targeting
* Expand B2B marketing
* Offer maintenance/service packages
* Prioritize repeat corporate clients

Strategic Recommendation

Treat Copiers as a strategic high-profit category.

8. Envelopes Category

Business Condition

* Low revenue contribution
* Stable but limited profitability

Business Insight

Envelopes serve mainly as a supporting office supply product.

Business Resolution

* Bundle with stationery products
* Promote bulk business orders
* Reduce unnecessary inventory holding

Strategic Recommendation

Maintain as a complementary category only.

9. Fasteners Category

Business Condition

* Low revenue and low profitability
* Weak overall business impact

Business Insight

Fasteners contribute minimally to total business growth.

Business Resolution

* Improve pricing strategy
* Bundle with related products
* Reduce warehousing cost

Strategic Recommendation

Keep minimal operational focus.

10. Furnishings Category

Business Condition

* Moderate revenue
* Lower-than-expected profit margin

Business Insight

Furnishings show customer demand but margin pressure indicates pricing or cost inefficiency.

Business Resolution

* Increase premium product offerings
* Reduce supplier dependency
* Improve inventory turnover
* Strengthen brand positioning

Strategic Recommendation

Improve brand differentiation to increase perceived value.

11. Labels Category

Business Condition

* Small revenue share
* Consistent but low profitability

Business Insight

Labels act as a low-risk, low-growth category.

Business Resolution

* Focus on corporate clients
* Sell in bulk
* Introduce subscription restocking models

Strategic Recommendation

Use for customer retention rather than growth.

12. Machines Category

Business Condition

* High revenue contribution
* Profit instability observed

Business Insight

Machines generate significant sales volume but profitability risk suggests high operational or return costs.

Business Resolution

* Strengthen after-sales support
* Improve warranty management
* Reduce defective product rates
* Enhance supplier quality checks

Strategic Recommendation

Critical category requiring operational optimization.

13. Paper Category

Business Condition

* Highest observed profit margin (~36%)
* Stable operational performance

Business Insight

Paper is one of the most profitable and operationally efficient categories.

Business Resolution

* Expand bulk sales strategy
* Focus on B2B institutional customers
* Increase recurring purchase contracts

Strategic Recommendation

Prioritize scaling due to high profitability.

14. Phones Category

Business Condition

* Strong revenue generation
* Competitive but volatile market trend

Business Insight

Phones drive major sales volume but may face pricing pressure and competitive margin reduction.

Business Resolution

* Improve promotional campaigns
* Offer financing/installment options
* Increase accessory bundling
* Strengthen customer loyalty programs

Strategic Recommendation

Aggressively scale while protecting margins.

15. Storage Category

Business Condition

* Moderate-to-good revenue
* Healthy profit consistency

Business Insight

Storage products show reliable customer demand and stable operational performance.

Business Resolution

* Expand product variety
* Improve warehouse bundling strategies
* Focus on home-office market trends

Strategic Recommendation

Safe growth category with long-term potential.

16. Supplies Category

Business Condition

* Lower revenue performance
* Stable but weak growth trend

Business Insight

Supplies serve mainly as recurring operational products rather than high-growth assets.

Business Resolution

* Introduce subscription purchasing
* Target office/corporate buyers
* Bundle with stationery categories

Strategic Recommendation

Optimize for recurring revenue.


17. Tables Category

Business Condition

* Lower profit margin despite reasonable demand
* Operational cost impact visible

Business Insight

Tables generate customer interest but profitability is weakened by cost structure and return issues.

Business Resolution

* Improve packaging efficiency
* Reduce transportation damage
* Optimize pricing structure
* Introduce premium customizable models

Strategic Recommendation

Improve operational efficiency before scaling further.

Overall Business Findings

High Potential Categories

* Appliances
* Chairs
* Phones
* Machines
* Paper
* Copiers

Stable Supporting Categories

* Accessories
* Storage
* Furnishings

Weak / Low Growth Categories

* Fasteners
* Envelopes
* Labels
* Binders

Final Strategic Business Recommendations

Short-Term Actions

* Reduce operational costs
* Improve inventory management
* Optimize low-performing categories
* Minimize product returns

Mid-Term Actions

* Increase B2B partnerships
* Launch bundled product campaigns
* Improve customer retention strategy

Long-Term Actions

* Focus on high-margin categories
* Use predictive sales analytics
* Expand premium product segments
* Build stronger supply chain efficiency
---

#  Interactive Features Implemented

The dashboard contains multiple interactive business intelligence features.

## Features Included

 Interactive Slicers  
 Cross-Filtering  
 Multi-Page Navigation  
 Dynamic KPI Updates  
 Geographic Drill-Down  
 Date-Based Filtering  
 Product-Level Analysis  
 Region-Based Analysis  
 Time-Series Exploration  

---

#  Business Intelligence Value

This project demonstrates how business intelligence tools can convert raw transactional data into meaningful insights.

The dashboard supports:
- Strategic decision-making
- Revenue monitoring
- Profitability tracking
- Regional analysis
- Product performance evaluation
- Operational analysis

---

#  Skills Demonstrated

---

#  Power BI Skills

- Data Modeling
- Dashboard Design
- DAX Calculations
- Time Intelligence
- Interactive Reporting
- KPI Development
- Power Query Transformation
- Visual Analytics

---

#  Business Analytics Skills

- Revenue Analysis
- Profitability Analysis
- Customer Segment Analysis
- Shipping Analysis
- Product Performance Analysis
- Regional Sales Analysis
- Return Analysis
- Trend Analysis

---

#  Project Highlights

 Professional Multi-Page Dashboard  
 Advanced KPI Reporting  
 Star Schema Data Model  
 Snowflake Schema Implementation  
 Time Intelligence Calculations  
 Interactive Filtering System  
 Geographic Revenue Analysis  
 Customer Segment Visualization  
 Product Sub-Category Analytics  
 Profitability & Return Analysis  

---

#  Dashboard Preview

##  Homepage
Interactive dashboard navigation interface.

##  Executive Dashboard
Business KPI and profitability overview.

##  Regional Dashboard
Regional sales and geographic analysis.

##  Sales Dashboard
Financial and trend-based analysis.

---

#  GitHub Tags

txt
powerbi
business-intelligence
data-analysis
dashboard
sales-analysis
ecommerce-dashboard
dax
power-query
time-intelligence
financial-analysis
business-dashboard
interactive-dashboard
analytics
data-modeling
star-schema
snowflake-schema


---

#  Developed By

*Ismam Tasnime*

Power BI | Data Analytics | Business Intelligence
