\# 🚗 Automotive Sales \& Territory Analytics Dashboard



\[!\[Power BI](https://img.shields.io/badge/Power\_BI-F2C811?style=flat\&logo=powerbi\&logoColor=black)](https://powerbi.microsoft.com/)

\[!\[DAX](https://img.shields.io/badge/DAX-Data\_Analysis\_Expressions-00758F?style=flat)](https://learn.microsoft.com/en-us/dax/)

\[!\[Data Modeling](https://img.shields.io/badge/Schema-Star\_Schema-blue?style=flat)](#data-modeling--architecture)



An executive-level Power BI business intelligence solution engineered to evaluate regional sales performance, inventory turnover velocity, and pricing efficiency across 22,500 automotive transactions.



\---



\## 📌 Executive Summary



Dealership networks frequently experience uneven profitability despite consistent transaction counts across territories. This project benchmarks performance across four operational territories (\*\*North, South, East, West\*\*) to isolate pricing leakage and inventory holding bottlenecks.



\### Key Finding

While transaction volume in the \*\*East territory\*\* remained steady, gross revenue efficiency trailed the benchmark (\*\*North\*\*) by \*\*12%\*\*. Detailed diagnostic modeling revealed the deficit was driven by:

1\. \*\*Pricing Margin Erosion:\*\* East dealerships operated at an average discount rate of \*\*9.0%\*\*, compared to the disciplined \*\*5.0%\*\* baseline maintained in the North.

2\. \*\*Inventory Holding Bottlenecks:\*\* High-margin models—specifically \*\*Apex Truck\*\* (53 days) and \*\*Volt EV\*\* (48 days)—remained in stock over 40% longer than smaller fleet vehicles (17–27 days), generating excessive holding costs.



\---



\## 📊 Dashboard Preview



!\[Dashboard Overview](assets/dashboard\_overview.png)



\*Interactive features: Dynamic KPI cards, territory cross-filtering, multi-tier conditional formatting on inventory velocity, and benchmark variance tooltips.\*



\---



\## 🏗️ Data Modeling \& Architecture



The report is built on a high-performance \*\*Star Schema\*\* to optimize DAX query evaluation and visual interaction speeds.







💡 Business Recommendations

Implement Discount Governance: Enforce regional managerial approval thresholds for discounts exceeding 6.0% to eliminate margin leakage in underperforming territories.



Rebalance Inventory Distribution: Reallocate slow-moving truck inventory away from East dealerships to territories with faster turnover cycles to reduce days-to-sell holding costs.



Capitalize on Fast-Moving Units: Increase stock allocations for high-velocity categories such as Urban Hatch (18 days to sell) to maximize cash conversion cycles.



\---







\## 🛠️ How to Replicate



1. Clone this repository:

git clone\[https://github.com/](https://github.com/)<arnvke01>/automotive-sales-analytics.git



**2.Navigate to the /pbix directory and open Automotive\_Sales\_Analytics.pbix in Power BI Desktop.**



**3.If prompted to refresh data sources, update the file paths pointing to /data/Fact\_Sales.csv.**

