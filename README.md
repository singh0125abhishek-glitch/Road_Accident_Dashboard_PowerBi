# Power BI Dashboard: Road Accident Analysis

## Overview

This Power BI dashboard provides an interactive, end-to-end analysis of road accident data for the years 2021 and 2022. It is designed to help stakeholders (such as the Ministry of Transport, police force, and emergency services) gain insights into accident trends, casualties, and severity to drive road safety decisions.

## Key Performance Indicators (KPIs)
**Primary Metrics:**
 - Total Current Year (CY) Casualties and Year-on-Year (YoY) Growth.
 - Total Current Year (CY) Accidents and YoY Growth.
 - Current Year Casualties dynamically categorized by Accident Severity (Fatal, Serious, Slight) with YoY comparisons.

**Secondary Metrics:**
 - Total Casualties grouped by specific Vehicle Types (e.g., Car, Bike, Bus, Van, Agriculture) utilizing custom grouping.

**Visualizations:**
 - Monthly Trend Analysis: An overlapping area chart comparing current year casualties versus previous year casualties on a monthly basis.
   
 - Casualties by Road Type: A horizontal bar chart detailing accidents across different road types (e.g., single carriageway, dual carriageway).
   
 - Demographic & Environmental Distributions: Donut charts breaking down casualties by Area (Urban vs. Rural) and Light Conditions (Day vs. Night).

 - Geospatial Analysis: A map visual plotting casualties and vehicles involved by local authority/district.

**Technical Implementations:**
 - Data Cleaning (Power Query): Handled data standardization and typo corrections (e.g., replacing "Fetal" with "Fatal" in the severity column) using Power Query Editor.
   
 - Data Modeling: Built a custom Calendar/Date table using DAX to support time-intelligence operations and established one-to-many relationships with the raw dataset.

 - Advanced DAX Calculations: Utilized functions like TOTALYTD, SAMEPERIODLASTYEAR, CALCULATE, and custom percentage logic to dynamically track year-to-date values and YoY growth.
   
 - Custom UI/UX Design: Integrated a custom-designed canvas background (built in PowerPoint) and customized multi-row cards, ensuring visual consistency. Added interactive slicers for Weather Conditions and Road Surfaces.
