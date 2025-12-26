# Data_Right
The dataset is a process report that contains records of contingency instruments issued by the legal department of Global Holdings.

# Problem Statement
The dataset is a process report that contains records of contingency instruments issued by the legal department of Global Holdings. You are expected to create a comprehensive and tracking dashboard for the team using the provided data. 

1. Explore the dataset attached using Microsoft PowerBI. Click this link for Download and Installation guide. 
2. Create a comprehensive reporting dashboard using the dataset to include but not limited to the following tracking features. 
a. Status Tracking 
b. Maturity Date Tracking 
c. Contingent Type 
d. Tenor report 
e. Beneficiary report 
f. Branch Ranking 
g. Customer Sector Ranking.


# Objective of Data Right

The objective of the DATA RIGHT project is to provide management with a single, reliable, and interactive view of contingent transaction performance, enabling timely monitoring, risk visibility, and informed decision-making across status, maturity, tenor, beneficiary, branch, and customer dimensions.

# Transformation Process

The data-cleaning process was designed to ensure that all insights presented in DATA RIGHT are accurate, consistent, and decision-ready. Before any visualization or KPI computation, the dataset was systematically cleaned to remove errors, inconsistencies, and duplicates that could distort reporting or mislead management decisions.

1. Data Validation & Initial Screening

Before cleaning began, the dataset was subjected to an initial validation process to:

Confirm expected data types (dates, numeric amounts, text fields)

Identify missing or malformed records

Detect outliers and logical inconsistencies

This step helped define what constitutes an error versus a valid business exception.


2. Error Identification & Removal

These are errors that affect data format or structure:

Incorrect date formats (e.g., text instead of date)

Numeric fields stored as text

Inconsistent naming conventions (e.g., branch names, customer names)


3. Duplicate Detection & Removal
a. Duplicate Definition

Duplicates were defined using a composite key, not just a single column, to avoid false positives.
Records with identical composite keys were flagged as duplicates

Time-based and amount-based duplicates were cross-checked to avoid removing legitimate repeat transactions

# DATA RIGHT – Overall Overview

DATA RIGHT provides a comprehensive, structured, and insight-driven view of the organization’s operational, financial, and customer-related performance. The report brings together multiple dashboards—covering maturity tracking, contingent liabilities, customer sectors, branch performance, beneficiary analysis, payroll data, and overall portfolio tracking—to deliver a clear picture of how the institution is performing across key dimensions.
By combining data quality, transparency, and analytics, DATA RIGHT enables leadership to quickly identify trends, assess risks, measure operational efficiency, and evaluate business opportunities. The insights help ensure that strategic decisions are grounded in accurate information, while highlighting areas that require attention, improvement, or deeper analysis.
Overall, DATA RIGHT serves as a central intelligence hub that strengthens monitoring, enhances accountability, and supports data-driven decision-making across the organization.


# VisualizationS

EXECUTIVE SUMMARY (STATUS TRACKING DASHBOARD)

![<img width="631" height="371" alt="Status tracking" src="https://github.com/user-attachments/assets/0e792631-d7eb-47a4-8e79-1de62cd2dc1e" />
](Status tracking.jpg)

#Executive Summary Status Tracking Dashboard

The Status Tracking Dashboard shows a total of 960 transactions, with 952 (99%) still active, 158 completed, and 8 cancelled. Financial performance is strong, with ₦1.46bn in commissions, ₦101M in legal fees, and ₦264bn in guaranteed value. Activity is concentrated in a few high-performing branches, while monthly trends show a gradual decline in active transaction volume.

# Key Insights

High Pipeline Load: Active transactions dominate the workflow (99%), indicating heavy operational demand and potential processing bottlenecks.

Uneven Branch Activity: Some branches contribute significantly more transactions than others, suggesting imbalance in workload and potential best-practice opportunities.

Declining Monthly Trend: Active transaction volume has been dropping month-to-month, pointing to reduced customer activity or slower processing.

Strong Revenue Impact: Commission earnings remain solid, supported by a substantial guaranteed exposure.

# Recommendations

Improve Throughput: Review transaction processing flow to increase completion rates and reduce backlog.

Optimize Branch Performance: Standardize processes and redistribute workload across branches to enhance efficiency.

Investigate Decline: Analyze the monthly drop in transactions to determine whether it is seasonal, operational, or market-driven.

Strengthen Risk Monitoring: Given the large guaranteed exposure, maintain close oversight on high-value active transactions.

Investigate Decline: Analyze the monthly drop in transactions to determine whether it is seasonal, operational, or market-driven.


# Execuitive Summary (Maturity Date Dashboard)

