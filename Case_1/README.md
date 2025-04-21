# Reservoir Production Prediction using Machine Learning
## 🧠 Overview

This project aims to predict reservoir fluid production using machine learning techniques based on petrophysical and geophysical features derived from well log data. Accurate prediction of production rates supports better reservoir management, production optimization, and informed decision-making in hydrocarbon development projects.

By leveraging historical well data and rock properties, we train predictive models that estimate production outcomes, enabling more accurate planning and resource allocation.

## 🚀 Use Case
Understanding and forecasting production performance from subsurface formations is a core challenge in reservoir engineering. Traditional methods may fall short when data is noisy or incomplete. This project focuses on predicting fluid production volumes based on key rock and fluid indicators from well logs.

The workflow includes:
- Data Cleaning: Handling missing values and outliers.
- Feature Engineering: Selecting and transforming features for modeling.
- Model Training: Using ML algorithms such as Linear Regression, Random Forest, and XGBoost.
- Evaluation: Using metrics like RMSE and R² to evaluate model performance.
- Visualization: Comparing actual vs. predicted production for model validation.

Predicted values can be used to forecast productivity in undrilled locations or plan enhanced recovery strategies in existing wells.

## 📊 Dataset
The dataset contains engineered features commonly used in reservoir modeling and performance prediction. Each row represents a sample from a well, with associated measurements and the production volume.

### Key Columns:

| Feature     | Description                                                                     |
|-------------|---------------------------------------------------------------------------------|
| `WellIndex` | Unique identifier for each well sample                                          |
| `Por`       | **Porosity** – percentage of void space in rock that can store fluids           |
| `LogPerm`   | **Logarithm of Permeability** – rock’s ability to transmit fluids               |
| `AI`        | **Acoustic Impedance** – product of rock density and seismic wave velocity      |
| `Brittle`   | **Brittleness Index** – indicates tendency of rock to fracture                  |
| `TOC`       | **Total Organic Carbon** – measure of hydrocarbon generation potential          |
| `VR`        | **Vitrinite Reflectance** – reflects thermal maturity of organic matter         |
| `Production`| **Fluid production volume** - target variable for machine learning prediction   |

## 🎯 Outcome
This project demonstrates how machine learning can be applied to petrophysical data for production forecasting. The final model provides:
- Reliable prediction of reservoir production
- Improved reservoir performance analysis
- Data-driven support for well planning and intervention
- Better understanding of production drivers across different reservoirs