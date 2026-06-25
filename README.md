# Visual Dashboards of Data-Driven-Project-Analysis-Statistical-Study-of-Consumer-Behavior-and-Lifestyle-Outcomes
📋 Overview

This project presents a comprehensive statistical analysis of student dietary habits and their effects on lifestyle outcomes — specifically sleep quality, stress levels, and alcohol consumption patterns — tracked across a full academic year (January–December 2025) using data from the ACHA 2025 dataset (n = 12 months).

The findings are delivered as both an interactive React dashboard and a multi-page visual PDF report, covering descriptive statistics, regression analyses, ANOVA testing, and correlation profiling.


📊 Dashboard Sections

1. Overview

Highlights key performance metrics across the dataset at a glance:

MetricValueAvg Pizza Consumption6.16×/month (range: 4–9)Avg Sleep Quality6.78 / 10 (declining trend)Avg Stress Level6.39 / 10 (rising over academic year)Alcohol Frequency58.6% of students drinking monthlyANOVA F-Value45.85 (Alcohol → Stress, p ≈ 0)



2. Alcohol Analysis

Explores alcohol consumption frequency and its relationship to student stress



3. Statistical Tests & Correlations

Deep-dive into the inferential statistics underpinning the analysis


🎨 Visual Assets

The dashboard and report use a consistent design language throughout:

TokenColorUsageNavy #1B2A4AShow ImageHeaders, backgroundsTeal #1A7A7AShow ImageSection titles, sleep data, significant resultsAmber #E8A020Show ImageAccent bar, warnings, not-significantCoral #D95F3BShow ImageStress data, alerts, negative correlationsMint #3DB88BShow ImagePositive outcomes, low-risk groupsLavender #7B6FB5Show ImageAlcohol frequency data

Chart types used: Line charts, vertical & horizontal bar charts, scatter plots, pie chart, and KPI cards — all built with Recharts in the React dashboard and ReportLab in the PDF.


📄 Report

The full visual PDF report (3 pages) is available here:https://visual-report-dietary-analysis.netlify.app

🔗 View Report on Netlify


🛠 Tech Stack


Dashboard — React, Recharts, inline CSS
PDF Report — Python, ReportLab
Deployment — Netlify
Dataset — ACHA National College Health Assessment 2025


