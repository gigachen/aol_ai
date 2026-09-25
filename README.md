# StockSense: Restaurant Inventory Intelligence

## Overview

**StockSense** is a restaurant inventory intelligence web application developed as a **3-person group project for an Artificial Intelligence course**. The system uses historical sales data to forecast future dish demand and turn those predictions into ingredient stock recommendations.

## Project Information

- **Type:** AI & Web Application · Course Project
- **Course:** Artificial Intelligence
- **Format:** Group Project · 3 members

## Key Features

- Restaurant dashboard
- Menu management
- Pantry inventory management
- Ingredient management
- Sales CSV upload and processing
- AI-based sales forecasting
- Ingredient requirement calculation
- Purchase recommendations based on predicted demand
- Forecast and sales-data export

## AI Implementation

The application uses **Random Forest Regression** to forecast daily sales for individual dishes.

The pipeline:
1. Processes historical sales data by dish and date.
2. Creates time-based features and a 7-day historical sales average.
3. Trains a Random Forest regression model for each dish.
4. Forecasts sales for a selected number of future days.
5. Converts predicted dish demand into estimated ingredient requirements.
6. Compares requirements with current pantry stock to identify ingredients that may need to be purchased.

## My Role

I focused on the **concept, web development, and AI-to-web integration**.

- Developed the overall project concept.
- Built the web interface and its main pages.
- Integrated the AI forecasting pipeline into the web application.
- Connected the forecasting output to ingredient requirement and recommendation features.

## Tech Stack

**Web:** PHP · HTML · CSS · JavaScript · Tailwind CSS · Chart.js

**AI / Data:** Python · Pandas · NumPy · Scikit-learn · Random Forest Regression · Matplotlib

## Outcome

A completed course project that combines an AI forecasting pipeline with a web-based restaurant inventory workflow, allowing users to move from sales data to demand forecasts and ingredient purchase recommendations.

## Portfolio Card

**StockSense — Restaurant Inventory Intelligence**  
*Artificial Intelligence · Web Application · Group Project*

An AI-powered restaurant inventory web application that forecasts dish demand from historical sales and translates predictions into ingredient stock recommendations.
