# Global Superstore Business Intelligence Dashboard

### Interactive Sales, Profitability, Customer & Operations Analytics Using Power BI

## Project Overview

The Global Superstore Business Intelligence Dashboard is an interactive
data analytics project developed using Microsoft Power BI to analyse
sales performance, product profitability, customer behaviour, market
performance, and shipping operations.

The project uses the Global Superstore dataset to transform transactional
data into structured visual reports that support business performance
monitoring and data-driven decision-making.

The dashboard consists of four analytical pages, each designed to address
a different area of business performance. It combines key performance
indicators (KPIs), trend analysis, comparative visualisations, and
detailed matrices to help users explore business performance across
different dimensions.

## Business Problem

Businesses generate large volumes of transactional data through sales,
customer orders, product categories, regional markets, and shipping
activities. However, raw data alone does not provide a clear understanding
of business performance.

Decision-makers need to identify:

- Which product categories generate the highest sales?
- How does profitability vary across products and regions?
- Are higher discounts associated with weaker profitability?
- Which customers contribute the most revenue?
- How does sales performance differ across markets?
- Which shipping methods have higher costs or longer delays?

This project addresses these questions through an interactive Power BI
dashboard that presents business metrics in an accessible visual format.

## Project Objectives

- Analyse overall sales and profitability.
- Monitor key business performance indicators.
- Compare sales contributions across product categories.
- Investigate the relationship between discounts and profit.
- Identify high-value customers and regional sales patterns.
- Evaluate shipping costs, delivery delays, and order priorities.
- Provide interactive reporting to support business analysis.

## Tools and Technologies

| Tool / Technology | Purpose |
|---|---|
| Microsoft Power BI | Dashboard development and data visualisation |
| DAX | Business measures and KPI calculations |
| Global Superstore Dataset | Transactional data source |
| Interactive Slicers | Filtering and data exploration |
| Data Visualisation | Communicating business trends and comparisons |
| Business Intelligence | Performance monitoring and reporting |

Note: Include only the tools and techniques actually used in the project.

## Dashboard Architecture

The report is organised into four analytical pages.

### 1. Executive Overview

**Objective:** Provide a high-level summary of business performance.

Key performance indicators include:

- Total Sales
- Total Profit
- Profit Margin
- Total Orders
- Total Customers
- Average Order Value

Visualisations:

- Sales and Profit Trend
- Sales Contribution by Category
- Sales by Market

Business questions:

- What is the overall sales performance?
- How does profit change over time?
- Which product categories contribute the most revenue?
- Which markets generate the highest sales?

### 2. Product and Profitability Analysis

**Objective:** Evaluate product performance and investigate profitability.

Visualisations:

- Average Discount versus Total Profit Scatter Chart
- Total Sales by Category
- Top Products by Sales
- Profit Margin Matrix by Region and Category

Business questions:

- Which products generate the highest sales?
- How does profitability vary across product categories?
- Are larger discounts associated with lower profits?
- Which regions and categories have weaker profit margins?

Analytical value:

This page supports product-level performance comparisons and helps
identify areas that may require further investigation into discounting,
pricing, and profitability.

### 3. Customer and Market Analysis

**Objective:** Understand customer contributions and market performance.

Visualisations:

- Top 10 Customers by Sales
- Region and Category Sales Matrix
- Customer and Market Performance Table
- Sales by Customer Segment

Business questions:

- Which customers contribute the most revenue?
- How does sales performance differ across markets?
- Which regions perform well across product categories?
- How are sales distributed among customer segments?

Analytical value:

This page supports customer performance monitoring, regional comparisons,
and the identification of opportunities for targeted business strategies.

### 4. Shipping and Operations Analysis

**Objective:** Evaluate shipping performance and operational efficiency.

Visualisations:

- Total Orders by Order Priority
- Shipping Cost versus Sales by Ship Mode
- Shipping Delay by Market
- Average Shipping Delay by Ship Mode

Business questions:

- How are orders distributed across priority levels?
- How do shipping costs compare across shipping methods?
- Which markets experience longer shipping delays?
- How does delivery performance vary by ship mode?

Analytical value:

This page supports the investigation of shipping efficiency, operational
costs, and potential delivery performance improvements.

## Key Performance Indicators

The dashboard includes the following KPIs:

