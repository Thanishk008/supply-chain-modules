# Supply Chain Forecasting and Optimization Module

## Description

This project provides a Python module implementing two common supply chain techniques:
1.  **Moving Average Forecasting:** A simple time-series forecasting method implemented from scratch.
2.  **Transportation Linear Programming (LP):** An optimization model to find the minimum cost shipment plan between supply sources and demand destinations, using the PuLP library.

This module was developed to demonstrate the application of these quantitative methods in a scalable and reusable format.

## Requirements

To run this code, you need:
* Python 3.x
* PuLP library
* NumPy library

You can install the required libraries using pip:
```
pip install pulp numpy
```
How to Run:
Ensure you have Python and the required libraries installed.
Save the code as a Python file (e.g., supply_chain_module.py).
Run the script from your terminal:
```
python supply_chain_module.py
```
The script includes example usage for both the MovingAverageForecaster and TransportationOptimizer classes
