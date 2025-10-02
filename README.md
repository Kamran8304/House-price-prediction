# House-price-prediction
## About Data
House Price Prediction ML Project | Python • Scikit-learn • Pandas • Matplotlib A comprehensive machine learning solution for real estate price forecasting.  Includes EDA, feature engineering, multiple model implementations, and performance  comparison. Perfect for learning ML workflows and real-world data science applications.
# Key Features & Data Analysis
The dataset used contains 4600 records and 18 features, offering a comprehensive view of property sales.
### Core Features Analyzed:
Price: The target variable for prediction.

Bedrooms & Bathrooms: The number of main rooms.

Square Footage (sqft_living, sqft_lot, sqft_above, sqft_basement)

Structural Details: floors, yr_built, yr_renovated, condition.

Premium Features: waterfront (if the property is on a body of water) and view (quality of the view).

Location: city, statezip, and country.

# Methodology
The notebook performs comprehensive Exploratory Data Analysis (EDA) and data wrangling to handle potential data quality issues.
The prediction phase explores multiple regression algorithms for comparison:
- Linear Regression
- Lasso Regression
- Decision Tree Regressor.
# Example Prediction
The final output demonstrates the model's ability to provide an estimated price based on user-defined inputs:
Input Parameters (Example for Seattle):
- City: Seattle
- Bedrooms: 3
- Bathrooms: 2
- Square Footage: 1500
- Model Type: Linear Regression
## Predicted Price: 
 $471,366.85
 # Technologies Used
 - Python
 - Jupyter Notebook
 - pandas (Data manipulation)
 - numpy (Numerical operations)
 - matplotlib.pyplot (Data visualization)
 - seaborn (Statistical data visualization)
 - scikit-learn (Machine learning models - assumed for Linear, Lasso, and Tree Regressors)
