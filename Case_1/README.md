# Reservoir Production Prediction using Machine Learning

This project aims to predict reservoir fluid production using machine learning techniques based on petrophysical and geophysical features from well log data.

## Dataset Description

The dataset contains the following features:

| Feature     | Description                                                                 |
|-------------|-----------------------------------------------------------------------------|
| `WellIndex` | Unique identifier for each well sample                                      |
| `Por`       | **Porosity** – the percentage of void space in the rock that can contain fluids |
| `LogPerm`   | **Logarithm of Permeability** – ability of rock to transmit fluids          |
| `AI`        | **Acoustic Impedance** – product of rock density and seismic wave velocity  |
| `Brittle`   | **Brittleness Index** – indicates rock's tendency to fracture               |
| `TOC`       | **Total Organic Carbon** – measure of hydrocarbon potential                 |
| `VR`        | **Vitrinite Reflectance** – maturity level of organic matter in the rock    |
| `Production`| Fluid production volume (target variable for prediction)     
