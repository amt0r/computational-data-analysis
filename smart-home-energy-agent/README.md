# Smart Home Energy Agent

This is the final portfolio project, demonstrating a comprehensive simulation of a smart home energy management system.

## 📝 Overview
The "Smart Home Energy Agent" is an intelligent system that evaluates weather conditions to estimate green energy generation (solar and wind) and automatically decides whether to activate a backup gasoline generator to meet the house's energy demands.

## 🚀 Features
- **Data Generation Module:** Simulates 365 days of realistic weather data (cloud cover and wind speed) and correlates it to energy generation using linear models and wind power curves.
- **Correlation Analysis:** Analyzes the relationship between weather factors and energy output using Pearson correlation.
- **Interactive Agent:** A console-based intelligent agent that:
  - Takes a predefined weather scenario.
  - Calculates estimated solar and wind energy.
  - Compares total green energy against a fixed house demand (4.5 kW).
  - Decides to turn `ON` or `OFF` the 5 kW backup generator.
- **Visualization:** Generates scatter plots with trendlines to visualize the weather-to-energy correlation.

## 🛠️ Tech Stack
- Python
- Pandas
- NumPy
- SciPy
- Matplotlib

## 🔧 How to Run
```bash
python main.py
```
