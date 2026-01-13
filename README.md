# Stop Selling Cars, Start Selling SUVs

### New Vehicle Sales Exploratory Data Analysis

**Author:** Aidan Daley
**Date:** August 18, 2025

## Overview

This project analyzes new vehicle sales data (2023–2025) sourced from Cars.com to identify **consumer purchasing trends that maximize dealership revenue**. Using exploratory data analysis (EDA), the project examines which vehicle characteristics—such as body type, drivetrain, fuel type, color, make, and price—are statistically most likely to sell.

The analysis culminates in **actionable inventory recommendations** for car dealerships seeking faster inventory turnover and higher profit margins.

## Business Problem

Car dealerships operate in a highly competitive environment where inventory decisions directly affect revenue and sales commissions. Stocking vehicles that do not align with consumer demand leads to slower turnover and opportunity cost.

**Objective:**
Determine which vehicle types and attributes customers are most likely to purchase, enabling dealerships to optimize inventory strategy for 2025.

## Dataset

* **Source:** “Vehicle Dataset 2024” (Cars.com, collected via Apify, published on Kaggle)
* **Entries:** 1,002 vehicles
* **Timeframe:** New vehicles (2023–2025)
* **Features (18):**

  * Make, model, year, price
  * Body type, drivetrain, fuel type
  * Exterior & interior color
  * Transmission, engine, trim
  * Doors, cylinders, mileage

The dataset was **ethically collected** and complies with Cars.com’s terms of service.

## Methodology

* Conducted **exploratory data analysis (EDA)** using summary statistics and visualizations
* Focused on **consumer-controlled purchase decisions**, including:

  * Body type
  * Make & model
  * Price range
  * Drivetrain
  * Fuel type
  * Interior & exterior color
* Excluded features with minimal dealership influence (e.g., cylinders, doors)
* Excluded mileage and year due to focus on new vehicles

## Key Findings

### Pricing Trends

* **Median price:** $46,835
* **Interquartile range (IQR):** $22,827
* Majority of sales occur between **$20,000–$60,000**
* Demand sharply declines above $60,000, indicating sensitivity to luxury pricing

### Vehicle Type Demand

* **SUVs:** 69.26% of all sales
* **Trucks:** 17.88%
* **Sedans:** 6.24%

**SUVs and Trucks account for ~87% of all vehicle sales**, demonstrating overwhelming consumer preference.

### Make Popularity

Top-selling manufacturers:

1. Jeep (21.24%)
2. Dodge (12.60%)
3. Hyundai (9.96%)
4. RAM (9.12%)
5. Ford (7.92%)

These brands are predominantly associated with **SUVs and trucks**, reinforcing body-type demand trends.

### Drivetrain & Fuel Preferences

* **All-Wheel Drive (AWD):** 44.90%
* **Four-Wheel Drive (4WD):** 42.42%
* **Gasoline vehicles:** 72.58% of SUV and truck purchases
* Hybrids represent a smaller but notable segment (15.97%)

### Color Preferences

* **Interior:** Black (74.38%)
* **Exterior:** Neutral colors dominate

  * White: 25.89%
  * Black: 18.59%

Consumers show a strong preference for **low-risk, neutral aesthetics**.

## Business Recommendations

Based on the analysis, dealerships should:

* Prioritize **SUV and truck inventory**
* Focus on **AWD and 4WD configurations**
* Stock primarily **gasoline-powered vehicles**
* Emphasize **neutral exterior and interior colors**
* Concentrate inventory pricing between **$20,000–$60,000**
* Allocate inventory toward **Jeep, Dodge, Hyundai, RAM, and Ford**

Following this strategy aligns inventory with statistically proven demand, increasing turnover speed and overall revenue.

## Tools & Skills Demonstrated

* Exploratory Data Analysis (EDA)
* Data visualization & descriptive statistics
* Business-driven analytical thinking
* Data cleaning and feature selection
* Translating data insights into strategic recommendations

## Future Improvements

* Incorporate **time-series analysis** to detect evolving trends
* Compare regional demand differences
* Extend analysis to include **profit margins** by vehicle type
* Integrate predictive modeling for sales forecasting
