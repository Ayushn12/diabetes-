# Glucose Level Prediction Project

This project uses machine learning to predict high glucose levels (potential diabetes) using health-related features from the Framingham dataset. The workflow includes data cleaning, exploratory data analysis, feature engineering, model training, evaluation, and interpretation.

## Features

- Data cleaning and imputation
- Exploratory data analysis and visualization
- Feature engineering (including new derived features)
- Model training: Logistic Regression, Decision Tree, Random Forest
- Model evaluation: accuracy, classification report, confusion matrix
- Feature importance visualization

## Dataset

- **Source:** `framingham.csv`
- **Description:** Contains health indicators such as age, BMI, blood pressure, cholesterol, and glucose levels.

## How to Run

1. **Install dependencies:**
   ```sh
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```

2. **Open the notebook:**  
   `Glucose_Prediction_Summary (1).ipynb` in Jupyter or VS Code.

3. **Run all cells:**  
   Execute each cell in order to reproduce the analysis and results.

## Project Steps

1. **Import and explore the dataset**
2. **Clean the data (handle missing values)**
3. **Visualize glucose and related health indicators**
4. **Feature engineering (including new features)**
5. **Train machine learning models**
6. **Evaluate model performance**
7. **Interpret feature importance**

## Example New Features

- Age group (young, middle-aged, senior)
- BMI category (underweight, normal, overweight, obese)
- Blood pressure ratio
- Cholesterol to HDL ratio
- Age × BMI interaction

## Results

- Random Forest performed best for predicting diabetes risk.
- Key features: BMI, blood pressure, age, cholesterol.



## Author

Created by Ayush
