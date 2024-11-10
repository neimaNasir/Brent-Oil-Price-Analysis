# BrentOilPriceAnalysis

## Overview
This repository contains an analysis of Brent oil prices, focusing on the effects of significant political and economic events over the past decade. By utilizing statistical models and change point analysis, this project provides insights that can guide decision-making for investors, analysts, and policymakers.

## Background
The Brent oil market is known for its volatility, with prices heavily influenced by geopolitical events, economic sanctions, OPEC policy shifts, and technological advancements. This project aims to model these factors, offering a data-driven approach to understanding market fluctuations.

## Objectives
1. **Define the Data Analysis Workflow:**
   - Steps for analyzing Brent oil prices
   - Understand data sources and compilation methods
   - Identify model inputs, parameters, and outputs

2. **Understand the Model and Data:**
   - Explore suitable time series models
   - Explain purpose and application of chosen models

3. **Analyze Brent Oil Prices:**
   - Measure the impact of major events on price trends
   - Examine additional factors like economic indicators

4. **Develop an Interactive Dashboard:**
   - Visualize results and enable stakeholders to explore data dynamics

## Data Collection
The dataset includes historical Brent oil prices from May 20, 1987, to September 30, 2022, along with notable events impacting oil prices. Key data sources include:
- Financial databases
- World Bank
- IMF
- IEA

## Data Preprocessing
Data cleaning was performed to handle missing values, remove outliers, and standardize date formatting and price representation for consistency.

## Exploratory Data Analysis (EDA)
EDA was conducted to identify trends, correlations, and anomalies. Visualizations helped to understand the relationship between oil prices and significant global events.

## Model Selection and Implementation
The following models were selected for analysis:
- **ARIMA**: For capturing trends and seasonality
- **GARCH**: To model and forecast price volatility
- **VAR**: For multivariate analysis, including economic indicators
- **LSTM**: To capture complex sequential data patterns

## Analysis of Results
Model performance was evaluated using metrics like RMSE and MAE. The analysis highlighted the impact of geopolitical and economic events on oil price trends.

## Communication of Findings
An interactive dashboard was developed using Flask (backend) and React (frontend) to visualize analysis results, allowing stakeholders to explore correlations between events and Brent oil prices dynamically.

## Expected Outputs and Limitations
### Expected Outputs
- Actionable insights on how events influence oil prices
- Predictive analytics to aid strategic decision-making

### Limitations
- Data quality and availability may impact the results
- Unforeseen events might produce patterns not captured in historical data

## Installation

To get started with the project:

1. **Clone the repository**:

    ```
    git clone https://github.com/neimaNasir/Brent-Oil-Price-Analysis.git
    cd BrentOilPriceAnalysis
    ```

2. **Set up a virtual environment** 

    ```
    python -m venv .venv
    source .venv/bin/activate       
    .venv\Scripts\activate          
    ```

3. **Install required packages**:

    ```
    pip install -r requirements.txt
    ```

## Usage
Run the analysis scripts to generate insights and visualizations. For the dashboard, navigate to the frontend directory and start the React application:
   
    ```
    cd frontend
    npm start
    ```

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

