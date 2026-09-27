# Revenue Time Series Analysis

This project focuses on time series analysis and performance optimization when working with large datasets in Python.

## 📝 Overview
The goal of this project is to generate a large synthetic daily revenue dataset (over 100,000 records) and compare the execution time of calculating a 7-day rolling mean using two different approaches.

## 🚀 Features
- **Data Generation:** Creates synthetic daily revenue time series data using Pandas and NumPy.
- **Pandas Method:** Calculates the rolling mean using the standard built-in `df.rolling().mean()` method.
- **NumPy Method:** Calculates the rolling mean using an optimized array-based cumulative sum (`cumsum`) approach.
- **Performance Benchmarking:** Measures and compares the execution times of both methods to highlight the performance benefits of vectorized operations.

## 🛠️ Tech Stack
- Python
- Pandas
- NumPy
- Time (for benchmarking)

## 🔧 How to Run
```bash
python main.py
```
