# 🚴 Global Retail & E-Commerce Performance Analysis (Excel)

## 📌 Project Background & Context
**Role:** Associate Data Analyst (Data Analyst Bootcamp Client Project)  
**Stakeholder Audience:** Regional Sales Directors  

**Context:** 
As part of my intensive Data Technician Bootcamp, I took on the role of a data consultant to complete a hands-on performance audit for a global consumer retail brand specializing in outdoor equipment and athletic goods. Moving beyond basic spreadsheet management, this project required using advanced Excel architectures to analyze transactional and demographic records across key international markets (United States, Germany, Australia) to identify revenue trends and optimize reporting efficiency.

---

## 📑 Executive Summary
An analysis of global sales transactions reveals that the **United States** stands as the primary revenue engine, dominating volume across all major product lines. Demographically, **consumers aged 35–64 in Germany** and **female shoppers globally** represent the highest-converting segments with the strongest average order values. Conversely, a severe profitability deficit was identified within the **Australian male customer group**, underperforming expectations compared to global cohorts. 

Through this analysis, I delivered automated reporting frameworks designed to help teams capitalize on high-performing European demographics and investigate margin compression in underperforming regional segments.

---

## 🛠️ Technical Workflow & Practical Applications
During my bootcamp training, I applied industry-standard workflows to clean, model, and visualize real-world business data:

### 1. Data Hygiene & Engineering
*   **Transaction Integrity:** Implemented transaction-identifier tracking to ensure zero data loss during multi-stage sorting, cleaning, and filtering phases.
*   **Database Lookups:** Utilized data-matching functions (`VLOOKUP`) to link demographic tables to transactional fact tables, establishing a clean relational dataset.

### 2. Automated Business Logic
To simulate a real reporting environment, I built conditional logical frameworks directly into the data model to automate how SKU velocity is classified:
*   **High Velocity:** Sales Volume > 600 units
*   **Medium Velocity:** Sales Volume 300–600 units
*   **Low Velocity:** Sales Volume < 300 units

*Formula Architecture Applied:* 
`=SWITCH(TRUE(), Volume_Cell>600, "High", Volume_Cell>=300, "Medium", "Low")`

### 3. Metric Aggregation & Reporting
Constructed multi-perspective Pivot Tables to isolate core performance indicators:
*   **Financial Performance:** Segmented revenue distribution, total commissions, and regional profitability.
*   **Demographic Mapping:** Cross-tabulated transaction frequency against customer age brackets and gender splits to isolate core market profiles.

---

## 📊 Insight Deep Dive & Visualization Strategy

### 📈 Core Findings:
*   **The German Expansion Opportunity:** The 35–64 age bracket in Germany represents an outsized share of regional profits, indicating a highly mature, stable target demographic.
*   **The Australian Profitability Deficit:** While transaction volume for Australian male customers remained steady, overall profitability was disproportionately low, pointing to structural margin issues (high shipping costs, deeper discounting, or unfavorable product mix).

### 🎨 Dashboard & Design Philosophy
To ensure maximum readability for stakeholders, I intentionally moved away from static, multi-colored charts (such as pie charts). Shifting trends across age distributions were mapped via continuous **Line Charts** and **Area Graphs**, which allow regional directors to instantly compare trajectory changes across fiscal periods without visual clutter.

---

## 🚀 Environment & Tooling
*   **Analytics Platform:** Microsoft Excel
*   **Key Toolkit:** Pivot Tables, Pivot Charts, Dynamic Arrays, Conditional Logical Modeling (`SWITCH`), Demographic Matrix Segmentation
*   **Training Foundation:** Data Technician Bootcamp
