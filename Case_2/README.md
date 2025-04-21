# Volve Log Prediction
## 🧠 Overview
This project aims to enhance subsurface geological interpretation by predicting missing or unreliable well log data using machine learning. Well logs are critical for understanding rock and fluid properties, which directly impact exploration, drilling, and reservoir management decisions. By improving the completeness and accuracy of well log datasets, we enable better modeling of the reservoir and optimize field development strategies.

## 🚀 Use Case
In subsurface evaluations, missing or noisy log data can significantly hinder analysis and decision-making. This project focuses on predicting sonic travel time (DT) — a key parameter for estimating porosity and lithology — using other available log measurements.

Our workflow involves:
- Data Cleaning: Handling null values and removing outliers.
- Feature Engineering: Creating meaningful input features from raw logs.
- Model Training: Applying and tuning machine learning models (e.g., Random Forest, XGBoost, Neural Networks).
- Evaluation: Comparing predictions using MAE/RMSE to ensure reliability.
- Visualization: Plotting actual vs. predicted curves to validate geophysical consistency.

The predicted DT logs fill gaps in the original data and support enhanced formation evaluation, contributing to more accurate reservoir modeling.

## 📊 Dataset
We utilize high-quality data from the Volve field, containing comprehensive well logs essential for characterizing subsurface formations.

### Key Columns:

| Feature   | Description                                                               |
|-----------|---------------------------------------------------------------------------|
| `DEPTH`   | Depth of the measurement in the well                                      |
| `NPHI`    | **Neutron porosity** – indicates porosity of the rock                     |
| `RHOB`    | **Bulk density** – reflects density of rock and fluid                     |
| `GR`      | **Gamma ray** – distinguishes shale from clean formations                 |
| `RT`      | **True resistivity** – helps detect hydrocarbon zones                     |
| `PEF`     | **Photoelectric factor** – aids in lithology identification               |
| `CALI`    | **Borehole diameter** – indicates wellbore condition                      |
| `DT`      | **Sonic travel time** – used for porosity/lithology estimates (target)    |

## 🎯 Outcome
The machine learning pipeline enables:
- Accurate imputation of missing DT values
- Enhanced porosity and lithology estimates
- Improved reservoir characterization
- Smarter field development decisions

This project demonstrates the power of data science in addressing real-world challenges in the energy sector.