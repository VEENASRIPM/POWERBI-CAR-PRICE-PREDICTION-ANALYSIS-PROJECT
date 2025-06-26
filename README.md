# CAR PRICE PREDICTION ANALYSIS - POWER BI

## Project Overview

This Power BI project performs a comprehensive analysis on car-related data to identify trends, understand performance, and explore the key factors that influence car pricing. The goal is to uncover actionable insights to support data-driven pricing decisions for stakeholders in the automotive industry.

---

## Objective

To analyze car price data using Power BI dashboards and uncover insights related to brand, fuel type, transmission, mileage, engine size, and condition, enabling better pricing strategies and future predictive modeling.

---

## Scope of Analysis

- Explore relationships between car attributes and pricing
- Identify top predictors of car price
- Visualize price variation across:
  - Brands (Luxury vs. Economy)
  - Transmission types
  - Fuel types
  - Vehicle conditions (New, Used, Like New)
  - Year and mileage
- Spot outliers and anomalies in pricing
- Support predictive modeling and strategic decision-making

---

## Target Audience

- Data analysts building car price prediction models  
- Sales and marketing teams analyzing trends  
- Dealers optimizing pricing strategies  
- Used car sellers assessing fair value  
- Auto industry researchers and strategists

---

## Dataset Summary

- **Total Records**: 2,500  
- **Features**:
  - Car ID, Brand, Model
  - Year (2000–2023)
  - Engine Size
  - Fuel Type (Hybrid, Petrol, Electric, Diesel)
  - Transmission (Automatic, Manual)
  - Condition (Used, New, Like New)
  - Mileage
  - Price  
- **Brand Categories**: Luxury, Economy

---

## Data Cleaning

- Verified and corrected data types  
- Removed duplicates using Power BI's "Remove Duplicates"  
- Clean and structured dataset prepared for analysis  

---

## Measures & DAX Calculations

### Measures:
- Average, Max, Min: Price, Mileage, Engine Size
- Price by Brand
- Price per Kilometer
- Car Count by Transmission
- Count by Decade

### Calculated Columns:
- **Recommendation** (based on Price vs. Mileage):
  - High Price & High Mileage → Least Preferred
  - High Price & Low Mileage → Acceptable
  - Low Price & High Mileage → Considerable
  - Low Price & Low Mileage → Highly Preferred
- **Brand Category**: Custom column for Luxury vs. Economy

---

## Power BI Dashboards & Analysis

### Key Visuals:
- **Price vs. Brand Category**  
- **Price vs. Brand & Transmission**  
- **Price vs. Fuel Type & Condition**  
- **Price vs. Year**  
- **Mileage vs. Brand**  
- **Engine Size vs. Fuel Type**  
- **Price vs. Condition & Mileage**  
- **Price vs. Transmission**  
- **Recommendation Count by Year**  

### Filters and Slicers:
- Interactive exploration of features (year, brand, fuel type, condition)

### KPIs:
- Total Sales
- Avg. Price
- Avg. Mileage
- Count of Vehicles

---

## Insights

- Luxury brands have higher counts and prices than economy brands  
- Automatic cars priced slightly higher than manual ones (~$50k difference)  
- Ford maintains price stability across both transmission types  
- Like New cars have the highest price and mileage  
- Electric cars: higher engine size, but lower mileage  
- BMW maintains consistent pricing regardless of condition  
- 2005 had highest sales; 2020 had lowest due to pandemic impact  

---

## Conclusion

The analysis highlights how attributes like **brand**, **engine size**, **mileage**, and **condition** affect car prices. Pricing is dynamic, influenced by multiple market and consumer-related factors.

---

## Recommendations

- Include brand strength and resale value context  
- Add data on safety features and amenities  
- Capture customer preferences and geographic effects  
- Focus on promoting newer, fuel-efficient automatic cars  

---

## PRESENTED BY

**VEENA SRI P M**  
*Data Analytics and Data Science*

---
