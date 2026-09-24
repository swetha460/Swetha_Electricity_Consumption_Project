# Electricity Consumption Analysis and Demand Prediction Using Data Analytics and Artificial Intelligence

## Project Overview
This project analyzes historical household electricity consumption data and predicts hourly electricity demand using machine learning.

It was prepared for the **AICTE × IBM SkillsBuild Data Analytics with AI Internship** through **BharatCares**.

## Problem Statement
Electricity consumption changes according to time and household usage patterns. Without proper analysis, it is difficult to identify high-demand periods and estimate future demand. This project uses data analytics and machine learning to understand historical electricity usage and predict hourly active power.

## Objectives
- Clean and understand historical electricity data.
- Analyze time-based consumption patterns.
- Visualize demand trends.
- Engineer calendar and lag-based features.
- Train Linear Regression and Random Forest Regression models.
- Evaluate models using MAE, RMSE and R².
- Produce data-driven findings and recommendations.

## Dataset
**Individual Household Electric Power Consumption**, UCI Machine Learning Repository, Dataset 235.

Official source:
https://archive.ics.uci.edu/dataset/235/individualhouseholdelectricpowerconsumption

DOI: https://doi.org/10.24432/C58K54

The dataset is not bundled in this generated package because it is a large public download. The notebook automatically downloads it from UCI when it is not found locally.

## Technologies Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Project Workflow
Dataset → Data Collection → Data Understanding → Data Cleaning → Preprocessing → EDA → Visualization → Feature Engineering → Chronological Train/Test Split → Machine Learning → Evaluation → Prediction → Insights → Recommendations

## Project Structure
```text
Swetha_Electricity_Consumption_Project/
├── Swetha_Electricity_Consumption_Analysis.ipynb
├── Swetha_Electricity_Consumption_ProjectReport.docx
├── README.md
├── requirements.txt
└── dataset/
    └── README.txt
```

## Installation
Open a terminal in the project folder:

```bash
python -m pip install -r requirements.txt
```

## How to Run
1. Install Python 3.
2. Open the project folder in VS Code.
3. Install the Jupyter extension if needed.
4. Open `Swetha_Electricity_Consumption_Analysis.ipynb`.
5. Select a Python kernel.
6. Run the notebook from top to bottom.
7. The first download cell retrieves the official UCI dataset if it is missing.
8. Review the generated graphs, tables and model metrics.

If automatic download does not work, download `household_power_consumption.txt` from the official UCI page and place it in the `dataset` folder.

## Machine Learning Models
1. Linear Regression
2. Random Forest Regressor

## Evaluation Metrics
- **MAE:** Average absolute prediction error. Lower is better.
- **RMSE:** Error metric that penalizes larger errors more strongly. Lower is better.
- **R²:** Indicates how much variation in the target is explained by the model. Higher is generally better.

## Results
The notebook generates the actual results after execution. No model performance values are hard-coded in this README.

## Key Insights
The final insights must be written from the executed notebook outputs. No findings are invented in advance.

## Future Enhancements
- Add weather and tariff information.
- Compare more forecasting approaches.
- Build a dashboard.
- Deploy the model as a web application.
- Test the method on multiple households.

## Author
**Swetha V**
