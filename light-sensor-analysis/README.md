# Smart Home Light Sensor Analysis

This project analyzes IoT sensor data to evaluate the efficiency of smart home lighting systems.

## 📝 Overview
By processing time-series data from a light sensor (`Light.csv`), the project calculates illuminance levels at specific intervals and assesses the energy efficiency of artificial lighting compared to natural daylight.

## 🚀 Features
- **Data Processing:** Reads and parses CSV sensor data containing timestamps and illuminance (lux) values.
- **Efficiency Calculation:** 
  - Compares light levels across different states (e.g., lamp on/off, curtains open/closed).
  - Calculates the percentage of illumination provided by natural daylight versus the artificial lamp.
- **Data Visualization:** Generates an annotated area plot showing illuminance over time, with markers indicating specific test intervals.

## 🛠️ Tech Stack
- Python
- Pandas
- Matplotlib
- Seaborn

## 🔧 How to Run
```bash
python pz.py
```
