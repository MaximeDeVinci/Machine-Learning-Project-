Brazilian Aeronautical Accidents Analysis & Prediction

I. Project Overview

This project focuses on the analysis and predictive modeling of aeronautical occurrences in Brazil, using data provided by CENIPA (Center for Research and Prevention of Aeronautical Accidents).
The primary goal is to distinguish between Simple Incidents and Critical Events (Accidents and Serious Incidents) to support better resource allocation for investigations and prioritize safety interventions.

II. How to Run (Google Colab)

Note: This project is designed to be executed in Google Colab to handle the file upload interface and library dependencies easily.
1. Open Google Colab
2. Upload the .ipynb file from this repository
3. Upload the two required datasets when prompted by the first code cells:
   - aircrafts.csv
   - occurrences.csv
4. Run all cells sequentially

III. Key Features & Methodology

The project follows a complete Data Science pipeline:
- Data Pre-processing: Handling missing values, categorical encoding (Label Encoding), and high-cardinality reduction
- Class Imbalance Management: Implementation of SMOTE (Synthetic Minority Over-sampling Technique) to address the minority class (27% critical events)
- Machine Learning Models:
    * Baseline: Decision Tree
    * Advanced: Random Forest, Logistic Regression, and XGBoost
- Optimization: Hyperparameter tuning using GridSearchCV

IV. Repository Structure

- Project_Pâris-Jeremie_Manas-Maxime_Poutiers-Chloé.ipynb: The full Python code with explanations.
- Data: aircrafts.csv and occurrences.csv

Authors: Chloé POUTIERS, Jérémie PARIS, Maxime MANAS
Dataset Source: CENIPA (Brazilian Aeronautical Accidents) via Kaggle

