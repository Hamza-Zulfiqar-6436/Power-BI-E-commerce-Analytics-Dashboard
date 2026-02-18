# E-Commerce Analytics Dashboard Using Power BI

## Project Overview

This project is an end-to-end Power BI dashboard built using the Brazilian Olist E-commerce dataset. The dashboard analyzes sales performance, customer behavior, payments, and delivery operations.

The primary focus of this project was not just visualization, but ensuring KPI accuracy through proper DAX logic, filter context control, and row-level validation.

 ## Business Objectives

- Analyze overall sales performance

- Evaluate customer segmentation

- Monitor payment distribution trends

- Measure delivery performance and operational efficiency

- Identify state-wise delivery delay patterns

## Key KPIs Built

- Total Orders

- Revenue & Sales Trends

- On-Time Delivery Rate

- Average Delivery Delay (Delivered Orders Only)

- Late Deliveries by State

## Technical Implementation

- Used Power BI Desktop

- Implemented advanced DAX measures:

  - CALCULATE

  - FILTER

  - AVERAGEX

  - DATEDIFF

- Resolved filter context mismatch between visuals and measures

- Ensured delay metrics only included delivered orders

- Performed manual row-level validation to verify KPI correctness

## Delivery Performance Insight

The analysis revealed that most deliveries occurred earlier than the estimated delivery date, with an average delivery difference of approximately 11 days ahead of schedule across states.

State-level breakdown helped identify regional variations in logistics performance.

## Dataset

- Olist Brazilian E-commerce Dataset

- ~100K+ orders

- Includes orders, customers, payments, products, and delivery data

## Tools Used

- Power BI

- DAX

- Data Modeling

- Data Cleaning & Validation

## Key Learning Outcomes

- Importance of filter context in DAX

- Measure vs Column behavior differences

- KPI validation strategies

- Business-aligned metric modeling

- Data storytelling for operational dashboards