![![Maturity Date Tracking](https://github.com/user-attachments/assets/78286a7c-e91e-4b73-a7b6-fca5881a9a83)
](Maturity Date Tracking.jpg)

The Maturity Date Tracking Dashboard provides an overview of 960 guaranteed transactions, 368 contingent IDs, and 7 contingent liabilities, with a strong distribution across maturity buckets. Medium-term items dominate both customer sector activity and legal fee exposure. Financial metrics remain strong with ₦1.46bn in commissions, ₦101M in legal fees, and ₦264bn in total guaranteed value.

# Key Insights

Medium-Term Dominance: Medium-term maturities account for the largest share of customer activity (68%) and attract the highest legal fees.

Low Long-Term Exposure: Long-term transactions represent a very small proportion (2.6%), reducing long-duration risk.

Commission Growth by Maturity: Commission earnings rise sharply with maturity time, indicating higher-value transactions concentrated in specific maturity windows.

Balanced Liability Distribution: Contingent liabilities remain low (7), suggesting controlled exposure and manageable risk levels.

# Recommendations

Prioritize Medium-Term Monitoring: Since most activity and legal fees fall under medium-term maturities, strengthen oversight and automate reminders for approaching maturity dates.

Enhance Long-Term Portfolio Strategy: Explore opportunities to grow long-term transactions for stability and predictable revenue.

Optimize Legal Costs: Review legal processes for medium-term items to reduce rising legal fee concentration.

Strengthen Risk Controls: Maintain close tracking of contingent liabilities to prevent unexpected exposure and ensure timely resolution.


# Executive summary

![![Contingent Type Tracking](https://github.com/user-attachments/assets/28bcb550-ba24-4692-b29f-69f7bf36ff3d)
](Contingent Type Tracking.jpg)

# EXECUTIVE SUMMARY

The Contingent Type Tracking Dashboard provides an overview of contingent liabilities totalling ₦264bn across 960 guaranteed items and 368 contingent IDs. The majority of exposure is concentrated in a few contingent liability types, particularly APG and BG, which dominate both the guaranteed amount and the number of contingent IDs. Financial performance remains strong with ₦1.46bn in commission and ₦101M in legal fees, supported by a broad distribution of contingent instruments.

# KEY INSIGHT

High Exposure in APG and BG: APG and BG collectively account for most of the guaranteed value and over 68% of contingent IDs, indicating heavy reliance on these instruments.

Uneven Liability Distribution: Other liability types such as PG, Custom Bonds, and IGADV contribute significantly less, suggesting a concentrated risk profile.

Commission Performance Follows Exposure: Average commission amounts and guaranteed amounts align with the liability types carrying the highest exposure, reinforcing their financial impact.

Low Utilization of Long-Tail Instruments: Instruments with lower counts (e.g., IGADV, BID Bond) may reflect untapped business opportunities or limited demand.

# RECOMMENDATION

Strengthen Monitoring on High-Exposure Types: APG and BG require close oversight due to their dominant share of liability and guaranteed values. Implement tighter tracking, periodic risk reviews, and early-warning indicators.

Diversify Contingent Liability Portfolio: Explore strategies to increase adoption of underutilized contingent instruments to reduce concentration risk and broaden revenue streams.

Optimize Commission Strategy: Evaluate pricing and approval processes for high-exposure contingent types to ensure commission income aligns with risk levels.

Enhance Risk Controls: Review underwriting and approval standards for APG and BG to ensure exposure remains within acceptable risk thresholds.



# EXECUTIVE SUMMARY (TENURE)

![![Tenure Tracking](https://github.com/user-attachments/assets/80f2d950-16a5-4104-836e-9a137d23a649)
](Tenure Tracking.jpg)

# EXECUTIVE SUMMARY (Tenor Tracking Dashboard)

EXECUTIVE SUMMARY – Tenor Tracking

The Tenor Tracking dashboard shows activity across Short-term, Medium-term, and Long-term contingent liabilities. Medium-term and Long-term dominate both the number of transactions and total guaranteed value (₦264bn). Total commissions amount to ₦1.46bn, while legal fees total ₦101m.

# KEY INSIGHTS

Medium-term has the highest transaction volume and strong commission performance.

Long-term carries the highest guaranteed amounts and legal fees, indicating higher exposure and more complex processing.

Short-term activity is minimal, showing limited customer uptake or stricter qualification.

Some branches show higher cancellation levels, mostly within Short- and Medium-term categories.

# OVERALL INTERPRETATION

The portfolio is concentrated in Medium- and Long-term tenors, which drive revenue but also carry higher operational and risk exposure. Short-term products remain under-utilized, and branch inconsistencies highlight operational gaps.

# RECOMMENDATIONS

Strengthen risk controls on Long-term guarantees due to higher exposure and legal costs.

Optimise Medium-term processing to maintain strong performance.

Investigate branch-level cancellations and enforce better compliance.

Review and promote Short-term guarantee offerings to boost adoption.


# EXECUTIVE SUMMARY (BENEFICIARY TRACKING DASHBOARD)

![![Beneficiary Tacking](https://github.com/user-attachments/assets/fd460e5e-6cc2-4ad1-9857-97a6d66c5b6f)
](Beneficiary Tacking.jpg)

# EXECUTIVE SUMMARY – Beneficiary Tracking

The Beneficiary Tracking dashboard highlights performance across beneficiaries and branches, focusing on guaranteed amounts, commissions, and cancellation patterns. Total transactions stand at 960, generating ₦1.46bn in commissions and ₦264bn in guarantees.

# KEY INSIGHTS

A small number of beneficiaries contribute the majority of guaranteed amounts, showing a concentrated portfolio.

Commission earnings are highest within a few key customer sectors, led by Manufacturing.

Cancellations are low overall but disproportionately higher in specific branches, signaling operational inconsistencies.

Some beneficiaries consistently show strong guaranteed amounts paired with high commissions, indicating strong business relationships.

# OVERALL INTERPRETATION

The portfolio relies heavily on a core group of beneficiaries and sectors. While this concentration boosts performance, it increases dependency risks. Branch-level variations in cancellation rates suggest gaps in process compliance or beneficiary documentation quality.

# RECOMMENDATIONS

Strengthen due diligence and documentation for high-value beneficiaries to reduce exposure.

Investigate branches with repeated cancellations and enforce standardized processing controls.

Expand engagement across underperforming sectors to diversify the beneficiary base.

Maintain strong relationship management for top-performing beneficiaries while monitoring concentration risks.


# EXECUTIVE SUMMARY (BRANCH TRACKING DASHBOARD)

![![Branch Ranking](https://github.com/user-attachments/assets/4474b1f1-8dde-41c6-994f-35625c91fbcc)
](Branch Ranking.jpg)

# EXECUTIVE SUMMARY – Branch Ranking

The Branch Ranking dashboard highlights performance across 31 branches, assessing guaranteed amounts, commissions, legal fees, and transaction volume. Total transactions stand at 960, contributing ₦1.46bn in commissions and ₦264bn in guarantees.

# KEY INSIGHTS

A few branches—particularly HorizonVista, FusionAxis, and PeakBridge—account for the largest guaranteed amounts, indicating strong business generation.

Transaction volume is similarly concentrated, with top-performing branches consistently outpacing others.

Some branches generate high commissions and legal fees, suggesting a mix of high-value deals and complex transactions.

Underperforming branches show low transaction counts and minimal guaranteed amounts, indicating untapped potential or operational gaps.

# OVERALL INTERPRETATION

Branch performance is uneven, with a small group of branches driving most of the portfolio’s value. This concentration presents an opportunity for targeted support to underperforming branches while strengthening high-performing ones to sustain growth.

# RECOMMENDATIONS

Provide targeted business development support and capacity building for low-performing branches.

Deepen engagement with high-performing branches to maintain momentum and understand success drivers.

Standardize operational processes across branches to reduce performance gaps.

Monitor branch-level risk exposure to ensure balanced portfolio distribution.


EXECUTIVE SUMMARY (CUSTOMER SECTOR RANKING)

![![Customer tracking](https://github.com/user-attachments/assets/2a10c04c-594b-4fbc-94ca-893b36ea559f)
](Customer tracking.jpg)

# EXECUTIVE SUMMARY – Customer Sector Ranking

The Customer Sector Ranking dashboard provides an overview of transaction performance across 188 customer sectors, contributing to 960 total transactions, ₦1.46bn in commissions, and ₦264bn in guarantees.

# KEY INSIGHTS

Construction and Manufacturing sectors contribute the highest guaranteed amounts, showing strong business activity.

Commission earnings are also dominated by Manufacturing, Construction, and Agriculture, reflecting high-value engagements.

Transaction distribution across sectors is broad, but a few sectors account for the majority of financial impact.

Some sectors generate modest guaranteed amounts but still contribute meaningfully to commission income.

# OVERALL INTERPRETATION

The portfolio is heavily influenced by a few high-performing sectors, particularly Construction and Manufacturing. This concentration highlights stable revenue drivers but also suggests exposure risk if these sectors fluctuate.

# RECOMMENDATIONS

Deepen partnerships with top-performing sectors to sustain revenue generation.

Explore opportunities in underrepresented or emerging sectors to diversify the portfolio.

Monitor performance trends to anticipate sectoral shifts or potential risks.

Align sector-focused strategies with high-potential areas to improve contribution balance.


# DATA RIGHT – Overall Closing Statement

“The DATA RIGHT report delivers a comprehensive, end-to-end view of contingent risk — from status and maturity, through type, tenor, beneficiary, branch, and customer — enabling informed, proactive, and data-driven executive decisions.”
