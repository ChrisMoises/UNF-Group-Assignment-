# Solar Energy PESTEL Analysis & Forecasting (U.S.)
### 📌 Project Overview

This project analyzes the growth of solar energy generation in the United States using a PESTEL framework (Political, Economic, Environmental) and applies time-series forecasting (SARIMA) to predict future trends.

The objective is to identify key drivers of solar energy expansion and provide data-driven strategic insights for decision-makers.

#### 🎯 Objectives

- Analyze historical solar energy generation (2015–2024)

- Identify key external drivers (PESTEL factors)

- Explore relationships between economic and environmental variables

- Forecast solar generation for 2025

- Provide strategic recommendations

#### 📊 Dataset

Frequency: Monthly

Time Range: 2015–2024

Unit of Analysis: United States

Key Variables:

- Solar Electricity Generation (MW)

- Investment (Billion USD)

- Electricity Price (USD/kWh)

- CO₂ Emissions

- Temperature (°F)

- Precipitation (mm)

#### 🧠 Methodology
1. Data Preparation

- Data cleaning and transformation

- Time index creation

- Handling missing values and outliers

2. Exploratory Data Analysis (EDA)

- Distribution analysis

- Trend visualization

- Seasonality detection

3. Statistical Analysis

- Correlation analysis

- Regression modeling

4. Time-Series Modeling

- Stationarity testing (ADF test)

- ARIMA model

- SARIMA model (main model)

#### 🔮 Forecasting Approach

The SARIMA model was selected because solar generation exhibits:

- Strong upward trend

- Clear seasonal cycles

#### 📅 Forecast horizon:
2025 (12 months)

#### 📈 Key Insights

- Solar energy generation has grown significantly over the past decade

- Strong seasonal patterns (summer peaks, winter declines)

- Investment and electricity prices are key drivers of growth

- Environmental conditions influence solar output

- Solar expansion contributes to emissions reduction

#### ⚠️ Limitations

- National-level aggregation (no regional breakdown)

- Limited time horizon

- External shocks not explicitly modeled

#### 🚀 Strategic Recommendations

- Invest in grid infrastructure to support future capacity

- Maintain policy incentives for renewable energy

- Expand energy storage solutions

- Improve climate-based forecasting systems

#### 📊 Dashboard

An interactive dashboard was developed in Power BI to visualize:

- Solar generation trends

- PESTEL drivers

- Forecast scenarios

📁 File: /dashboard/Solar_PESTEL_Dashboard.pbix

#### 🛠️ Technologies Used

Python (Pandas, NumPy, Matplotlib, Seaborn)

Statsmodels (ARIMA, SARIMA)

Power BI

Jupyter Notebook

📂 How to Run

Clone the repository:

git clone https://github.com/ChrisMoises/UNF-Group-Assignment-.git


Install dependencies:

pip install -r requirements.txt


Run the notebook:

jupyter notebook Solar-PESTEL-Forecasting.ipynb

### 📌 Author

Cristhian Moises Martínez Alay

Daniel Olmedo Zapata Gaibor

María Alejandra Boada Rodríguez

Viviana Rivera Lozano 

Yovanni Rojas Cardona  
