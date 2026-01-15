# Alzheimer's Disease Risk Factor Analysis 

**Final Project: Neuro-Data Analysis** **Team Members:** Roni prince, hanna Sharon 

## Project Overview
This project investigates the relationship between demographic data, lifestyle habits, and cognitive clinical scores in predicting Alzheimer's Disease. Using a comprehensive dataset of 2,149 patients, we aim to identify key predictors and assess how lifestyle choices impact cognitive health.

## Hypotheses
1. **Lifestyle:** We hypothesize that smoking and lack of physical activity correlate with a higher likelihood of diagnosis.
2. **Education:** We expect to find a "protective effect" where higher education levels correlate with higher MMSE scores.
3. **Sleep:** We investigate if poor sleep quality is linked to increased memory complaints.

## Folder Structure
- `/data`: Contains the raw dataset (`alzheimers_disease_data.csv`).
- `/src`: Python modules for data processing, modeling, and visualization.
- `/tests`: Pytest scripts for data and model validation.
- `main.py`: Entry point for the analysis.
- `requirements.txt`: Project dependencies.

## Key Stages
1. **Data Import & Cleaning:** Handling missing values and outliers.
2. **EDA:** Visualizing correlations (Heatmaps, Boxplots, Scatter plots).
3. **Modeling:** Logistic Regression to predict diagnosis.
4. **Analysis:** Statistical validation (T-Tests, Chi-Square).

## Instructions
1. Install requirements: `pip install -r requirements.txt`

2. Run analysis: `python main.py`