| KPI | Business Purpose |
|---|---|
| Total Sales | Measures overall revenue generated |
| Total Profit | Measures the profit generated by transactions |
| Profit Margin | Evaluates profit relative to sales |
| Total Orders | Measures order volume |
| Total Customers | Indicates the number of distinct customers |
| Average Order Value | Measures average sales value per order |
| Average Shipping Delay | Evaluates delivery timeliness |
| Shipping Cost % of Sales | Measures shipping cost relative to sales |

The interpretation of each KPI depends on its underlying calculation,
aggregation level, and data definitions.

## Interactive Features

The dashboard includes slicers for:

- Year
- Product Category
- Customer Segment
- Market

These filters allow users to explore the report from different business
perspectives and compare performance across selected dimensions.

The report also uses page navigation to organise the four analytical
sections into a single Power BI experience.

## Analytical Approach

The project follows a structured reporting workflow:

1. **Data Source:** Use the Global Superstore transactional dataset.
2. **Data Preparation:** Prepare the source data for analysis.
3. **Metric Development:** Define business measures and KPIs.
4. **Visualisation:** Select charts and tables appropriate to each
   business question.
5. **Dashboard Development:** Organise the visualisations into four
   analytical pages.
6. **Interactive Analysis:** Add slicers and report navigation.
7. **Validation:** Review metric calculations, filters, totals, and
   visual behaviour before drawing business conclusions.

The documentation describes the intended analytical workflow.
Specific data-cleaning and modelling techniques should be documented
according to the steps actually performed.

## Business Value

The dashboard provides a consolidated view of business performance
through sales, profitability, customer, market, and shipping metrics.

Potential business applications include:

- Monitoring sales and profit trends.
- Comparing category and regional performance.
- Investigating products with weak profitability.
- Understanding customer revenue contributions.
- Evaluating shipping costs and delivery delays.
- Supporting more informed operational decisions.

These are potential applications of the analysis rather than claims of
measured business improvements.

## Repository Structure

```text
global-superstore-powerbi-dashboard/
│
├── README.md
│
├── PowerBI/
│   └── Global_Superstore_Business_Intelligence.pbix
│
├── Screenshots/
│   ├── 01_Executive_Overview.png
│   ├── 02_Product_Profitability.png
│   ├── 03_Customer_Market.png
│   └── 04_Shipping_Operations.png
│
└── Dataset/
    └── README.md
```

The repository structure represents the planned organisation of the
project files. Add each file after uploading it to GitHub.

## How to View the Project

### Option 1: Power BI Desktop

1. Download the `.pbix` file from the repository.
2. Open the file using Microsoft Power BI Desktop.
3. Navigate through the four report pages.
4. Use the available slicers to explore the data.
5. Review the KPIs, charts, and analytical tables.

### Option 2: Dashboard Screenshots

Open the Screenshots folder to view the dashboard pages directly on
GitHub without downloading the Power BI file.

## Limitations and Considerations

- Findings depend on the accuracy and completeness of the source dataset.
- Observed relationships do not necessarily establish causation.
- Discount and profitability patterns require further investigation
  before making pricing decisions.
- Shipping delay metrics depend on the definitions and date fields used.
- KPI results should be validated against the underlying data model.
- The dashboard represents historical data and does not automatically
  predict future business performance.

## Future Enhancements

Potential future improvements include:

- Adding more detailed year-over-year performance comparisons.
- Developing drill-through pages for product and customer analysis.
- Improving tooltip information for individual visualisations.
- Adding further profitability and operational efficiency measures.
- Integrating SQL-based data preparation.
- Automating data refresh where an appropriate data source is available.

These enhancements are potential extensions and are not represented
as completed features.

## Project Deliverables

- Four-page interactive Power BI dashboard.
- Executive-level KPI reporting.
- Product and profitability analysis.
- Customer and market performance analysis.
- Shipping and operations analysis.
- Project documentation and dashboard screenshots.

## Author

**Imran**

Aspiring Data Analyst | Business Intelligence | Power BI | SQL | Python

This project demonstrates practical work in dashboard development,
business reporting, KPI visualisation, and exploratory data analysis.

## Disclaimer

This project is intended for educational and portfolio purposes.
Business observations should be interpreted in the context of the
source dataset and validated calculations.

The project does not claim verified financial gains or operational
improvements for an actual business.
