# Chipotle Pricing Optimization: Analyzing Guacamole Prices Across the U.S.

## 📊 Overview

This project focuses on analyzing and visualizing guacamole price variations across 3,000+ Chipotle outlets in the U.S. by integrating data from the official Chipotle website, USDA ingredient pricing records, and the Hass Avocado Board. The goal is to understand regional price dynamics and model the relationship between ingredient prices and final guacamole pricing using machine learning.

---

## 🧩 Problem Statement

Guacamole, a staple Chipotle item, exhibits inconsistent pricing across different locations. This project aims to:

- Understand how ingredient costs affect guacamole prices.
- Build predictive models to anticipate price fluctuations.
- Offer insights for pricing strategy and optimization.

---

## 🥑 Ingredients Analyzed

- Avocados  
- Cilantro  
- Jalapeños  
- Lemons  
- Limes  
- Onions

---

## 🗂️ Data Sources

1. **Chipotle Website**: Menu prices & store locations via web scraping.
2. **USDA Website**: Historical daily ingredient prices via Selenium automation.
3. **Hass Avocado Board**: CSV with regional avocado prices.

---

## 🛠️ Data Processing

- **Preprocessing**: Handling nulls, duplicates, inconsistent units (e.g., converting to pounds), and merging multiple datasets.
- **Imputation**: Filling missing date/city values using forward fill and geographic proximity.
- **Standardization**: Ensuring consistent formats for dates, units, and locations.

---

## 📉 Data Visualization

### Tableau Dashboards:

- [Avocado Price Variations](https://public.tableau.com/views/Group_5_Project/WeeklyTop10AvocadoPricesVariationPerCity)
- [Guacamole Price Variation Map](https://public.tableau.com/views/Group_5_Project/ChipotlesGuacmolePriceVariation)

### Python Graphs:

- Ingredient price trends  
- Correlation heatmaps  
- Animated price fluctuations over time  

---

## 🤖 Machine Learning Model

### Objective:
Forecast ingredient prices using regression models and correlate them to guacamole pricing.

### Techniques Used:
- Linear Regression  
- Ridge Regression  
- Random Forest Regressor  

### Evaluation Metrics:
- Mean Absolute Error (MAE)  
- Mean Squared Error (MSE)  

### Results:
Random Forest generally yielded the lowest error; however, Ridge performed better on non-imputed datasets.

---

## ⚠️ Limitations

- Lack of direct historical guacamole price data.
- Heavy imputation of missing values.
- Assumptions in weight conversions and city mappings.

---

## 🚀 Future Work

- Forecasting guacamole prices directly with enhanced historical data.
- Expanding the model to other dishes on the Chipotle menu.

---

## 📁 Project Structure
├── data/ # Raw and processed datasets
├── notebooks/ # Jupyter notebooks for analysis & modeling
├── dashboards/ # Tableau dashboard links
├── src/ # Scripts for scraping, preprocessing, modeling
├── README.md # Project documentation


---

## 📬 Contact

Project by: [Vaishnavi Mocherla](https://github.com/Vaishnavi-mocherla)  
For questions or feedback, feel free to reach out via GitHub Issues.

