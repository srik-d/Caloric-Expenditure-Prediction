## Caloric Expenditure Prediction Project

### Prediction Objective
This project predicts the caloric expenditure (calories burnt) based on user-provided inputs related to physical activity and individual characteristics.

### Dependencies
- Python 3.x
- pandas
- scikit-learn
- xgboost

 ### Datasets
- **exercise.csv**: Dataset containing features related to personal and exercise activities of users collected .
- **calories.csv**: Dataset providing information on caloric expenditure of users collected.

### Usage
1. **Run the Python notebook file**: Execute `caloricExpenditurePrediction.py` to initiate the prediction process.
2. **Input Data**: Follow the prompts to input the required data as listed below.
3. **Output**: The script will output the predicted caloric expenditure based on the provided inputs.

### Input Requirements
Users are required to provide the following inputs:
- **Age**: Age of the individual in years.
- **Height**: Height of the individual in centimeters (cm).
- **Weight**: Weight of the individual in kilograms (kg).
- **Duration**: Duration of the physical activity in minutes.
- **Heart rate**: Average heart rate during the activity.
- **Body temperature**: Body temperature during or after the activity.
- **Gender**: Gender of the individual, specified as:
  - **Gender_female**: 1 for female, 0 for not female.
  - **Gender_male**: 1 for male, 0 for not male.

### Model: XGBoost Regressor
XGBoost (eXtreme Gradient Boosting) Regressor is chosen for its robustness and efficiency in handling complex relationships within data. It combines decision tree-based models to improve predictive accuracy and is well-suited for regression tasks like predicting caloric expenditure.

### Model Performance
**Mean Absolute Error (MAE)**: The model achieves a Mean Absolute Error of **1.4837**, indicating its accuracy in predicting caloric expenditure based on the provided inputs.





