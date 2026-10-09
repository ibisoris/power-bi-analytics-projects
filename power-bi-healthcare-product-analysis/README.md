# Healthcare Product Analysis

[Back to the Power BI Analytics Projects portfolio](../README.md)

## Overview

This repository contains a Power BI project for analyzing the healthcare product pricing data of TechnoEdge. The dataset includes information on product ID, vendor, brand name, unit price, dosage form, and manufacturer location, among other parameters.

**Portfolio Author and Maintainer:** Ibinabo Orifama · [ibisoris2026@gmail.com](mailto:ibisoris2026@gmail.com)

## Business Problem and Objectives

Product and procurement teams need to compare healthcare product pricing, vendor offerings, and logistics costs.

### Documented objectives

1. **Pricing Trends:** Analyze pricing trends across sub-categories and product groups.
2. **Top Vendors and Manufacturers:** Identify top vendors and manufacturers by sales.
3. **Top-Selling Molecules/Test Types:** Determine top-selling molecules/test types and their prices.
4. **Dosage Form Comparison:** Compare prices of different dosage forms of the same product.
5. **Impact of Weight:** Analyze the impact of weight on shipping and insurance costs.
6. **Discount Effectiveness:** Evaluate the effectiveness of discounts on sales.
7. **Geographic Pricing Trends:** Identify geographic trends in pricing.
8. **Sales and Packaging:** Analyze the relationship between sales and packaging.

These are the original analysis objectives. An objective is not evidence that a feature or finding was completed. Verified report components and limitations are listed below.

## Dataset and Available Sources

The problem statement describes product ID, vendor, brand name, unit price, dosage form, and manufacturer location, with additional pricing, weight, shipping, insurance, discount, and packaging fields discussed in the objectives.

The available sources for reviewing this project are the saved [Power BI report](./PowerBI_Healthcare_Analysis.pbix), [project brief](./Problem_Statement.pdf), [PDF dashboard export](./Healthcare_Dashboard.pdf), and [dashboard screenshot](./Product_report.png). No standalone CSV or Excel source dataset is included in this folder. The saved report contains a data-model payload; the original input files, connection settings, source provenance, record count, currency units, and refresh requirements have not been independently verified.

## KPIs and Metrics

Shipping cost, insurance cost, unit price, pack price, product counts by sub-category/location, molecular-type counts by vendor, and pack-price comparisons by brand.

The screenshot shows metrics in its saved filter context. Metric labels do not, by themselves, verify aggregation rules, population definitions, or calculations.

## Tools and Technologies

- **Power BI Desktop:** The included `.pbix` file contains the report layout and data model.
- **Data visualization:** Bar charts, Cards, Clustered column charts, Donut charts, Funnel charts, Pie charts, Scrolling-text custom visual, Slicers.
- **Report tooltips:** A dedicated tooltip page is present in the report layout.

Tools mentioned only as prerequisites are not treated as verified implementations. This review does not establish Excel, Power Pivot, Power View, or Power BI Service use.

## DAX Measures and Analytical Techniques

No explicit named model-measure references were found in the inspected report layout. Visuals use column references and aggregations; this does not establish that the model contains no DAX measures. No independently verified DAX formulas are available, so no example expressions are presented as implemented code.

**Analytical techniques and verified report components:** Power BI Desktop; location slicer, cards, vendor column chart, sub-category pie chart, location bar chart, brand funnel, scrolling-text custom visual, action buttons, and a tooltip page confirmed in the report layout.

### Report pages

| Page | Role |
| --- | --- |
| Page 1 | Report page |
| Tooltip | Report tooltip |

## Dashboard Screenshot

![Saved Healthcare Product Analysis dashboard](./Product_report.png)

Existing project screenshot, shown without alteration. [View the PDF dashboard export](./Healthcare_Dashboard.pdf) for another saved view.

## Findings and Business Recommendations

### Observed findings

The saved chart shows Pediatric as the largest labeled product sub-category at 133, while Chennai leads the displayed location counts. Generic leads the displayed pack-price comparison at approximately 49K. These support assortment and pricing review, but do not establish vendor sales leadership or discount effectiveness.

These observations describe the saved screenshot and are not live, audited, or causal results.

### Recommended follow-up

- Investigate Pediatric product coverage and Chennai's displayed product concentration to support assortment and supply planning.
- Compare Generic pack prices on a consistent dosage, pack-size, and quantity basis before drawing pricing conclusions; vendor molecular-type counts should not be treated as sales.

Recommendations are proposed next steps based on the displayed patterns and documented objectives; they are not claims of implemented changes or proven business impact.

## Open and Explore the Report

1. Download [PowerBI_Healthcare_Analysis.pbix](./PowerBI_Healthcare_Analysis.pbix) to your Windows computer and open it in Power BI Desktop.
2. Start with the saved report view, then explore the report pages listed above. Tooltip pages support hover detail and may be hidden from normal navigation.
3. Use the available slicers and navigation controls to compare segments or periods. Record the filter context when interpreting values and reset selections before comparing totals.
4. Review [the project brief](./Problem_Statement.pdf) to compare the intended objectives with the available visuals. Hover over charts where tooltips are configured.
5. Inspect visual field aggregations, any model measures, and relationships in Power BI Desktop before relying on reported totals.
6. If refreshing requires unavailable files, credentials, or connections, the original data sources must be obtained and configured first. The screenshot and PDF remain available for reviewing the saved output.

No verified public interactive-report URL is included in this project. Opening the local file does not require publishing it.

## Project Files

| File | Purpose |
| --- | --- |
| [PowerBI_Healthcare_Analysis.pbix](./PowerBI_Healthcare_Analysis.pbix) | Power BI report |
| [Problem_Statement.pdf](./Problem_Statement.pdf) | Original problem statement / project overview |
| [Healthcare_Dashboard.pdf](./Healthcare_Dashboard.pdf) | Saved dashboard PDF |
| [Product_report.png](./Product_report.png) | Existing dashboard screenshot |
| [README.md](./README.md) | Project documentation |

## Limitations and Missing Information

- Original input datasets, data provenance, record counts, refresh configuration, and currency definitions are not verified.
- Full DAX expressions, model relationships, transformation steps, and independent metric validation are not available in this documentation review.
- Cost and price card aggregation definitions are not verified. Sales rankings, discount effectiveness, and packaging/weight effects are documented objectives rather than proven outcomes.
- Licensing and redistribution terms remain incompletely documented, as explained below.

## Original Technical Documentation

The original prerequisites are retained for reference. They are historical project guidance, not a verified current compatibility list or proof of tool usage.

<details>
<summary>Original technical prerequisites</summary>

### Skill Prerequisites
- Solid understanding of data visualization and analysis concepts.
- Experience with data modeling and ETL processes.
- Proficiency in Power BI tools such as Power Query, Power Pivot, and Power View.
- Ability to collaborate effectively with stakeholders.

### System Requirements
- **Operating System:** Windows 10, Windows 8.1, Windows 8, or Windows 7 Service Pack 1 (32-bit and 64-bit).
- **Processor:** 1 GHz or faster x86 or x64-bit processor.
- **RAM:** 1 GB (32-bit) or 2 GB (64-bit) RAM.
- **Hard Disk Space:** 1 GB available disk space.
- **Display:** 1024 x 768 resolution.

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
