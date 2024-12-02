# Predicting Insurance Charges Using Decision Tree Regression

## Project Overview
This project aims to predict insurance charges based on personal and demographic information using a Decision Tree Regression model. The dataset contains information such as age, sex, BMI, number of children, smoking habits, and the region of the insured individual. 

## Dataset Details
The dataset used for this project (`insurance.csv`) contains 1,338 entries with the following columns:
- `age` (int): The age of the individual.
- `sex` (str): The gender of the individual (`male` or `female`).
- `bmi` (float): Body Mass Index, a measure of body fat.
- `children` (int): Number of children/dependents covered by health insurance.
- `smoker` (str): Smoking habits (`yes` or `no`).
- `region` (str): Region of residence (`northeast`, `northwest`, `southeast`, `southwest`).
- `charges` (float): Medical insurance charges.

## Objective
The goal is to develop a machine learning model that predicts insurance charges (`charges`) based on the input features (`age`, `sex`, `bmi`, `children`, `smoker`, and `region`).

## Technologies and Tools Used
### Libraries:
1. **Pandas**: For data manipulation and analysis.
2. **NumPy**: For numerical computations.
3. **Matplotlib & Seaborn**: For data visualization.
4. **Scikit-learn**: For implementing the Decision Tree Regression model and evaluating its performance.

### Techniques:
- Data preprocessing: Handling categorical data using encoding techniques.
- Feature scaling: Applying techniques like Min-Max scaling and standardization.
- Machine Learning: Using Decision Tree Regression to predict insurance charges.
- Performance Metrics: Evaluated the model using metrics such as Mean Absolute Error (MAE) and R² score.

## Steps Performed
1. **Data Exploration**:
   - Visualized relationships between features and the target variable (`charges`).
   - Checked for missing values and cleaned the data.
2. **Data Preprocessing**:
   - Encoded categorical features (`sex`, `smoker`, and `region`) into numerical representations.
   - Split the dataset into training and testing sets using an 80-20 split.
   - Scaled features to improve model performance.
3. **Model Building**:
   - Built a Decision Tree Regressor using Scikit-learn.
   - Optimized hyperparameters to improve prediction accuracy.
4. **Evaluation**:
   - Measured model performance using Mean Absolute Error (MAE) and R² score.
   - Visualized predictions to understand model behavior.

## Results
- **R² Score**: Indicates how well the model explains variance in insurance charges.
- **MAE**: Measures the average prediction error in terms of insurance charges.
