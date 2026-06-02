# Gamezone Retail E-Commerce: Sales Performance Analysis (EDA)

![Sales performance Dashboard](/Images/Sales_performance_Dashboard.gif)

![Power BI](https://img.shields.io/badge/PowerBI-F2C811?style=for-the-badge&logo=power-bi&logoColor=black)
## 1. Executive Summary & Project Background

### Macro-Environment Context
This analysis examines a global gaming electronics retailer navigating the highly volatile macroeconomic landscape between **2019 and 2022.** This period was heavily defined by the COVID-19 pandemic, structural societal lockdowns, and subsequent digital acceleration.

As physical entertainment venues shuttered, consumer capital shifted drastically toward home entertainment ecosystems. This evaluation maps those dramatic changes in market demand to actionable cross-functional initiatives for **Finance, Product, and Marketing leaders.**

## Tech Stack & Skills Applied
* **Data Exploration & Prototyping:** Microsoft Excel (Pivot Tables, Advanced Formulas, Data Quality Audits)
* **Data Visualization & Analytics:** Power BI Desktop (DAX, Multi-Page Architecture, Interactivity, Page Navigation)
* **Frameworks Used:** SCAN Framework (Strategic Coverage, Aggregates, Notable segments), DASH Framework (Design, Audience, Signal, Hierarchy)

### The Analytical Objective

- **Objective:** Understand how total sales revenue ($ USD) performed across various products and regions from 2019 to 2022.

- **The goal of this EDA:** Is to dissect how global sales revenue (USD) performed across **products, timeframes, channels, and geographies.** The ultimate aim is to uncover high-level trends and behavioral anomalies before committing major engineering or financial resources to structural dashboard overhauls.

## 2. Methodology & Excel Architecture
![Pivot Table](/Images/Pivot_table.png)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)

###  Exploratory Data Analysis Architecture
To demonstrate rapid prototyping and core **Data Validation** skills, the initial discovery phase was executed entirely in **Excel**:
* **Pivot Tables & Slicers:** Deployed to isolate `usd_price` performance across months, regions, and marketing funnels.
* **Data Quality Profiling:** Conducted an anomaly audit that successfully flagged potential data corruption in the Gaming Headset logging infrastructure.

**The exploratory phase was built using structured Pivot Tables to isolate variables and identify root causes behind revenue shifts:**

The foundation of this data discovery phase was executed entirely within Microsoft Excel to establish a rapid data-validation prototype.

### Core Tracking Architecture
![Overall Sales](/Images/Overall_Sales.png)

- **Dimensions Analyzed:** `product_name`, `purchase_time`, `region`, and `marketing_channel.`
- **Primary Key Performance Indicator (KPI):** usd_price (Gross Revenue).
- **Baseline Baseline Volume:** $6.1 Million in cumulative gross sales captured between 2019 and 2021.
- **Monthly Operational Baseline:** Sales fluctuated heavily between a floor of $80,000 and a macro-peak of $500,000 per month.

## 3. Granular Insights & Analytical Discoveries

### Macro Timeline & Financial Trajectory

- **The Lockdown Catalyst:** The onset of global lockdowns in early 2020 acted as a massive catalyst. Total monthly gross revenue more than doubled compared to 2019 baselines. This explosive trajectory climbed steadily throughout the year, culminating in an all-time company spike between September and December 2020.
- **The Post-Peak Correction:** In early February 2021, the market experienced a synchronized revenue drop across all categories. This correction reflects a global market stabilization as vaccines rolled out, brick-and-mortar spaces reopened, and consumers diversified their discretionary spending.

### Product Portfolio Performance & Mix Matrix
![Top 3 Products](/Images/Top-3_Products.png)
- **The Revenue Engine:** The 27" 4K Gaming Monitor established itself as the company's clear flagship product, bringing in nearly $2.0 Million in total sales and maintaining the most stable demand footprint.
- **The High-Tier Complements:** The Nintendo Switch and PlayStation 5 (PS5) served as the secondary pillars of structural volume. However, these three top-tier products also drove the steep aggregate correction seen in early 2021.
- **The Portfolio Anomaly (Gaming Headsets):** Gross data reveals that Gaming Headsets accounted for less than 2% of total revenue (a mere $800 in total sales over multiple years). This performance is an extreme outlier that points to either a failed product line or a critical data logging failure where headset transactions were missed or misclassified.


