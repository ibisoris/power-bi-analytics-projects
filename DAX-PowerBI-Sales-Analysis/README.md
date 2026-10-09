# DAX Sales Analysis

[Back to the Power BI Analytics Projects portfolio](../README.md)

## Overview

This repository contains a Power BI DAX project for analyzing the sales data of TechnoEdge from 2022 to 2024. The dataset includes various tables such as Calendar, Customers, Product Categories, Product Sub-Categories, Products, Returns, Territories, and Sales. The goal is to gain insights and improve business operations by analyzing sales trends, customer behavior, product performance, and returns.

**Portfolio Author and Maintainer:** Ibinabo Orifama · [ibisoris2026@gmail.com](mailto:ibisoris2026@gmail.com)

## Business Problem and Objectives

Commercial teams need to compare sales and returns against goals while understanding which products, customer groups, and territories contribute to performance.

### Documented objectives

1. **Sales Data Analysis:** Analyze sales data for TechnoEdge across different regions, countries, and product categories.
2. **Trend Identification:** Identify trends and patterns in sales data to improve business performance.
3. **Customer Behavior:** Understand customer behavior and preferences based on buying patterns.
4. **Product Performance:** Identify high-performing and underperforming products and product categories.
5. **Sales Metrics Monitoring:** Monitor key sales metrics such as sales, profit, and profit margin to identify areas for improvement.
6. **Reporting and Visualization:** Create reports and visualizations to help stakeholders make informed decisions about sales and marketing strategies.

These are the original analysis objectives. An objective is not evidence that a feature or finding was completed. Verified report components and limitations are listed below.

## Dataset and Available Sources

The problem statement describes Calendar, Customers, Product Categories, Product Sub-Categories, Products, Returns, Territories, and Sales tables covering 2022–2024.

The available sources for reviewing this project are the saved [Power BI report](./DAX_Sales_Analysis_Project.pbix), [project brief](./Problem%20Statement.pdf), [PDF dashboard export](./Sales_Analysis_Dashboard.pdf), and [dashboard screenshot](./Sales_report.png). No standalone CSV or Excel source dataset is included in this folder. The saved report contains a data-model payload; the original input files, connection settings, source provenance, record count, currency units, and refresh requirements have not been independently verified.

## KPIs and Metrics

Revenue, total orders, return quantity, goal comparisons, profit by country, and orders by age group and income level.

The screenshot shows metrics in its saved filter context. Metric labels do not, by themselves, verify aggregation rules, population definitions, or calculations.

## Tools and Technologies

- **Power BI Desktop:** The included `.pbix` file contains the report layout and data model.
- **DAX / model measures:** Named measure references are present in the report layout; formulas are not independently verified.
- **Data visualization:** Cards, Clustered bar charts, Gauges, KPI visuals, Matrices, Pie charts, Slicers.

Tools mentioned only as prerequisites are not treated as verified implementations. This review does not establish Excel, Power Pivot, Power View, or Power BI Service use.

## DAX Measures and Analytical Techniques

The following **measure names are verified as references in the saved report layout**. Their DAX expressions are not available in the inspected documentation or layout, so no formulas are reproduced or reconstructed. Names indicate their intended use; calculation semantics still require inspection in Power BI Desktop.

- `2022`
- `2023`
- `2024`
- `Target Return`
- `Total Order`
- `Total Revenue`
- `Total order-NO`
- `Total profit`
- `Total return No`
- `previous month Order`
- `previous month return`
- `previous month revenue`

**Analytical techniques and verified report components:** Power BI Desktop; DAX-focused analysis documented in the project materials; date-range slicer, KPI visuals, gauge, cards, matrix, pie chart, and clustered bar chart confirmed in the report layout.

### Report pages

| Page | Role |
| --- | --- |
| Home page | Report page |
| Summary Page | Report page |

## Dashboard Screenshot

![Saved DAX Sales Analysis dashboard](./Sales_report.png)

Existing project screenshot, shown without alteration. [View the PDF dashboard export](./Sales_Analysis_Dashboard.pdf) for another saved view.

## Findings and Business Recommendations

### Observed findings

The saved dashboard names Water Bottle - 30 oz. as the top-selling product and Mountain-200 Black, 46 as the top product by profit. The United States has the largest displayed country profit. Product rankings therefore differ depending on the metric. The order KPI and segmented order counts appear inconsistent, so they should be reconciled before drawing conclusions about total order volume.

These observations describe the saved screenshot and are not live, audited, or causal results.

### Recommended follow-up

