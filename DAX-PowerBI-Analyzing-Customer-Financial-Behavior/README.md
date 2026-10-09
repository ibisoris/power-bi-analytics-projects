# DAX Customer Financial Behavior

[Back to the Power BI Analytics Projects portfolio](../README.md)

## Overview

This repository contains a Power BI DAX project for analyzing the financial behavior of TechnoEdge's customers. The dataset includes customer information (name, age, gender), loan details (amount, status), and date-related information (month, quarter, fiscal year). The goal is to gain insights into customers, loans, and trends for informed decision-making and strategic planning.

**Portfolio Author and Maintainer:** Ibinabo Orifama · [ibisoris2026@gmail.com](mailto:ibisoris2026@gmail.com)

## Business Problem and Objectives

Lending teams need to monitor customer profiles, borrowing patterns, debt, and credit balances over time.

### Documented objectives

1. **Loan Status Distribution:** Analyze loan status distribution using a pie chart.
2. **Income Comparison:** Compare average annual income by gender using a bar chart.
3. **Debt Trend Visualization:** Visualize the trend of monthly debt over time using an area chart.
4. **Credit Balance Calculation:** Calculate the total current credit balance and display it in a card visual.
5. **Quarterly Data Filtering:** Filter data by calendar quarter using a slicer for more focused analysis.
6. **Bookmark Navigator:** Create a bookmark navigator for easy navigation between different time periods in the calendar.

These are the original analysis objectives. An objective is not evidence that a feature or finding was completed. Verified report components and limitations are listed below.

## Dataset and Available Sources

The problem statement describes Bank Detail for customer/loan information, Customer Detail for demographics, and Calendar for month, quarter, and fiscal-year information.

The available sources for reviewing this project are the saved [Power BI report](./DAX_Customer_Financial_Analysis.pbix), [project brief](./Problem_Statement.pdf), [PDF dashboard export](./Customer_Financial_Behavior_Dashboard.pdf), and [dashboard screenshot](./Dashboard.png). No standalone CSV or Excel source dataset is included in this folder. The saved report contains a data-model payload; the original input files, connection settings, source provenance, record count, currency units, and refresh requirements have not been independently verified.

## KPIs and Metrics

Customer count, average income, monthly debt, male and female counts, current balance, average age, and loan amount by state.

The screenshot shows metrics in its saved filter context. Metric labels do not, by themselves, verify aggregation rules, population definitions, or calculations.

## Tools and Technologies

- **Power BI Desktop:** The included `.pbix` file contains the report layout and data model.
- **DAX / model measures:** Named measure references are present in the report layout; formulas are not independently verified.
- **Data visualization:** Area charts, Bookmark navigation, Cards, Clustered bar charts, Line charts, Pie charts, Slicers.
- **Report tooltips:** A dedicated tooltip page is present in the report layout.

Tools mentioned only as prerequisites are not treated as verified implementations. This review does not establish Excel, Power Pivot, Power View, or Power BI Service use.

## DAX Measures and Analytical Techniques

The following **measure names are verified as references in the saved report layout**. Their DAX expressions are not available in the inspected documentation or layout, so no formulas are reproduced or reconstructed. Names indicate their intended use; calculation semantics still require inspection in Power BI Desktop.

- `Average Age`
- `Average Annual Income`
- `Average Monthly Debt`
- `Total Annual Income`
- `Total Current Credit Balance`
- `Total Customers`
- `Total Female Customers`
- `Total Loan Amount`
- `Total Loans`
- `Total Male Customers`

**Analytical techniques and verified report components:** Power BI Desktop; DAX-focused analysis documented in the project materials; year/quarter slicers, bookmark navigator, cards, area charts, pie/bar charts, action buttons, and line-chart tooltip page confirmed in the report layout.

### Report pages

| Page | Role |
| --- | --- |
| Summary | Report page |
| Report Page | Report page |
| Tooltip1 | Report tooltip |

## Dashboard Screenshot

![Saved DAX Customer Financial Behavior dashboard](./Dashboard.png)

Existing project screenshot, shown without alteration. [View the PDF dashboard export](./Customer_Financial_Behavior_Dashboard.pdf) for another saved view.

## Findings and Business Recommendations

### Observed findings

In the saved view, California has the largest displayed loan amount. The current-balance chart peaks in 2022 and falls in 2023. These patterns suggest areas for geographic exposure and balance-trend review, but do not demonstrate default risk or its causes.

These observations describe the saved screenshot and are not live, audited, or causal results.

### Recommended follow-up

- Review California's displayed loan concentration alongside validated loan status and borrower data before assessing exposure.
- Investigate the displayed fall in current balance after 2022 using consistent period filters and validated measures; the chart alone does not explain the decline.

Recommendations are proposed next steps based on the displayed patterns and documented objectives; they are not claims of implemented changes or proven business impact.

## Open and Explore the Report

1. Download [DAX_Customer_Financial_Analysis.pbix](./DAX_Customer_Financial_Analysis.pbix) to your Windows computer and open it in Power BI Desktop.
2. Start with the saved report view, then explore the report pages listed above. Tooltip pages support hover detail and may be hidden from normal navigation.
3. Use the available slicers and navigation controls to compare segments or periods. Record the filter context when interpreting values and reset selections before comparing totals.
4. Review [the project brief](./Problem_Statement.pdf) to compare the intended objectives with the available visuals. Hover over charts where tooltips are configured.
5. Select the referenced measures in Power BI Desktop to inspect their actual expressions and formatting; check relationships and date/filter context before relying on their results.
6. If refreshing requires unavailable files, credentials, or connections, the original data sources must be obtained and configured first. The screenshot and PDF remain available for reviewing the saved output.

No verified public interactive-report URL is included in this project. Opening the local file does not require publishing it.

## Project Files

| File | Purpose |
| --- | --- |
| [DAX_Customer_Financial_Analysis.pbix](./DAX_Customer_Financial_Analysis.pbix) | Power BI report |
| [Problem_Statement.pdf](./Problem_Statement.pdf) | Original problem statement / project overview |
| [Customer_Financial_Behavior_Dashboard.pdf](./Customer_Financial_Behavior_Dashboard.pdf) | Saved dashboard PDF |
| [Dashboard.png](./Dashboard.png) | Existing dashboard screenshot |
| [README.md](./README.md) | Project documentation |

## Limitations and Missing Information

- Original input datasets, data provenance, record counts, refresh configuration, and currency definitions are not verified.
- Full DAX expressions, model relationships, transformation steps, and independent metric validation are not available in this documentation review.
- Loan-status distribution and income-by-gender comparisons are documented objectives; their completion is not established by the saved screenshot. No default-risk finding is verified.
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
