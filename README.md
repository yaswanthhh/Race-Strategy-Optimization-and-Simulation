# Race-Strategy-Optimization-and-Simulation
An interactive Python application for simulating and optimizing Formula 1 race strategies using machine learning, and real-time telemetry data.

# F1 Race Strategy Simulator and Optimizer

An interactive Python application to simulate, analyze, and optimize Formula 1 race strategies using machine learning, Bayesian optimization, and real telemetry data.

## Project Overview

This project models Formula 1 race dynamics by predicting lap times based on tire compounds, fuel load, and degradation. It incorporates safety car effects and fuel strategies to realistically simulate race scenarios. The platform offers an interactive Streamlit dashboard that allows users to manually specify strategies or run automatic optimization to find the best pit stop laps and tire choices to minimize total race time.

## Key Features

- **Machine Learning Model:** XGBoost regressor trained on official F1 telemetry data to predict lap times.
- **Bayesian Optimization:** Automated optimization of pit stops, tire compounds, and degradation parameters.
- **Dynamic Simulation:** Models exponential tire degradation, fuel load effects, and compounds strategy.
- **Safety Car Integration:** Allows inclusion of safety car laps altering race pace and pit stop penalties.
- **Interactive Dashboard:** User-friendly interface built with Streamlit for parameter tuning, simulation, and visualization.
- **Multi-Strategy Comparison:** Test, compare, and visualize multiple strategies side-by-side.
- **Strategy Persistence:** Save and load strategies through JSON files for collaboration and workflow continuity.
- Adjust global parameters such as tire degradation (`alpha`, `beta`), pit stop times, and safety car laps via sidebar.
- Define up to three race strategies with customizable pit stop laps and tire compounds.
- Run simulations or Bayesian optimizations individually to explore strategy impacts.
- Visualize lap times, pit stops, safety car periods, and stint summaries interactively.

## Example Screenshots
<img width="2293" height="1313" alt="image" src="https://github.com/user-attachments/assets/762f190d-68fc-4e10-aa01-3e4fe17fd939" />

<img width="1258" height="1168" alt="image" src="https://github.com/user-attachments/assets/08205140-aefd-408d-b4eb-309e2e38a16f" />

## Contact

Yaswanth Udayakumar – yaswanthudayakumar1@gmail.com  
Project Link: [https://github.com/yourusername/f1-race-strategy-simulator](https://github.com/yaswanthhh/Race-Strategy-Optimization-and-Simulation)

---

*Developed as part of a data-driven motorsports analytics portfolio project.*
