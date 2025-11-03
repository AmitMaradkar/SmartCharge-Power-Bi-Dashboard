# SmartCharge-Power-Bi-Dashboard
##Project Overview

This project presents a Machine Learning–based predictive analytics framework for forecasting Electric Vehicle (EV) charging demand, expected waiting time, and tariff fluctuation across multiple cities and charging stations. The system integrates predictive modeling with interactive Power BI dashboards to support data-driven decision-making for EV infrastructure planning, tariff regulation, and station optimization.

The solution bridges data science, energy management, and visualization by combining real-world datasets, ensemble-based regression models, and dynamic Power BI reporting tools. It is designed to assist urban planners, charging network operators, and policymakers in improving the efficiency and sustainability of EV charging ecosystems.

##Key Features

Machine Learning Framework: Implements regression-based predictive modeling (Random Forest Regressor) to estimate demand, price, and waiting times.

Data Integration: Combines real-world and simulated datasets including attributes like city, station ID, connector type, energy usage, and session duration.

Feature Engineering: Extracts influential predictors such as port utilization, average energy drawn, and charging frequency.

Performance Evaluation: Validated using R², MAE, and RMSE metrics to ensure high predictive accuracy and generalization.

Power BI Dashboard: Offers real-time visualization with interactive maps, cards, and filters (distance, city, and station).

Decision Support: Provides insights for station placement, dynamic pricing, and load management strategies.

##Data Model Overview

The Power BI data model connects multiple datasets for integrated analysis:

Predicted_Station_Demand: Contains machine learning predictions for demand, tariff, and waiting time per station.

MLdataset: Source dataset used for model training and testing.

StationsDummy: Reference table holding station location and ID details.

prmMaxDistance: Parameter table for distance-based filtering on the dashboard.

These datasets are linked through station_id and city relationships to enable dynamic spatial filtering and interactive analytics.

##Tech Stack

Languages & Libraries: Python (Pandas, NumPy, Scikit-learn, Matplotlib)

Machine Learning Model: Random Forest Regressor

Visualization: Power BI (cards, filters, maps, relationships)

Tools: Power BI Desktop / GitHub

Data Sources: Real-world EV charging data 

##Outcomes

Improved accuracy in predicting EV charging demand and tariff trends.

Enhanced energy management and infrastructure planning through predictive analytics.

Developed a user-friendly Power BI dashboard for operational and policy-level decision-making.
