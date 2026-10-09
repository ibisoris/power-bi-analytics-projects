# Financial Analysis Using DAX

[Back to the Power BI Analytics Projects portfolio](../README.md)

## Overview

This repository contains a Power BI DAX project for analyzing the financial data of TechnoEdge. The project provides an interactive snapshot of finance data, including sales, profit, and transaction details. Visuals such as bar charts and tables display key metrics by segments, products, and countries, allowing for easy analysis and decision-making.

**Portfolio Author and Maintainer:** Ibinabo Orifama · [ibisoris2026@gmail.com](mailto:ibisoris2026@gmail.com)

## Business Problem and Objectives

Decision-makers need to connect financial performance with transaction activity, payment methods, and sales channels.

### Documented objectives

1. **Sales Analysis:** Interactive report for sales performance by segment, country, product, and discount band with line charts and filters.
2. **Transaction Analysis:** Report for transaction trends by date, quantity, payment method, and channel with line charts and slicers.
3. **Profitability Analysis:** Report for profitability metrics with bullet charts, comparing actual vs target profit margins.
4. **Sales Channel Analysis:** Report for sales performance by online/offline channels with stacked area charts and drill-through.
5. **Customer Analysis:** Report for customer demographics, payment methods, and purchasing patterns with pie charts and filters.
6. **Financial Performance Analysis:** Report for financial metrics by month, quarter, and year with line charts, KPIs, and interactive features.

These are the original analysis objectives. An objective is not evidence that a feature or finding was completed. Verified report components and limitations are listed below.

## Dataset and Available Sources

The project documentation describes financial sales, profit, and transactions, with segment, product, country, discount band, date, quantity, payment method, and channel dimensions.

The available sources for reviewing this project are the saved [Power BI report](./Financial_Analysis_Report.pbix), [project brief](./Problem_Statement.pdf), [PDF dashboard export](./Financial_Analysis_Dashboard.pdf), and [dashboard screenshot](./Financial_Report.png). No standalone CSV or Excel source dataset is included in this folder. The saved report contains a data-model payload; the original input files, connection settings, source provenance, record count, currency units, and refresh requirements have not been independently verified.

## KPIs and Metrics

The saved report displays Sales, Monthly Sales, Last 30 Days Sale, and Quantity cards, plus segment/product sales and channel quantities. Profit margin and target comparisons are documented objectives.

The screenshot shows metrics in its saved filter context. Metric labels do not, by themselves, verify aggregation rules, population definitions, or calculations.

## Tools and Technologies

- **Power BI Desktop:** The included `.pbix` file contains the report layout and data model.
- **DAX / model measures:** Named measure references are present in the report layout; formulas are not independently verified.
- **Data visualization:** Area charts, Bar charts, Cards, Clustered column charts, Donut charts, Pie charts, Slicers.
- **Report tooltips:** A dedicated tooltip page is present in the report layout.

Tools mentioned only as prerequisites are not treated as verified implementations. This review does not establish Excel, Power Pivot, Power View, or Power BI Service use.

## DAX Measures and Analytical Techniques

The following **measure names are verified as references in the saved report layout**. Their DAX expressions are not available in the inspected documentation or layout, so no formulas are reproduced or reconstructed. Names indicate their intended use; calculation semantics still require inspection in Power BI Desktop.

- `MonthlySales`
- `SalesLast30Days`
- `Total Quantity Sold`
- `Total Sales`

**Analytical techniques and verified report components:** Power BI Desktop; DAX-focused analysis documented in the project materials; country slicer, cards, area/bar/column charts, pie/donut charts, action buttons, and a tooltip page confirmed in the report layout.

### Report pages

| Page | Role |
| --- | --- |
| Summary | Report page |
| Report page | Report page |
| Tooltip | Report tooltip |

## Dashboard Screenshot

![Saved Financial Analysis Using DAX dashboard](./Financial_Report.png)

Existing project screenshot, shown without alteration. [View the PDF dashboard export](./Financial_Analysis_Dashboard.pdf) for another saved view.

## Findings and Business Recommendations

### Observed findings

Government leads the displayed segment sales at approximately 53M, and Paseo leads product sales at approximately 33M. In-store has the largest displayed channel quantity at 729. The three sales cards show the same value in the saved screenshot; their time filters and measure definitions need validation before interpreting monthly or rolling-period performance.

These observations describe the saved screenshot and are not live, audited, or causal results.

### Recommended follow-up

- Validate MonthlySales and SalesLast30Days against the calendar and filter context because their saved values match Total Sales.
- Compare Government/Paseo performance and in-store quantities with profitability and channel costs before changing budgets or distribution.

Recommendations are proposed next steps based on the displayed patterns and documented objectives; they are not claims of implemented changes or proven business impact.

## Open and Explore the Report

1. Download [Financial_Analysis_Report.pbix](./Financial_Analysis_Report.pbix) to your Windows computer and open it in Power BI Desktop.
2. Start with the saved report view, then explore the report pages listed above. Tooltip pages support hover detail and may be hidden from normal navigation.
3. Use the available slicers and navigation controls to compare segments or periods. Record the filter context when interpreting values and reset selections before comparing totals.
4. Review [the project brief](./Problem_Statement.pdf) to compare the intended objectives with the available visuals. Hover over charts where tooltips are configured.
5. Select the referenced measures in Power BI Desktop to inspect their actual expressions and formatting; check relationships and date/filter context before relying on their results.
6. If refreshing requires unavailable files, credentials, or connections, the original data sources must be obtained and configured first. The screenshot and PDF remain available for reviewing the saved output.

No verified public interactive-report URL is included in this project. Opening the local file does not require publishing it.

## Project Files

| File | Purpose |
| --- | --- |
| [Financial_Analysis_Report.pbix](./Financial_Analysis_Report.pbix) | Power BI report |
| [Problem_Statement.pdf](./Problem_Statement.pdf) | Original problem statement / project overview |
| [Financial_Analysis_Dashboard.pdf](./Financial_Analysis_Dashboard.pdf) | Saved dashboard PDF |
| [Financial_Report.png](./Financial_Report.png) | Existing dashboard screenshot |
| [README.md](./README.md) | Project documentation |

## Limitations and Missing Information

- Original input datasets, data provenance, record counts, refresh configuration, and currency definitions are not verified.
- Full DAX expressions, model relationships, transformation steps, and independent metric validation are not available in this documentation review.
- Period-specific sales measures need validation. Bullet charts, target-profit comparisons, and drill-through appear in the objectives but are not confirmed in the inspected layout.
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

**Republication permission:** See the [permission and public-sharing record](../REPUBLISHING_PERMISSION.md). Permission scope and clearance are pending confirmation; this portfolio does not claim a repository-wide MIT license.

## Contact and Contributions

**Portfolio Author and Maintainer:** Ibinabo Orifama  
**Email:** [ibisoris2026@gmail.com](mailto:ibisoris2026@gmail.com)

The original documentation welcomes improvements and contributions. For documentation corrections or portfolio questions, contact the maintainer.

[Return to the main portfolio](../README.md)
