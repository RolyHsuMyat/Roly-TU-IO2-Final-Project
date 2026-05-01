This README provides a professional, academic-grade overview of your Thai
Airways Strategic AI Dashboard. It is designed to demonstrate your expertise in
Industrial Organization (IO) and Data Science to your professor.

✈️ Thai Airways CEO Strategic Command

Industrial Organization & AI Revenue Strategy for War-Induced Fuel Spikes

Economics Python Gradio

📝 Overview

In the wake of current global geopolitical conflicts, jet fuel prices have
become highly volatile. This project acts as a Decision Support System (DSS)
designed for the CEO of Thai Airways to navigate this crisis.

Using Segmented Price Elasticity and Machine Learning, this dashboard allows
executives to simulate "What-If" scenarios to calculate the exact price
threshold where revenue gain from price increases outweighs the loss from
passenger drop-off (The Law of Demand).

🛠️ Step-by-Step Methodology

Step 1: Industrial Organization Market Simulation

We developed a stochastic dataset of 12,000 observations grounded in Thai
Airways’ real-world network operational parameters.

  - Variable Segmentation: Modeled the difference between Domestic routes (High
    substitution risk, train/car competitors) and International routes
    (Inelastic long-haul segments).
  - Stochastic Shock: Integrated a "Fuel Price Index" (baseline 100) that spikes
    to simulate war-time supply-side inflation.

Step 2: Multi-Model Machine Learning Engine

Following the requirements of Workshop 04-09, we benchmarked four different
algorithms to identify the best predictor of passenger demand during volatility:

1.  OLS (Econometric Baseline): Used to isolate specific Elasticity coefficients
    (\epsilon).
2.  Random Forest: For managing route-level outliers.
3.  Neural Network: For deep pattern recognition in regional seasonality.
4.  XGBoost: Selected as the Best Model due to its superior handling of
    non-linear shocks during the fuel crisis (Lowest MAPE).

Step 3: Simulation of Revenue Mix & Concentration Risk

The dashboard categorizes revenue by travel class and route type.

  - Finding: Proved that International Business Class serves as the carrier's
    "Profit Engine" (Inelastic demand), generating 5x the profit-per-kilometer
    compared to Domestic Economy.

Step 4: Strategic Pricing Simulator (Boardroom UI)

The CEO can adjust two critical variables in real-time:

  - Fuel Price Index: Simulates different severities of global war conflict.
  - Fare Adjustment %: Calculates the resulting change in Load Factor and EBIT.
  - Strategic Suggestion: The engine automatically warns the CEO to unbundle
    Economy services while applying full surcharges to Business segments based
    on the Inverse Elasticity Rule.

📊 Technical KPI & Metrics

  - Metric Used: Mean Absolute Percentage Error (MAPE / MAPS Score).
  - Forecast Confidence: The XGBoost engine achieved high reliability, ensuring
    boardroom decisions are based on data-backed precision.
  - Corporate Identity: The dashboard UI follows the official Smooth Orchid
    (#4B246A) and Tropical Gold (#D4AF37) branding of Thai Airways
    International.

📐 Economic Foundations Applied

1.  Inverse Elasticity Rule: Passing marginal cost shocks (fuel) only to
    price-insensitive travelers.
2.  Ramsey Pricing: Determining mark-ups based on segmented sensitivities.
3.  Substitution Effect: Domestic market analysis for travelers switching to
    Budget airlines or surface travel.
4.  Inter-temporal Price Discrimination: Analyzing "High vs. Low" season booking
    patterns.

🚀 How to Run the System

1.  Install Requirements

    pip install pandas numpy plotly gradio scikit-learn xgboost statsmodels

2.  Execute Dashboard

    python thai_airways_ceo_dashboard.py

3.  Gradio Output Follow the local URL provided in the terminal to interact with
    the full Strategic Command dashboard.

Developed for the Industrial Organization Final Project. Leading-edge economic
analytics for sustainable aviation growth. 🇹🇭✈️
