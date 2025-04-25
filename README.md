# Bakery-Market-Basket-Analysis
This repository contains the complete analysis and recommendations from the award-winning UNCW MS Business Analytics capstone project on optimizing product pairings for revenue growth.

Business Problem The bakery sought data-driven strategies to:

Identify high-value product associations Optimize upselling opportunities Implement effective suggestive selling strategies Enhance operational efficiency Increase customer spend per visit

Methodology Data Analysis

Conducted association rules mining using R (arules package) Analyzed transaction patterns across multiple product categories Identified seasonal and time-based purchasing behaviors Calculated key association metrics: support, confidence, and lift values

Visualization

Created comprehensive Tableau visualizations for:

Seasonal purchasing patterns Year-Round purchasing patterns Product category associations Time and day analysis Product-specific performance

Key Findings Strong Product Associations

Holiday-themed products showed exceptional lift values (17-49) Cinnamon Croissant & Cheese Danish: strongest year-round pairing (372 transactions) Coffee showed strong associations with pastry items, particularly Cinnamon Croissants

Temporal Patterns

Peak sales hours: 11AM-1PM (particularly on weekends) Coffee peak hours: 9AM-10AM Friday/Saturday sales significantly higher than weekdays Seasonal product popularity spikes October-December

Customer Behavior Insights

When customers buy butter cookies, they're 11.38% likely to also purchase large eclairs Mini eclairs show strong purchase association with cream puffs (8.9 lift) Cheesecake purchases strongly correlate with specific complementary items

Business Recommendations Staffing & Operations

Schedule top performers during identified peak hours Cross-train BOH staff on coffee operations during high-volume periods Implement data-driven prep sheets using historical transaction patterns

Sales Strategy

Bundle coffee as an add-on to pastry items (maintaining 50% margin) Create table cards highlighting "Perfect Pairings" for staff reference Implement two-tier loyalty program focusing on coffee/pastry combinations

Seasonal Planning

Prepare inventory for October-December transaction spike Feature identified high-lift seasonal product combinations Develop special promotions for slower periods

Project Impact The recommendations from this analysis provided actionable strategies to:

Increase average transaction value Enhance operational efficiency Improve customer experience Boost revenue through strategic product pairings

Repository Structure

code/: R scripts for market basket analysis data_preparation/: Excel methodology and data cleaning documentation visualizations/: Static visualizations exported from the analysis dashboards/: Power BI interactive dashboard files reports/: Detailed documentation of recommendations and methodology data/: Sample anonymized datasets presentation/: Complete presentation slides in PDF format

Data Privacy Note All data in this repository has been anonymized to protect client confidentiality. Product names are preserved to demonstrate analytical findings while ensuring business identity remains protected. Project Role As the Project Manager for this top-ranked capstone project in the MS Business Analytics program, I led documentation, submission tracking, and performance monitoring while maintaining regular client check-ins. I also contributed significantly to the data analysis, visualization creation, and strategic recommendation development. Technologies Used

Excel (data cleaning, preparation, and initial analysis) R (market basket analysis and association rules mining) Tableau (advanced data visualization) Power BI (interactive dashboard creation)

Project Process

Data Preparation (Excel):

Cleaned and structured transaction data Created pivot tables for initial pattern discovery Formatted data for import into R for association analysis

Market Basket Analysis (R):

Conducted association rules mining Calculated support, confidence, and lift metrics Identified significant product pairings

Visualization & Analysis:

Created comprehensive visualizations using Tableau Developed interactive dashboards in Power BI Conducted time-based and product-specific analysis

Business Recommendations:

Translated analytical findings into actionable recommendations Developed implementation strategies Created presentation for stakeholders
