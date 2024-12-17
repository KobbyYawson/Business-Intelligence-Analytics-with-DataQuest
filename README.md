## Data Analysis and Dashboard Design Project as a Business Intelligence Analyst at DataQuest

## Overview

This document serves as a guide to the steps, tools, and methods used in analyzing CRM sales opportunities data and creating interactive visualizations for Festman Learning Hub, under the task assigned by DataQuest Solutions.

## Project Details

**Tools and Technologies Used**:

**Python**: For initial data analysis and preparation.

**Power BI**: For advanced analysis, visualizations, and interactive dashboard design.

**DAX (Data Analysis Expressions)**: To create calculated measures and columns for deeper insights.

**Power Query**: For data transformation within Power BI.


## Project Workflow

**1. Data Preparation and Import**

Imported datasets into Power BI.

Ensured data cleanliness and consistency.

Utilized Python notebooks for preprocessing and data analysis prior to importing.

Segmented revenue figures into predefined ranges for analysis.

**2. Key Analysis Tasks**

**Distribution Analysis**:

Segmented account revenues into ranges such as 1B-5B, 500M-1B, 100M-500M.

**Performance Metrics**:

Identified top-performing products by close rate.

Analyzed the performance of sales teams, agents, and managers across regions and product lines.

Derived insights into patterns of deal values, close dates, and product preferences across industries.

**3. Calculations and Features Implemented**

**DAX Calculations**:

Created measures to calculate:

Total closed deals (Won + Lost).


Counted deals by deal_stage and filtered for specific timeframes (monthly, quarterly).

**Sorting and Ordering**:

Sorted revenue segmentation using an independent sorting table to avoid circular dependency.

Ensured correct ordering of bar charts using a SortOrder column.

**Visualizations**:

Bar charts for revenue segmentation.

Line graphs to compare trends between engaged and closed deals over time.

Drill-down capabilities to explore sales performance by managers and agents.

**Enhancements**:

Curved edges for visual blocks.

Interactive slicers for filtering data by managers, sales agents, regions, and deal stages.

**4. Challenges and Solutions**

Challenge: Circular dependency when sorting revenue ranges.

Solution: Created an independent table for sorting and linked it to the existing table using an active relationship.

Challenge: Ambiguous relationships between tables.

Solution: Revisited the data model to ensure appropriate and unique relationships between tables.

Challenge: Adjusting visual trends after linking multiple date columns.

Solution: Used inactive relationships and custom DAX measures to separate trend lines for engaged and closed deals.

**5. Dashboard Features**

Fully interactive dashboard with:

Drill-down and cross-filtering capabilities.

Multiple slicers for custom views.

Clear visualizations to highlight actionable insights.

Optimized visuals with:

Currency formatting for revenue in millions (USD).

Filters for monthly and quarterly trends.

## Final Deliverables

A comprehensive Power BI dashboard with:

Clear insights into sales team performance.

Revenue segmentation trends.

Top-performing products and accounts.

Visualizations of deal trends over time.

## Key Outcomes:

Identified actionable trends and insights for client’s management teams.

Presented findings effectively to stakeholders.

Notes for Future Reference

This README can serve as a template for documenting similar projects.

Ensure all relationships and DAX measures are double-checked for accuracy.

Keep visualizations user-friendly and tailored to client’s specific goals.

