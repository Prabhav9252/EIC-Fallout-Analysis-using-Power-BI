# EIC-Fallout-Analysis-using-Power-BI

<img width="1157" height="644" alt="image" src="https://github.com/user-attachments/assets/960fb2c3-a6e8-41f2-b328-6c684e16d86f" />


## Overview
This project demonstrates the design and implementation of an **Insurance Performance Dashboard** using Power BI. 
The dashboard analyzes an insurance company's financial and operational data, focusing on **premiums, claims, policy trends, and profitability**. 
It transforms half a million rows of raw policy data into interactive visual insights that help identify loss-making segments, profitable categories, and overall business performance.

## Objectives
- Evaluate the financial performance of the insurance company.
- Track total premiums collected vs. claims paid over time.
- Analyze the **premium-to-claims ratio** to assess profitability.
- Identify which **vehicle types, makes, and demographics** contributed most to losses or profits.
- Provide interactive visuals to support decision-making in **risk management and underwriting**.

## Dataset
The dataset consisted of ~500,000 policy records with details such as:
- Policy start and end dates.
- Vehicle type, make, and usage.
- Policyholder demographics (sex code).
- Premium amount collected and claim amount paid.
- Insured value.

A supporting **calendar table** was added to enable time-based analysis (year, quarter, month).

## Features of the Dashboard
1. **KPI Cards**
   - Policies issued/closed.
   - Total premiums vs. claims.
   - Average premium vs. average claim.
   - Premium-to-claims ratio (with red/green conditional formatting).
   - Total claim counts.

2. **Segmentation Analysis**
   - Vehicle types, usage, and makes contributing to profits/losses.
   - Interactive bar charts and scatter plots with tooltips.

3. **Claims Trend Analysis**
   - Ribbon charts showing year-wise distribution of claims across vehicle usages.

4. **Demographic Impact**
   - Comparative analysis of policies vs. claims across different sex codes using donut charts.

5. **Profitability Exploration**
   - Scatter plots with symmetry shading to identify the "profit zone".

6. **Segment-Wise Profitability**
   - Matrix view with conditional formatting (red = losses, green = profits).

7. **Interactivity**
   - Dynamic slicers for year-based filtering.
   - Detailed tooltips with premium, claims, and ratios.
   - Professional custom visuals, icons, and themes.

## Key Insights
- The company incurred **major losses** from 2014–2017, with claims ($9.2B) far exceeding premiums ($4B).
- Only in **2018 (Q2)** did the company briefly turn profitable.
- **Motorcycles and certain vehicle makes** were profitable, while trucks and buses drove heavy losses.
- Around **10% of policies resulted in claims**, but claims were disproportionately large.
- Overall, the business model was **unsustainable**, highlighting poor underwriting/risk management.

## Tools and Technologies
- **Power BI** – dashboard design and DAX measures.
- **DAX** – calculations for KPIs, ratios, and profitability metrics.
- **Power Query** – data cleaning and transformation.
- **Custom Visuals & Design** – card visuals, scatter plots, tooltips, and custom backgrounds.

## Conclusion
This project demonstrates how **Power BI can transform raw insurance data into actionable business insights**. 
It highlights how poor underwriting decisions led to cumulative losses and showcases how dashboards can guide better **policy pricing, risk management, and strategic planning**.
