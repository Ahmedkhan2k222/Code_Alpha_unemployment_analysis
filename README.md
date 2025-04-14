# Code_Alpha
# 📊 Unemployment Rate Analysis in India

This project presents a comprehensive analysis of unemployment trends across different regions of India using time-series data. Through data preprocessing, visualization, and statistical exploration, we aim to understand the patterns and relationships within India’s labor market from both temporal and regional perspectives.

---

## 📁 Dataset Description

The dataset includes monthly observations with the following attributes:

- **Region** – Indian states and union territories.
- **Date** – Date of record in day-month-year format.
- **Estimated Unemployment Rate (%)**
- **Estimated Employed**
- **Estimated Labour Participation Rate (%)**
- **Area** – Categorized as Urban or Rural.

---

## 🔧 Data Preparation

- Removed extra spaces from column headers.
- Converted the `Date` column into proper datetime format.
- Dropped rows with missing values to maintain data quality.
- Extracted `Year` and `Month` for deeper temporal analysis.

---

## 📊 Visual Analysis Overview

1. **Unemployment Rate Over Time**  
   Visualized unemployment trends across all regions to observe fluctuations, trends, and seasonal patterns.

2. **Average Unemployment by Region**  
   Compared the average unemployment rates per region to highlight areas with consistently high or low unemployment.

3. **Labour Participation vs. Unemployment**  
   Investigated the relationship between labor force activity and unemployment rates using a scatter plot.

4. **Distribution of Unemployment Rates**  
   Explored regional variations and outliers using box plots for each region.

5. **Correlation Heatmap**  
   Examined statistical relationships between numeric features such as employment levels and participation rates.

---

## 🔍 Key Insights

- **Regional Disparities**: Some regions exhibit significantly higher average unemployment rates, indicating regional economic challenges.
- **Labor Participation Relationship**: In several regions, higher labor participation does not necessarily correspond with lower unemployment, suggesting structural issues in job availability.
- **Variability Across Regions**: The distribution of unemployment rates differs widely, with some regions experiencing more consistent rates while others show high volatility.
- **Strong Correlations**: Notable correlations exist between labor participation, employment levels, and unemployment, which could be useful for forecasting or economic policy planning.

---

## 🧾 Summary

This project successfully demonstrates how visual analytics can uncover meaningful insights from labor market data. By analyzing unemployment trends across regions and over time, we provide a clearer understanding of employment challenges in India. These findings can support data-driven decision-making for policymakers, economists, and researchers aiming to improve job creation and labor market efficiency.
