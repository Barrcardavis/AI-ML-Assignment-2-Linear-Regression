# 🏡 AD331 Assignment 2: Linear Regression  
**Author:** David Davis  
**Course:** AD331 - Application Development  
**Term:** Fall 2025  

## 📊 Dataset  
King County House Price dataset (simplified version)  
**Target Variable:** `SalePrice`  

## 🧼 Data Cleaning  
- Removed nulls and filtered outliers  
- Verified data types and feature distributions  

## 🧠 Feature Engineering  
- Created `house_age` from `yr_built`  
- One-hot encoded `ZipCode`  
- Added `LandVal` as a predictive feature  
- Constructed audit-aligned custom inputs for prediction

## 📈 Model  
- Linear Regression  
- Train/Test split: 80/20  
- Evaluation metrics:  
  - **R²:** *your value here*  
  - **MSE:** *your value here*  

## 🔮 Custom Predictions  
- 2,000 sqft, 10 yrs old, not renovated → **$415,941.06**  
- 3,000 sqft, 20 yrs old, not renovated → **$327,447.35**

## 🪞 Reflection  
This assignment reinforced the importance of data cleaning and thoughtful feature engineering in improving model accuracy. One key insight came from the box plot visualization: after refining the feature set each time and re-running the data for the model the plot points got closer to the red dash line indication a better match for predicting pricing.

Future iterations could explore nonlinear models (e.g., Random Forest or Gradient Boosting) to capture deeper interactions between features like `house_age`, `LandVal`, and `BldgGrade`. Additionally, evaluating feature importance and residuals could help identify remaining sources of prediction error.
