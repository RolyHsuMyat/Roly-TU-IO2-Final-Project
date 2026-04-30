# Roly-TU-IO2-Final-Project
Thai Airways Strategic Dashboard for fuel crsis
This README provides a comprehensive guide to the Thai Airways CEO Strategic
Command Dashboard, an AI-powered economic decision-support tool designed to
navigate pricing strategies during global supply shocks (fuel crises).

✈️ Thai Airways CEO Strategic Command Dashboard

AI-Driven Economic Insights for War-Induced Fuel Spikes

Python 3.8+ Framework Industry

📌 Project Overview

As an economist, the primary objective is to evaluate how Thai Airways should
adjust ticket prices across different customer classes (Economy, Business,
First) and route types (Domestic vs. International) in response to jet fuel
price volatility caused by current geopolitical conflicts.

The tool uses 8 different AI and Econometric models to predict demand and
provides real-time strategic recommendations to the CEO based on Price
Elasticity of Demand and the Ramsey Pricing Rule.

🛠️ Features

1. Data Simulation (Industrial Organization Theory)

The engine simulates 10,000 airline booking records based on:

  - Customer Classes: First Class (Inelastic), Business Class (Moderately
    Elastic), and Economy (Highly Elastic).
  - War Context: A dynamic Fuel_Index that spikes to simulate war shocks,
    causing cost-push inflation in ticket pricing.
  - Routes: Categorized as Domestic vs. International to observe substitution
    risks.

2. Deep Learning & Machine Learning Engine

We benchmark eight distinct architectures to find the best forecaster for
airline demand:

  - Traditional: OLS (Linear Regression), Random Forest, XGBoost.
  - Deep Learning:
      - Neural Network (MLP)
      - ANN (Artificial Neural Network - Keras)
      - RNN (Simple Recurrent Neural Network)
      - LSTM (Long Short-Term Memory) - Captures temporal trends in fuel prices.
      - 1D CNN (Convolutional Neural Network) - Identifies sudden demand shocks.

3. CEO Strategic Roadmap

An interactive simulation where the CEO can:

  - Slide a "War Scenario" Fuel Index to observe its impact.
  - Simulate a Global Price Adjustment % to see the resulting Revenue Volume.
  - Receive specific Executive Directives (e.g., "Hike International First
    prices immediately," "Avoid headline hikes for Domestic Economy").

4. Advanced Analytics & EDA

  - YData Profiling: Automatic high-fidelity data audit report.
  - Elasticity Heatmaps: Visualization of Pearson correlation between fuel
    costs, ticket prices, and passenger load.

🚀 Installation & Setup

1.  Clone the project:

    git clone https://github.com/yourusername/thai-airways-strategy-ai.git
    cd thai-airways-strategy-ai

2.  Install Dependencies:

    pip install pandas numpy plotly gradio scikit-learn xgboost tensorflow ydata-profiling statsmodels seaborn

3.  Run the Dashboard:

    python thai_airways_strategic_dashboard_for_fuel_crsis.py

📊 Technical Performance (Benchmark Summary)

The dashboard evaluates each model using MAPE (Mean Absolute Percentage Error)
and Forecast Accuracy.

| Architecture      | Advantage               | Recommended Use                        |
| :---------------- | :---------------------- | :------------------------------------- |
| **OLS**           | Highly Interpretable    | Understanding Elasticity               |
| **XGBoost**       | Extremely Fast/Accurate | Tactical Revenue Optimization          |
| **LSTM**          | Handles Volatility      | Predicting during long-term War crises |
| **Random Forest** | Robust to Outliers      | Stability during peak seasons          |

👔 Boardroom Insights

  - International First Class (ε ≈ -0.35): Inelastic segment. These customers
    value time and comfort. The CEO should pass 100% of fuel costs through a
    dedicated surcharge.
  - Domestic Economy (ε ≈ -2.25): Highly elastic segment. Direct price hikes
    lead to severe demand collapse. The strategy recommends Unbundling (charging
    separately for bags/food) rather than increasing the base fare to defend
    against Low-Cost Carrier (LCC) competition.
  - The "War Effect": Demand degradation occurs not just through pricing, but
    through the macro-environment shock simulated by the fuel index regression.

🎨 User Interface Theme

Designed with the official Thai Airways Identity:

  - Smooth Orchid (Purple): Main accents and containers.
  - Tropical Gold: Headline metrics and strategic advice highlighting.
  - Night Navy: Deep, professional dashboard background for low eye-strain.

📜 Disclaimer

This dashboard is a simulation model for educational purposes only. Data is
generated using randomized distributions grounded in 2023 airline performance
parameters to demonstrate Industrial Organization (IO) logic.



