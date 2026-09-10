Olist Marketplace Performance Analysis

Team: The Delivery Detectives (Solo Submission) Hackathon: Gradient Data Analytics Hackathon Analysis Period: September 2016 – October 2018

Overview

This project is a full analytical investigation into the Olist Brazilian E-Commerce Public Dataset — approximately 99,441 real orders placed on Olist's marketplace between September 2016 and October 2018.

The goal: determine what is actually driving customer satisfaction on the platform, where performance varies most, and what Olist should prioritize as it scales to more sellers and regions of Brazil.

Repository Structure
├── notebook/
│   └── Olist_Marketplace_Performance_Analysis.ipynb   # Full analysis notebook (Colab)
├── report/
│   └── Olist_Marketplace_Performance_Analysis_Report.docx   # Written business report
├── charts/
│   └── chart1_trends.png ... chart6_compound.png      # Key visualizations
├── docs/
│   └── video_script.md                                # 3-minute video presentation script
└── README.md
Core Questions Investigated
Marketplace Performance Over Time — order volume, revenue, and review score trends
Delivery Performance and Customer Satisfaction — how delivery timing relates to review scores
Seller and Geographic Patterns — how location relates to delivery, freight, and satisfaction
Product Category Performance — volume, price, and review scores across categories
Payment Behavior — payment type and installments vs. order value and experience
Root Cause Analysis — the primary and secondary drivers of low review scores
Key Finding

Delivery timing is the single strongest observed driver of customer satisfaction on Olist. Late deliveries drop average review score from 4.28 to 2.26 — a pattern that holds consistently across every major product category and region, and compounds further when combined with cross-state shipping (average score drops to 2.14, the lowest in the dataset). Payment behavior, by contrast, shows negligible correlation with satisfaction.

See the full report for the complete analysis, evidence, and recommendations.

How to Run
Open notebook/Olist_Marketplace_Performance_Analysis.ipynb in Google Colab
Upload the Olist dataset (.xlsx with sheets: orders, order_items, order_payments, order_reviews, customers, products, sellers, geolocation, category_translation)
Run all cells top to bottom
Data Source

Brazilian E-Commerce Public Dataset by Olist, originally published on Kaggle under a Creative Commons Attribution-NonCommercial-ShareAlike license.

Video Presentation

Watch the 3-minute presentation: Click here to watch

See the full script: https://drive.google.com/file/d/14Drye0LDGEzrZqHVL8Q-lLorqDolwZvl/view?usp=drive_link

Deliverables
✅ Google Colab Notebook — data cleaning, EDA, analysis, visualizations, key findings
✅ Analysis Report — problem understanding, approach, insights, recommendations
✅ 3-Minute Video Presentation
