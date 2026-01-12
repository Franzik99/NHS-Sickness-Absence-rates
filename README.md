# NHS-Sickness-Absence-Rates
**Project Date : 02 t0 12th January 2026**
## Background
This project analyses and forecasts NHS workforce sickness absence trends using official NHS Digital data. The objective is to understand long-term patterns, 
seasonality, and structural changes in absence rates, and to build predictive insights that can support workforce planning and cost optimisation. 
Using historical monthly data from 2009–2025, the project applies data cleaning, exploratory analysis, regression modelling, and time-series techniques to 
separate trend, seasonality, and residual components. The results demonstrate clear seasonal effects and a sustained increase in sickness absence following 
the COVID-19 period, highlighting the importance of data-driven workforce forecasting.

## Project Workflow / Steps Involved
- **Data Sourcing** : 
  Collected official monthly NHS sickness absence data from NHS Digital (2009–2025).

- Data Cleaning & Preparation : 
Transformed publication-style Excel tables into analysis-ready datasets by removing metadata rows, standardising column names, converting dates, and handling missing values.

- Exploratory Data Analysis (EDA) : 
Analysed trends and seasonality using visualisations to identify recurring winter spikes and long-term structural changes.

- Trend Modelling (Regression) : 
Applied linear regression to quantify long-term growth in sickness absence rates and establish a baseline trend.

- Time-Series Decomposition : 
Decomposed the series into trend, seasonal, and residual components to isolate cyclical effects.

- Forecasting : 
Built and evaluated time-series forecasting models to predict future sickness absence rates.

- Interpretation & Insights : 
Translated analytical results into clear insights relevant to workforce planning and operational decision-making.

## Key Results & Insights
- Identified strong and consistent seasonality, with absence rates peaking during winter months.

- Detected a structural increase in sickness absence post-2020, with levels remaining above pre-COVID baselines.

- Regression analysis confirmed a long-term upward trend in absence rates across England.

- Forecasting results suggest continued elevated absence levels if current patterns persist, reinforcing the need for proactive workforce planning.

## Programming & Analysis:

* Python

**Libraries:**

* Pandas (data manipulation and cleaning)
* NumPy (numerical operations)
* Matplotlib (visualisation)
* Statsmodels (time-series decomposition and forecasting)
* Scikit-learn (regression modelling)

**Data Source:**

* NHS Digital – NHS Sickness Absence Rates (monthly data)


