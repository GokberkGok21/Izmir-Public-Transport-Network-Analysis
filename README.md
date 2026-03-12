# 🚌 Machine Learning for Urban Mobility: Izmir Transport Analysis

This project utilizes advanced **Machine Learning (ML)** and **Causal Inference** techniques to evaluate the impact of infrastructure changes and digital transformation on Izmir’s public transport ecosystem.

## 🤖 Machine Learning & Methodology
The core of this project relies on a **Counterfactual Analysis** framework, treating the infrastructure launch as an experimental intervention:
- **Baseline Modeling:** Trained predictive models on historical transit data (ESHOT, Metro, Izdeniz) to forecast "what would have happened" without the Narlıdere Metro expansion.
- **Causal Inference:** By comparing ML-generated baselines against actual observed data, we isolated the true impact of the infrastructure change, removing external noise and seasonal trends.
- **Trend Prediction:** Used time-series analysis to identify shifts in passenger behavior following service frequency optimizations (8-minute headway).

## 📊 Key Analytical Insights
- **Infrastructure Shift:** The ML model confirmed a **3.46% increase** in Metro dominance over the bus network (ESHOT) directly attributable to the Narlıdere line extension.
- **Digital Transformation Analysis:** Identified the "Cannibalization Effect" where contactless credit card and QR payment adoption led to a measurable decline in physical ticket sales, modeled through adoption-rate analytics.
- **Fleet Optimization:** Provided data-driven recommendations for bus route re-allocation based on predicted transit demand shifts.

## 🛠 Tech Stack
- **Languages & Libraries:** Python (Pandas, Scikit-learn, Statsmodels)
- **ML Techniques:** Time-Series Forecasting, Causal Impact Analysis, Regression Modeling
- **Visualization:** Seaborn, Plotly for dynamic mobility heatmaps
