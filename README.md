# Brand-Affiliate-Analysis DashBoard-TABLEAU-

Data Analytics | Marketing Performance | Tableau Visualization

---

## Project Overview
This project analyzes affiliate marketing performance across multiple gaming brands between January and March 2024. The goal is to evaluate brand-level acquisition performance, traffic quality, and revenue contribution using marketing funnel metrics such as impressions, clicks, signups, and first-time deposits.

The analysis was developed as an end-to-end data analytics project including data preparation, metric design, exploratory analysis, and interactive dashboard development using Tableau.

The dashboard allows stakeholders to quickly evaluate marketing effectiveness across brands and identify opportunities for improving customer acquisition and affiliate ROI.

---

## Problem Statement
Affiliate marketing is a major acquisition channel for many digital businesses. However, marketing teams often face several challenges:

• Limited visibility into which brands drive the most profitable traffic  
• Difficulty identifying where customer drop-off occurs in the acquisition funnel  
• Inability to quickly compare affiliate performance across brands  
• Lack of consolidated dashboards for executive reporting

This project addresses these challenges by building a centralized analytics dashboard that monitors the complete acquisition funnel and revenue performance by brand.

---

## Data Structure and Overview

Dataset Source Files:
• CSV Dataset  
• Excel Dataset  
• Tableau Workbook (.twbx)  
• Dashboard Image Preview (.jpg)

Main Data Fields:

| Column | Description |
|------|-------------| Brand | Gaming brand name |
| Brand ID | Unique identifier for each brand |
| Month and Year | Reporting period |
| Affiliate | Affiliate source sending traffic |
| Impressions | Number of ad impressions |
| Clicks | Number of ad clicks |
| Signups | New account registrations |
| NDC | New depositing customers |
| FDT | First time deposits |
| Net Revenue | Revenue generated |
| Earnings | Affiliate earnings |

The dataset represents the affiliate marketing funnel from visibility to revenue.

Marketing Funnel Structure:

Impressions → Clicks → Signups → Deposits → Revenue

---

## Success Metrics

Key performance indicators used in the analysis include:

• Impressions – advertising reach  
• Clicks – engagement with marketing content  
• Signups – conversion from visitors to registered users  
• NDC (New Depositing Customers) – high value customer conversion  
• FDT – first time deposit events  
• Net Revenue – total generated revenue  
• Earnings – affiliate payouts  
• ROI – return on marketing investment

These metrics allow measurement of both acquisition performance and profitability.

---

## Tools Used

Data Processing
• Microsoft Excel

Data Analysis
• SQL-style aggregation logic
• Data modeling

Visualization
• Tableau Dashboard

Version Control
• GitHub

---

## Data Analysis Process

Step 1: Data Collection
Affiliate marketing data was collected from Excel and CSV sources.

Step 2: Data Cleaning
• Removed null values
• Standardized brand names
• Checked duplicate affiliate records

Step 3: Data Modeling
Created calculated metrics including:
• Click-through analysis
• Signup conversion tracking
• Deposit conversion analysis
• ROI metrics

Step 4: Visualization
Built Tableau dashboard visualizations:

• Brand impressions comparison
• Click performance scatter chart
• Signup vs First-time deposit chart
• ROI trend by brand
• Earnings by brand
• Customer acquisition distribution

---

## Executive Summary

The dashboard reveals significant differences in marketing performance across brands.

Key insights:

• Nesine generated the highest share of impressions (64%)
• Bilyoner achieved the strongest new customer acquisition (40% share)
• Click performance varies significantly across brands
• Revenue distribution shows concentration among a few key brands
• Some brands generate impressions but limited conversions

These insights help marketing teams prioritize investment into high-performing acquisition channels.

---

## Recommendations

Based on the analysis:

1. Increase marketing spend on high converting brands such as Bilyoner.
2. Investigate low conversion brands to understand funnel drop-off.
3. Improve landing page optimization for brands with high impressions but low signups.
4. Evaluate affiliate quality based on deposit conversion rather than clicks.
5. Implement ongoing performance monitoring dashboards.

---

## Conclusion

Affiliate marketing performance varies significantly across brands. By visualizing the acquisition funnel from impressions to revenue, this project provides actionable insights that allow marketing teams to:

• allocate budgets effectively
• optimize acquisition strategy
• improve customer conversion
• maximize marketing ROI

---

## LinkedIn Storytelling Version

Data without context rarely drives decisions.

I built a Tableau dashboard to analyze affiliate marketing performance across multiple brands. Instead of only tracking traffic metrics, the project focused on the full acquisition funnel:

Impressions → Clicks → Signups → Deposits → Revenue

The analysis quickly revealed which brands actually generate high value customers rather than just traffic.

Key insight:
One brand generated the majority of impressions, but another brand delivered the highest new depositing customers.

This type of analysis helps marketing teams shift focus from vanity metrics to revenue-driving acquisition.

Tools used:
Tableau | Excel | Data Analysis | Marketing Analytics

---

## How to Use This Project

1. Clone the repository
2. Download the dataset files
3. Open the Tableau workbook (.twbx)
4. Explore the dashboard filters
5. Analyze brand performance metrics
6. Extend the project with additional KPIs

---

## Repository Structure

Brand-Affiliate-Analytics/
│
├── data/
│   ├── Brand-Affiliate-Dataset.csv
│   ├── Brand-Affiliate-Dataset.xlsx
│
├── dashboard/
│   ├── BrandAffiliate.twbx
│   ├── dashboard-preview.jpg
│
├── docs/
│   └── project-explanation.md
│
└── README.md

---
