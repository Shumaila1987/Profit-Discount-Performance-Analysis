# Profit & Discount Performance Analysis
 
## Project Overview
This end‑to‑end sales‑analysis project uses the public Superstore retail dataset to explore profit performance and discount‑distribution patterns across product groups, customer segments and geographic regions. Alongside this Power BI dashboard, I previously completed a separate customer‑segment‑level RFM analysis on the same dataset, to examine customer‑value patterns. This combined work forms portfolio practice for sales‑focused data‑analyst roles.
 
## Dataset Information
‑ Source: Public Superstore retail‑sales dataset
‑ Key fields used: Order Date, Category, Sub‑Category, Segment, Region, Profit, Discount, Quantity, Sales, Customer ID
‑ Data‑pre‑processing steps: Checked Customer ID validity; reviewed for missing records and negative‑value entries before loading into Power BI (cleaning workflow documented within the Power BI query steps)
 
## Tools & Methods
‑ Primary tool for this dashboard: Microsoft Power BI Desktop
‑ Work flow: Import raw data → quality‑check in Power Query → build data model → create consistent‑styled visuals → compile one‑page analysis dashboard
‑ Visual design approach: Used copy‑and‑swap‑field technique to maintain unified pink‑themed styling across all charts; assigned fixed distinct colours to each geographic region for consistent reading
‑ Prior related analysis: Customer‑segment‑focused RFM (Recency‑Frequency‑Monetary) study carried out to rank buyer‑group value ‑ output stored in a separate portfolio repository folder
 
## Key Findings
‑ Product performance: Technology is the highest‑profit main category; Copiers and Phones are top‑performing sub‑categories; several Furniture sub‑categories show lower profit returns.
‑ Customer segments: The Consumer segment contributes the largest share of total profit, followed by Corporate and Home Office ‑ these same groups were also examined in my earlier RFM analysis to identify high‑value buyer profiles.
‑ Regional outcomes: Overall total profit = 286.40 K; West and East regions are leading profit‑generating areas.
‑ Discount patterns: Office Supplies within the Central region received the highest total discount volume ‑ discount levels vary noticeably across different category‑region combinations.
 
## Project Files in this Repository
‑  .pbix  Power BI dashboard file
‑ Brief screenshot of the finished one‑page dashboard
- Raw source dataset Sample‑Superstore.csv

 
## Possible Future Work
‑ Add time‑series trend charts to track profit and discount changes year‑over‑year
‑ Build additional DAX measures to calculate profit‑margin percentages per product sub‑category
‑ Combine the RFM customer‑value results with this profit‑and‑discount dashboard to create an integrated sales‑and‑customer‑insight report

Project created by Shumaila | Data‑Analyst‑Portfolio Project ‑ Oct 2026
