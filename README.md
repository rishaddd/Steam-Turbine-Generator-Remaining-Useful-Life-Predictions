# Steam-Turbine-Generator-Remaining-Useful-Life-Predictions
Thesis Project: Steam Turbine RUL Prediction using Ensemble Model (TCN + XGBoost)

**Project Overview**:
This project aims to predict the Remaining Useful Life (RUL) of geothermal power plant equipment using historical sensor data.
The objective is to support predictive maintenance strategies, reduce unplanned downtime, and optimize maintenance scheduling.

**Business Problem**:
Unplanned equipment failure in geothermal power plants can lead to:
- High maintenance costs
- Production downtime
- Safety risks
By predicting RUL, maintenance teams can shift from reactive to predictive maintenance.

**Analytical Approach**:
The project follows a structured data analysis pipeline:
1. Business Understanding
   - Defined predictive maintenance objectives and RUL formulation
2. Data Understanding
   - Explored multivariate sensor data and operational patterns
3. Exploratory Data Analysis (EDA)
   - Analyzed sensor trends and degradation behavior
4. Feature Engineering
   - Created time-based and statistical features to capture degradation signals
5. Modeling
   - Applied regression-based machine learning models such as XGBoost, TCN and Ensemble Model to estimate RUL
6. Evaluation
   - Assessed model performance using regression metrics and visual comparison
  
Model Evaluation
Model performance was evaluated using regression metrics such as:
- **RMSE (Root Mean Squared Error)**
- **MAE (Mean Absolute Error)**

The results indicate that the model is able to capture degradation patterns and provide reasonable RUL estimates for predictive maintenance purposes.

---

## Tech Stack
- **Programming Language:** Python  
- **Libraries:**  
  - Pandas, NumPy  
  - Scikit-learn  
  - Matplotlib / Seaborn  

---

## Dataset
The dataset consists of historical sensor readings from geothermal power plant equipment.

> ⚠️ Due to confidentiality reasons, the raw dataset is not publicly shared.  
> The notebook focuses on methodology, analysis workflow, and modeling approach.

---

## Key Insights
- Certain sensor variables exhibit clear degradation trends as equipment approaches end-of-life
- Feature engineering plays a critical role in improving RUL prediction performance
- Predictive maintenance can significantly reduce unplanned downtime compared to reactive maintenance

Notes
This project is part of a personal data portfolio focused on:
- Data analysis
- Industrial analytics
- Predictive maintenance use cases