- Evaluate high-volume and high-profit products separately when planning inventory and promotions; the displayed leaders differ by metric.
- Reconcile the total-order KPI with age/income breakdowns and confirm target definitions before acting on order or return goal variances.

Recommendations are proposed next steps based on the displayed patterns and documented objectives; they are not claims of implemented changes or proven business impact.

## Open and Explore the Report

1. Download [DAX_Sales_Analysis_Project.pbix](./DAX_Sales_Analysis_Project.pbix) to your Windows computer and open it in Power BI Desktop.
2. Start with the saved report view, then explore the report pages listed above. Tooltip pages support hover detail and may be hidden from normal navigation.
3. Use the available slicers and navigation controls to compare segments or periods. Record the filter context when interpreting values and reset selections before comparing totals.
4. Review [the project brief](./Problem%20Statement.pdf) to compare the intended objectives with the available visuals. Hover over charts where tooltips are configured.
5. Select the referenced measures in Power BI Desktop to inspect their actual expressions and formatting; check relationships and date/filter context before relying on their results.
6. If refreshing requires unavailable files, credentials, or connections, the original data sources must be obtained and configured first. The screenshot and PDF remain available for reviewing the saved output.

No verified public interactive-report URL is included in this project. Opening the local file does not require publishing it.

## Project Files

| File | Purpose |
| --- | --- |
| [DAX_Sales_Analysis_Project.pbix](./DAX_Sales_Analysis_Project.pbix) | Power BI report |
| [Problem Statement.pdf](./Problem%20Statement.pdf) | Original problem statement / project overview |
| [Sales_Analysis_Dashboard.pdf](./Sales_Analysis_Dashboard.pdf) | Saved dashboard PDF |
| [Sales_report.png](./Sales_report.png) | Existing dashboard screenshot |
| [README.md](./README.md) | Project documentation |

## Limitations and Missing Information

- Original input datasets, data provenance, record counts, refresh configuration, and currency definitions are not verified.
- Full DAX expressions, model relationships, transformation steps, and independent metric validation are not available in this documentation review.
- Order KPI and segmented counts need reconciliation. Goal definitions and return aggregation are not validated.
- Licensing and redistribution terms remain incompletely documented, as explained below.

## Original Technical Documentation

The original prerequisites are retained for reference. They are historical project guidance, not a verified current compatibility list or proof of tool usage.

<details>
<summary>Original technical prerequisites</summary>

### Skill Prerequisites
- Access to Power BI.
- Understanding of data modeling concepts (relationships, cardinality, normalization).
- Familiarity with Excel functions and formulas.
- Basic knowledge of programming concepts (variables, loops, conditional statements).
- Continuous practice and experience with DAX and data analysis.

### System Requirements
- **Operating System:** Windows 10 or later, Windows Server 2016 or later, or Windows Server 2012 R2.
- **Processor:** A 64-bit processor.
- **Memory:** Minimum of 8GB RAM recommended.
- **Storage:** Sufficient storage space for data and Power BI application.
- **Graphics Card:** At least 1GB of memory recommended.
- **Internet Connection:** Reliable internet connection for accessing and sharing data.
- **Power BI Desktop:** Download and install Power BI Desktop.
- **Power BI Service:** Sign up for a Power BI service account to publish and share reports and dashboards.

</details>

## Attribution and Licensing

Original project materials are credited to **Dagogo Orifama**, from [Complete Power BI Projects](https://github.com/DagogoOrifama/Complete-Power-BI-Projects). **Ibinabo Orifama** maintains this portfolio and its documentation; this does not claim original development of the report.

**Existing license notice (preserved):**

> This project is licensed under the MIT License.

**Unresolved terms:** Neither this local collection nor the verified upstream root includes a standalone license file. GitHub repository metadata reports no detected license, despite the project README's MIT statement. This documentation preserves the statement without adding a new license or resolving the missing license text. Confirm the intended license, applicable copyright/permission notices, and dataset or third-party asset rights with the original author before reuse or redistribution. Do not assume unrestricted redistribution from the README statement alone. See the [portfolio licensing review](../README.md#attribution-and-licensing).

**Republication permission:** See the [permission and public-sharing record](../REPUBLISHING_PERMISSION.md). The author has confirmed authorship and that customer/employee data are synthetic or cleared for public sharing. These are author declarations; this portfolio does not claim a repository-wide MIT license.

## Contact and Contributions

**Portfolio Author and Maintainer:** Ibinabo Orifama  
**Email:** [ibisoris2026@gmail.com](mailto:ibisoris2026@gmail.com)

The original documentation welcomes improvements and contributions. For documentation corrections or portfolio questions, contact the maintainer.

[Return to the main portfolio](../README.md)
