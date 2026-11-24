# Superstore – Strategic, tactical and operational BI Dashboard (Power BI)
A four-page Power BI report built for a fictional retail company,
*Superstore – Office & Corporate Supplies*. The report is structured around
the **information pyramid**: each page is designed for a different recipient,
with the right data, at the right level of detail, in the right format.

## The assignment
Create an enterprise BI application based on open data, with reports for
three recipients (one per level of the information pyramid) and a
summary page that combines the best parts of each.

## Data
[Sample Superstore](https://www.kaggle.com/datasets/naveenkumar20bps1137/sample-superstore)
from Kaggle (orders, sales, profit, products and locations in the US, 2014–2017).
License: not specified by the uploader on Kaggle. The raw data and the
.pbix file are therefore not included in this repository.

## The story in the dashboard
Superstore's overall profit is growing, but the results differ a lot
between regions. The **Central** region has the lowest profit margin,
and drilling down points to **Texas**. Several Texas cities have high
sales but negative profit, including Houston, San Antonio and Dallas.
At product level, many items are sold with a negative margin, which
suggests that pricing should be reviewed.

## Pages

### 1. Strategic – for senior management
Long time horizon, aggregated data and KPIs (profit, profit margin, sales)
with comparison to the previous period. A trend line shows profit over time,
a bar chart highlights the top and bottom cities, and a heatmap shows profit
margin by region and year with drill-down to state level.

![Strategic page](images/strategic.png)

### 2. Tactical – for regional and middle managers
Breaks the big picture down to the region (Texas) to show where action is
needed. Sales are high but profit is negative. Bar charts with buttons let
the user switch between sales/profit and profit margin, and a heatmap shows
profit margin per city and quarter.

![Tactical page - Sales & Profit](images/tactical1.png)
![Tactical page - Profit Margin](images/tactical2.png)

### 3. Operational – for the warehouse manager
Granular data for acting "here and now". The detailed product table makes it easy to find products with
a negative margin, which are highlighted in red.

![Operational page](images/operational.png)

### 4. Summary – for everyone in the company
Combines the most important parts of the three levels in one dashboard, with
KPIs first and details further down.

![Summary page](images/summary.png)

## Design choices
- **Visual hierarchy:** KPIs at the top, details further down.
- **Consistency:** Same logo, menu, colours and layout on every page, which
  lowers cognitive load.
- **Minimalism:** No decorative elements, few colours, and accent colour only
  where attention is needed.
- **User control and flexibility:** Filters, drill-down and toggle buttons.
- **Chart choice:** Bar charts for comparing categories, line chart for
  trends, heatmaps instead of dense tables, and tables for detailed data.
- **UX principles:** Gestalt principles and Norman's design principles guided the layout, visual grouping and interaction design.

## Tools
Power BI, DAX, Power Query

## Contributors
Group project at Nackademin (BI Analyst programme). All team members
worked on all parts of the project.
