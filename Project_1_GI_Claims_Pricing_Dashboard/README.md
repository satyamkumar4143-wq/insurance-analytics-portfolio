# Project 1: India General Insurance Claims & Pricing Performance Dashboard

## 1. Project Objective

This project analyses premium growth, claim pressure and pricing adequacy signals across Indian general insurance segments using public insurance data.
The main objective is to show that premium growth alone does not prove profitability. A segment or insurer may show strong premium growth, but claims, incurred claims ratio, commission load and operating expenses must also be checked before interpreting pricing strength.

## 2. Business Problem

General insurance dashboards often focus only on premium growth and market ranking. However, premium growth is only a volume indicator.

This project asks a more practical insurance question:

**Are premium growth and market size supported by claim-pressure and pricing-load indicators?**

The project connects:
- Segment premium growth
- Insurer ranking
- Incurred Claims Ratio
- ICICI Lombard company-level claims, commission and operating expense load
- Dashboard-ready business insights

## 3. Data Sources Used

Source	- Data Used	Purpose in Project

GI Council Segment - wise GDPI data	Segment - wise gross direct premium by insurer and segment	Used for segment premium growth analysis and insurer ranking
IRDAI Annual Report 2024-25, - Table I.14	Segment-wise incurred claims ratio	Used for claim-pressure and pricing adequacy interpretation
ICICI Lombard NL-4 Public Disclosure	- Gross direct premium and net earned premium	Used for premium base and claim-ratio denominator
ICICI Lombard NL-5 Public Disclosure	- Net incurred claims	Used for claim-ratio numerator
ICICI Lombard NL-6 Public Disclosure	 - Gross commission and net commission	Used for commission load analysis
ICICI Lombard NL-7 Public Disclosure	- Operating expenses related to insurance business	Used for expense load analysis

## 4. Workbook Structure

Sheet Name	Purpose

Final_Summary	- Executive summary of project objective, methodology, key findings, recommendations and limitations
Dashboard_Draft	- Main dashboard with KPI cards, charts, claim-pressure caution box, executive insights and source note
Analysis	- Segment premium growth, insurer ranking, top 10 insurers and dashboard-ready insights
IRDAI_ICR_Data	- Segment-wise incurred claims ratio analysis and premium growth vs claim-pressure interpretation
ICICI_Company_Case	- Company-level pricing-pressure mini-case using ICICI Lombard NL-4 to NL-7 disclosures
Pivot_Auto_Segment_Analysis	- Pivot support for segment premium analysis
Pivot_Insurer_Analysis	- Pivot support for insurer ranking
Cleaned_Auto	- Cleaned long-format data created from GI Council source data
Raw_GI_Council	- Raw GI Council source extraction
Raw_IRDAI	Raw - IRDAI Table I.14 extraction
Raw_ICICI_NL4	- Raw ICICI Lombard premium extraction
Raw_ICICI_NL5	- Raw ICICI Lombard claims extraction
Raw_ICICI_NL6	 - Raw ICICI Lombard commission extraction
Raw_ICICI_NL7 -	Raw ICICI Lombard operating expenses extraction
Source_Log	- Source audit trail showing source, extraction status and sheets where each source is used

## 5. Methodology

The project follows a source-to-dashboard analytics workflow:

1. Collected public insurance data sources.
2. Extracted raw tables into separate raw sheets.
3. Cleaned GI Council data into long-format analysis-ready structure.
4. Built pivot tables for segment and insurer analysis.
5. Analysed selected segment premium growth from Apr-25 to Apr-26.
6. Added IRDAI incurred claims ratio to measure claim pressure.
7. Built ICICI Lombard mini-case using NL-4, NL-5, NL-6 and NL-7 disclosures.
8. Created dashboard with KPI cards, charts, claim-pressure box, executive insights and source note.

## 6. Key Findings

1. Selected segment premium increased from ₹29,143.19 Cr in Apr-25 to ₹31,654.17 Cr in Apr-26, showing 8.62% growth.
2. Health is the largest selected segment and grew 21.61%.
3. Marine grew fastest at 33.63%, but from a smaller base.
4. Motor ICR is 85.51% and Health ICR is 85.34%, showing high claim-pressure signals.
5. The New India Assurance Co Ltd ranked first by Apr-26 premium among selected insurers.
6. ICICI Lombard’s company-level analytical combined load indicator is 104.98%, suggesting pricing-load pressure before full P&L and investment income analysis

## 7. Recommendations

1. Premium growth should not be interpreted as profitability without checking claim pressure.
2. Motor and Health should be monitored closely because both show high incurred claims ratio.
3. Insurer ranking should be treated as market-volume ranking, not direct profitability ranking.
4. Pricing adequacy analysis should combine premium growth, ICR, claims, commission load and expense load.

## 8. Limitations

This project uses publicly available data only.
ICICI Combined Load is an analytical pricing-pressure indicator created for this project. It is not the formal combined ratio.
Selected ICICI segment rows do not add to Grand Total because Grand Total includes additional business lines beyond the selected case-study rows.
Final profitability cannot be concluded without full profit and loss account, investment income, reserves and complete underwriting result analysis.

## 9. Tools and Skills Used

- PlanMaker / Excel-style spreadsheet modelling
- Data cleaning
- Pivot tables
- Growth analysis
- Ratio analysis
- Dashboard design
- Source logging
- Insurance business interpretation
- Pricing adequacy and claim-pressure analysis
