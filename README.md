# Policy-Analysis
Government Effectiveness Prediction model
# Forecasting Government Effectiveness in Africa
## A Machine Learning Analysis of Socio-Economic Drivers

### Project Overview
This research examines the relationship between 2019 socio-economic indicators and 2020 government effectiveness across 20 African nations. It provides a predictive framework for 2024 governance risks.

### Key Technical Features
* **Model:** Ridge Regression (handling multi-collinearity in development data).
* **Validation:** 5-fold Cross-Validation (R²: 0.541).
* **Data Sources:** World Development Indicators (WDI) & Worldwide Governance Indicators (WGI).

================================================================================
🤖 BUILDING PREDICTIVE MODEL: Government Effectiveness
================================================================================

📊 Features: 19
📈 Target range: 20.0 - 57.4

Linear Regression:
  CV R²: -0.944 (±2.601)

Ridge Regression:
  CV R²: 0.541 (±0.174)

Lasso Regression:
  CV R²: 0.526 (±0.248)

Random Forest:
  CV R²: 0.409 (±0.138)

✅ Best model: Ridge Regression
   Cross-validated R²: 0.541


### Major Findings
* **Positive Impact:** Control of Corruption is the strongest predictor of institutional success.
* **Risk Factors:** High Youth Dependency and Multilateral Debt Service show the strongest negative correlation with effectiveness.

================================================================================
🌍 GEOPOLITICAL DRIVERS OF GOVERNMENT EFFECTIVENESS
================================================================================

📈 POSITIVE DRIVERS (Strengthen Governance):

   ✓ Control of Corruption
      Effect: +6.25
      Policy Implication: Strengthening this area predicts improved Government Effectiveness

   ✓ Government consumption expenditure growth
      Effect: +1.93
      Policy Implication: Strengthening this area predicts improved Government Effectiveness

   ✓ Male contributing family workers
      Effect: +1.68
      Policy Implication: Strengthening this area predicts improved Government Effectiveness

📉 NEGATIVE DRIVERS (Weaken Governance):

   ✗ Old-age dependency ratio
      Effect: -1.60
      Policy Implication: Increases in this area signal governance risks

   ✗ Multilateral debt service
      Effect: -2.12
      Policy Implication: Increases in this area signal governance risks

   ✗ Youth dependency ratio
      Effect: -3.25
      Policy Implication: Increases in this area signal governance risks

<img width="1287" height="495" alt="image" src="https://github.com/user-attachments/assets/5577084b-8cab-4cf8-8eab-7925166832ef" />


### Outputs
* **Policy Executive Summary:** Targeted for senior officials.
* **Country Program Data:** For resource allocation.
* **Full Research Dataset:** For academic replication.
