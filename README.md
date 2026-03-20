# Global Food Distribution Performance Analysis
## Power BI Dashboard | Sales Performance & Revenue Analytics Dashboard |
### Executive Summary
A global food distribution company needs better visibility into regional sales performance, product profitability, customer value, and expansion opportunities to maximize revenue and margins.
Using Power BI, I built an interactive multi-dashboard reporting system analyzing sales trends (2012–2014), gross margins, product performance, customer profitability, and geographic opportunities across the U.S. and Europe.
The analysis identified high-volume but medium-margin categories (Snacks), high-margin low-volume opportunities (Meat), key high-value customers (PageWave), and growth markets in Germany, Spain, and Nordic regions — enabling data-driven strategic decision-making.

### Business Problem

The company operates across multiple regions and product groups but lacks clear answers to:

Which product groups drive the most revenue in each region?

Where are margins strongest vs weakest?

Who are the most profitable customers?

Which managers generate the highest average sales?

Where should European expansion efforts focus?

Without structured analysis, decisions around pricing, product focus, and expansion remain reactive rather than strategic.

This project transforms raw operational data into actionable business insights.

### Methodology
**1. Data Preparation & Cleaning**

*Imported 5 datasets:*

Cities

Customers

Item Master

Sales Rep

Sales

Removed duplicates

Standardized date formats

Split Sales Rep data into ID, Name, and Manager fields

Ensured consistent data types

**2. Data Modeling**

Created relationships between Sales, Customers, Cities, Item Master, and Sales Rep tables.

Built a clean star-schema structure to support cross-filtering and performance analysis.

**3. Calculated Columns & Measures (DAX)*

*Created time-based columns:*

Year

Quarter

Month

Month Number (used for chronological sorting)

*Key measures:*

Gross Margin (%)

Average Sales per Invoice

Sales aggregations by region, product group, customer, and manager

**4. Dashboard Development**

*Built four interactive dashboards:*

High-Level Executive Dashboard

Product Performance Dashboard

Customer Insights Dashboard

Geographic Sales Dashboard

Each dashboard answers a specific business question using visual storytelling.

### Specific Skills Used| Tools & Technologies

Power BI

DAX (Data Analysis Expressions)

Excel (Pre-cleaning)

### Analytical Techniques

Relationships

### DAX Functions Used

SUM()

DIVIDE()

DISTINCTCOUNT()

YEAR()

QUARTER()

FORMAT()

MONTH()

### Results & Business Recommendations
### Regional Product Performance (2014 YTD)

USA Top Product Group: Canned Products

Europe Top Product Group: Deli

#### From 2012–2014:

2012 had the strongest U.S. performance

2013 was strongest for Europe

Both regions show seasonal peaks in February, March, August, and September

#### Insight:
Sales demonstrate consistent seasonality across both regions.

### Product Profitability Analysis

#### Among Breakfast Foods, Meat, and Snacks:

Snacks: Highest sales volume, medium margin

Meat: Lowest sales, highest gross margin

Breakfast Foods: Low sales and lower profitability

### Recommendation:

Increase sales focus on Meat (high-margin opportunity)

Improve margin strategy on Snacks (high-volume category)

Reevaluate Breakfast Foods performance

### Manager Performance

Top Manager (Highest Avg Sales per Invoice): Dennis Johnson

Average per invoice: $11,562.75

This suggests stronger account quality or pricing power under his management.

### Customer Profitability

#### Top Customer: PageWave

$5.63M+ in sales

232,000+ units sold

67% gross margin

PageWave is both high-volume and high-margin — a strategic priority account.

### Business Recommendations

Promote high-margin products like Meat to increase portfolio profitability.

Optimize pricing strategy for Snacks to improve margins.

Prioritize retention and upselling for high-value customers like PageWave.

Expand European presence in Germany, Spain, and Nordic regions.

Replicate best practices from high-performing managers.

### Next Steps & Limitations
#### Limitations

Analysis limited to 2012–2014 YTD

No cost breakdown beyond gross margin

No predictive forecasting model implemented

#### Next Steps

If given more time, I would:

Build a sales forecasting model

Perform contribution margin analysis

Add inventory and supply chain metrics

Develop customer lifetime value (CLV) modeling

Implement advanced segmentation clustering

### Project Outcome

This project demonstrates the ability to:

Design relational data models in Power BI

Build executive-level dashboards

Translate complex sales data into strategic insights

Balance revenue growth and margin optimization

Communicate insights clearly for decision-makers