### Acquisition Channels & Regional Breakdowns
![Marketing](/Images/Marketing-USD.png)
- **The Direct Traffic:** Website data shows that **"Direct"** web traffic is the overwhelming driver of sales. Outbound acquisition channels like Paid Search, Social Media, and Email Marketing appear flat by comparison. This signals an incredibly loyal organic audience but highlights a severe underutilization of targeted outbound marketing.

- **The North American PlayStation 5 Drop:** While the early 2021 market correction affected all regions, a deep dive reveals that the **PlayStation 5** suffered a localized drop focused heavily in the **North America (NA)** territory. Cross-referencing this drop shows it happened entirely within Direct web traffic, indicating a friction point on the domestic storefront or a sudden shift to local retail competitors.

## 4. Cross-Functional Strategic Recommendations


### Data Engineering & Governance
- **Attribution Funnel Audit:** [High Priority] Investigate the tracking setup for marketing channels. The massive size of the "Direct" segment suggests that tracking parameters (UTM tokens) from Paid Search, Social, and Email campaigns are breaking during checkout sessions, misclassifying paid traffic as direct visits.
- **Headset Data Sanity Check:** Audit historical databases to confirm if the $800 headset sales figure is accurate or a tracking error before making final inventory cuts.

### Product Management
- **Inventory Rationalization:** Assuming the data is validated, phase out and sunset the Gaming Headset line. Reallocate manufacturing budgets and warehouse shelf space to scale up high-margin variations of the Gaming Monitor ecosystem.

### Growth Marketing

- **North American PS5 Recovery Campaign:** Launch targeted seasonal campaigns in North America tailored to the PS5. Investigate if the early 2021 drop stemmed from checkout friction or design changes on the NA website.
- **Seasonal Playbook:** Double down on the golden holiday quarter. Group your top three performing products (Monitor, Switch, PS5) into attractive holiday bundles, launching campaigns early in October and November to capture early holiday demand.
- **Outbound Channel Diversification:** Build out a robust, segmented Email Marketing infrastructure. Email campaigns show early signs of organic growth potential; scaling this channel will reduce the brand's risky over-reliance on pure Direct traffic.

## Power BI Dashboard Implementation
The insights from the Excel EDA phase were converted into an interactive corporate report leveraging advanced **Power BI** capabilities:
* **User Experience (UX) Design:** Implemented a seamless multi-page navigation interface using programmed action buttons and custom back-navigation tiles following the **DASH Framework**.
* **Data Storytelling:** Structured visual hierarchy to separate high-level macro trends (Executive Page) from granular category deep-dives (Regional Page).

![Regional insights](/Images/Dashboard2.png)

# Conclusion
This Exploratory Data Analysis (EDA) successfully converts raw transactional data from the 2019–2021 COVID era into high-impact business intelligence. **The analysis highlights a $6.1M pandemic market surge heavily driven by the flagship Gaming Monitor (~$2M) and a universal sales peak in December 2020.**

Crucially, the EDA exposes key operational vulnerabilities: an aggressive post-peak correction in early February 2021 **(centered on the PS5 in North America)**, an over-reliance on Direct web traffic, and a potential data-logging failure in the Gaming Headset line (<2% of revenue).

## Next Steps & Action Plan
- **Data Engineering:** Audit the tracking funnel to fix broken UTM tokens and verify the missing headset data logs.

- **Product:** Sunset underperforming headsets and reallocate manufacturing capital to high-margin monitors.

- **Marketing:** Build a Q4 holiday bundling playbook and scale outbound email marketing to reduce dependence on direct traffic.

Ultimately, this prototype phase validates data integrity, maps the macro-environment, and establishes a definitive roadmap for the final Sales Performance Power BI Dashboard.
