# Agricultural Price Prediction using Deep Learning

This project aims to predict agricultural commodity prices in India using historical market data. By analyzing price fluctuations influenced by factors like seasonal variations, market demand, and climate, the system provides reliable short and mid-term price forecasts to benefit farmers, retailers, and supply chain stakeholders.

## Project Overview

- **Problem Statement:** Agricultural prices are highly volatile. This project uses historical data to build an intelligent system for price prediction with high accuracy.
- **Key Focus Areas:**
  - Analysis of historical price data.
  - Feature engineering including market and seasonal factors.
  - Using Deep Learning models (like LSTMs and GRUs) to capture long-term dependencies in time-series data.

## Dataset Description

The dataset `Price_Agriculture_commodities_Week.csv` includes wholesale prices for various commodities (e.g., Tomato, Potato, Onion, Wheat) across several Indian states and markets.

- **Columns:**
  - `State`, `District`, `Market`: Location details of the mandi.
  - `Commodity`, `Variety`, `Grade`: Specifics of the agricultural product.
  - `Arrival_Date`: Date of price recording (DD-MM-YYYY).
  - `Min Price`, `Max Price`: Traded price ranges (Rs/quintal).
  - `Modal Price`: The target variable representing the most frequent price.
- **Units:** Prices are recorded in Indian Rupees (INR) per quintal (100 kg).

## Notebook Content

The `DLWTF_MajorAssignment (2).ipynb` notebook contains the complete implementation:
1. **Exploratory Data Analysis (EDA):** Detailed visualization of price behaviors, trends, seasonality, and anomalies.
2. **Data Preprocessing:** Date conversion, sorting, and cleaning (identifying relevant features).
3. **Model Development:** Implementation of Deep Learning architectures using TensorFlow and Keras to produce reliable price predictions.

## Group 16 Contributors
- **Surajit Sahoo** (2341019165)
- **Tribhuwan Singh** (2341019538)
- **Badri Narayan Patra** (2341016251)
