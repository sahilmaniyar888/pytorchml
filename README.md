Urban Heat Island Prediction with Machine Learning
Overview
This GitHub Repo contains Jonah Zembower and Benjamin Nicholson's work from the EY Data Challenge 2025: Predicting Urban Heat Islands. We built a predictive machine learning model to identify Urban Heat Islands (UHI) using remote sensing and iterative Machine Learning pipelines. Over the source of the project we leveraged a variety of satellite imagery, geospatial data, and machine learning models to accurately predict UHI values. You can find the final model documentation in the Model folder as Final_Model (detailed process of analysis) or nyc_notebook and greensburg_notebook (focused specifically on the model).

Our model achieved a final accuracy of 0.9606, ranking 86th globally out of over two thousand participants. Model Accuracy Ranking
= https://github.com/JZembower/Urban_Heat_Island_Index_Prediction_Model/blob/main/Model/nyc_notebook.ipynb

Data Sources
Sentinel-2 (Multispectral Imaging) median mosaic
Sentinel-1 (Radar Imaging) median mosaic
Landsat-8 (Thermal) temperature data
Landsat-8 (Non Thermal) median mosaic
Building & Natural Elevation (NYC Open Data Source)
LiDAR DSM (Total Elevation), DTM (Natural Elevation), HAG (Building Height)
Notebook Structure
Introduction
Load in EY Dataset
Satellite Imagery Creation using Microsoft Planetary Computer
Load NYC Open Data
Load Satellite Data
Build Random Forest Model
Fit Hyperparameters to Optimize Accuracy
Output Final Results
Results
Best Model Evaluation
The best model was a Random Forest:

Max Depth: 37

Max Features: log2

Min Samples Leaf: 1

Min Samples Split: 2

Number Estimators: 500

Model Accuracy Evaluation

Feature Importance
The feature importance of our model is included below.

Feature Importance

UHI Prediction Heatmap
The below is the heatmap that we have created from our model with a 96.06% accuracy

UHI Prediction

Achievements
Ranked 86th globally with an accuracy of 0.9606.
Presented findings at Seton Hill University Research Conference.
Entered in Seton Hill Pitch Competition.
Reflections
This project presented the power of big data and machine learning and its applications in climate science. This has opened the world of data science in climate tech and I look forward to continue contributing to its widespanning impacts.
