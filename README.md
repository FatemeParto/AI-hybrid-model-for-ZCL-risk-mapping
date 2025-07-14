Disease Risk Mapping Using Random Forest & XGBoost
Status: Manuscript Under Peer Review (Submitted to Environmental Research Communications)
Project Overview
This repository implements an integrated AI-GIS-RS framework for the precise spatial risk prediction of Zoonotic Cutaneous Leishmaniasis (ZCL). The framework combines:
•	Remote Sensing (RS): Extraction of environmental variables from satellite data
•	Geographic Information Systems (GIS): Spatial data preparation and analysis
•	Machine Learning (ML): Utilization of Random Forest (RF) and Extreme Gradient Boosting (XGBoost) algorithms for high-fidelity disease risk mapping
The study leverages ZCL incidence data collected between 2014 and 2019, alongside critical environmental predictors including temperature, normalized difference vegetation index (NDVI), and humidity. All spatial data layers have been standardized into ASCII raster (.asc) format with consistent resolution, projection, and spatial extent to ensure methodological rigor.
Features
•	Preprocessing and alignment of multi-source spatial datasets
•	Conversion of raster environmental data into structured feature matrices suitable for ML modeling
•	Training and evaluation of RF and XGBoost models for disease risk classification
•	Model performance assessment using Root Mean Square Error (RMSE), Mean Absolute Error (MAE), and Area Under the Curve (AUC) metrics
•	Generation of high-resolution, publication-quality risk maps exported as PDF files

