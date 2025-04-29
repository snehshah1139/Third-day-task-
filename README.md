# Third-day-task-

# Task 3 - Linear Regression: Cancer Severity Prediction

## Objective
Apply simple and multiple linear regression techniques to understand key factors influencing cancer severity scores.

## Tools Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

## Dataset Details
The dataset includes:
- Patient information (age, gender, country, health risks)
- Medical records (cancer type, stage, treatment cost)
- Target variable: Severity Score

## Steps Performed
1. Data Loading and Cleaning  
   - Removed unnecessary columns such as Patient_ID and Country_Region.
   
2. Feature Selection  
   - Focused on relevant numeric features for modeling.

3. Data Splitting  
   - Divided into training and testing sets (80/20 split).

4. Model Training  
   - Used LinearRegression from sklearn to fit the model.

5. Evaluation  
   - Calculated MAE, MSE, and R² score to assess model performance.

6. Coefficient Interpretation  
   - Analyzed the importance of each feature based on model coefficients.

7. Visualization  
   - Plotted predicted vs actual severity scores to check the fit.

## Files Included
- global_cancer_patients_2015_2024: Input dataset
- `Elevate_lab_task_D3`: Full code and analysis
- `README.md`: Task explanation and structure

## After puting Liner Regression,Ploat view

![Screenshot (63)](https://github.com/user-attachments/assets/06d22739-568f-49c3-9192-a8b72cb6185f)

# **Actual vs Predicted Plot – Model Accuracy Visualization**

**If the model was guessing wrong, the dots would be scattered. But here, they all sit perfectly on the ideal line — proving the model has learned the relationship extremely well!**



## Note
The task focuses on clear understanding, feature interpretation, and professional model building.
