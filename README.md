# F1 Race Strategy Optimizer & Performance Analysis

This repository contains a comprehensive toolkit for Formula 1 data analysis, featuring advanced tire wear modeling, Monte Carlo race simulation, and interactive performance dashboards. Built with Python, `fastf1`, and `scikit-learn`, this project turns raw race data into actionable strategic insights.

## ✨ Key Features

-   **🏎️ Data Loading & Processing**: Automatically fetches and preprocesses official F1 timing data, including laps, stints, and pit stops, for any race weekend.
-   **📊 Tire Degradation Modeling**:
    -   Fits both linear and polynomial regression models to analyze tire performance.
    -   Calculates degradation rates (s/lap), R² scores, and Mean Absolute Error (MAE) for each compound.
    -   Provides detailed summaries and visualizations of tire wear for specific drivers and compounds.
-   **🕹️ Monte Carlo Race Simulator**:
    -   Simulates entire race outcomes based on different pit stop strategies (0-stop, 1-stop, 2-stop).
    -   Models complex variables like weather impact, pit loss, track evolution, and safety car probability.
    -   Identifies the optimal strategy by comparing thousands of simulated race results.
-   **📈 Interactive Visualization Dashboards**:
    -   **Pace Analysis**: Compare a driver's lap times, stint performance, and sector times against model predictions.
    -   **Strategy Comparison**: Visualize the effectiveness of different pit stop strategies by comparing cumulative race times.
    -   **Advanced Analytics**: Explore championship standings, driver consistency, position changes, and overall tire usage in detailed dashboards.
-   **🤖 Machine Learning Predictor**:
    -   Utilizes a **Random Forest Regressor** to predict lap times based on key features like lap number, tire age, and stint progress.
    -   Analyzes feature importance to identify the biggest factors influencing lap time.

## 🛠️ Installation

To run this project, you will need Python 3.

