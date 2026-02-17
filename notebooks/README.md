# Climate Visibility Prediction

## Project Overview
This project focuses on predicting maximum atmospheric visibility based on weather and environmental parameters. The goal is to build a machine learning model that can accurately estimate visibility under different climatic conditions.

## Objective
- Predict visibility distance using historical weather data
- Analyze the impact of temperature, humidity, wind, and pressure on visibility
- Apply proper data preprocessing and machine learning techniques

## Dataset
- Weather data collected from a meteorological station
- Cleaned and preprocessed dataset available in the `data/` folder
- Target variable: VISIBILITY

## Data Preprocessing
The following preprocessing steps were performed:
- Missing value analysis and handling
- Univariate and multivariate analysis
- Correlation analysis and multicollinearity check (VIF)
- Outlier detection and treatment using IQR method
- Feature selection based on statistical analysis

## Project Structure
climate-visibility-prediction/
├── data/
│ └── final_preprocessed_visibility_data.csv
├── notebooks/
│ └── EDA_Preprocessing.ipynb
├── models/
│ └── (model training notebooks)
└── README.md


## Team Contributions
- EDA & Data Preprocessing: Completed
- Model Development: In progress
- Evaluation & Visualization: In progress
- Documentation & Presentation: Pending

## Tools & Technologies
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Google Colab
- GitHub
