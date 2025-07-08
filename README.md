# Automatic-Pricing-and-Replenishment-Model-for-Vegetables

Project Description
This repository contains a model developed to optimize the pricing and replenishment strategies for vegetable products in a supermarket, leveraging sales data and demand analysis.     The model applies ARIMA time series forecasting, Kendall consistency tests, and Particle Swarm Optimization (PSO) to predict sales and optimize replenishment while maximizing profitability.

The primary objectives of this project are:
Sales Distribution and Relationship Analysis: Analyzing the sales patterns and correlations across different vegetable categories and individual products.
Replenishment and Pricing Strategy: Calculating daily replenishment and pricing strategies to maximize supermarket profit for the week of July 1-7, 2023.
Product-Level Replenishment: Developing a replenishment plan for individual products, while adhering to constraints such as maintaining the total number of available products between 27 and 33, and ensuring a minimum stocking quantity.

Data Recommendations: Identifying additional data that can further improve replenishment and pricing decision-making.

Data Overview
The data includes the following files:
Vegetable Category Information: Contains the list of vegetable categories.
Sales Detail Data: Includes detailed sales transactions from July 1, 2020, to June 30, 2023.
Wholesale Price Data: Provides the wholesale prices of the vegetables.
Loss Rate Data: Contains the loss rates associated with each vegetable category.

Methodology
Sales Analysis: The data is grouped by daily, monthly, and category-level sales.     Visualization techniques like heatmaps, bubble charts, and scatter plots were used to analyze sales distributions.
ARIMA Model: For forecasting future sales, an ARIMA time series model is fitted to the historical sales data.     The model provides sales predictions for the week of July 1-7, 2023, to guide pricing and replenishment decisions.
Particle Swarm Optimization (PSO): This multi-objective optimization model is employed to balance product replenishment quantity and maximizing profits, considering constraints such as the number of available products and minimum stocking quantities.

Key Insights
Sales Distribution: Analyzed the sales data to reveal the top-performing vegetable categories and their respective sales trends.     Certain vegetable categories, such as "Flowering Vegetables," exhibit high sales frequency and volume.
Pricing and Replenishment Optimization: By combining historical sales data and forecasting models, the project generates an optimal replenishment and pricing strategy for the upcoming week.
Data Enhancements: Recommendations include acquiring additional data related to the supply chain, customer preferences, and competitor strategies to enhance future decision-making.

Files Included
Product information of 6 vegetable categories.xlsx
Recent Loss rate of vegetable products.xlsx
Sales Transaction Details Data.xlsx
Wholesale Prices of vegetable products.xlsx
The paper "Vegetable Automatic Pricing and Replenishment Model Based on Sales Volume and Demand Analysis"

Future Work
Model Enhancement: Future work could involve comparing ARIMA with other time series models (e.g., LSTM) to identify the most accurate forecasting method.
Real-time Data: Incorporating real-time data and adjusting strategies dynamically could further optimize the replenishment and pricing process.

License
This project is licensed under the MIT License - see the LICENSE file for details.
