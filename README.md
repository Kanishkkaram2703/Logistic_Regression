# Logistic_Regression

#### **1. Linear Regression with Multiple Variables**
This notebook implements a linear regression model to predict house prices based on multiple variables (e.g., lot size, number of bedrooms, and bathrooms). The following are its key features:

- **Data Loading and Preparation**:
  - Reads data from a CSV file (`Housing.csv`) and checks for missing values.
  - Fills missing values in the `bedrooms` column with the median value.

- **Model Training**:
  - Fits a `LinearRegression` model using Scikit-learn, with predictors: `lotsize`, `bedrooms`, and `bathrms`.
  - Extracts model coefficients and intercept.

- **Prediction**:
  - Uses the trained model to predict house prices based on specified input values.
  - Performs manual calculation of the prediction using the regression equation for validation.

- **Code**:
  - Includes 12 code cells covering data import, preprocessing, model training, and prediction.

#### **2. Linear Regression with a Single Variable**
This notebook implements a simpler linear regression model that predicts house prices using a single predictor: lot size. Key features include:

- **Data Loading and Exploration**:
  - Reads the same `Housing.csv` dataset.
  - Provides basic data statistics and visualizations of the `lotsize` vs. `price` relationship.

- **Model Training**:
  - Fits a `LinearRegression` model with `lotsize` as the independent variable.
  - Extracts the model's coefficient and intercept.

- **Prediction and Visualization**:
  - Predicts house prices for a given lot size.
  - Visualizes the data points and the regression line on a scatter plot.

- **Code**:
  - Includes 14 code cells covering data visualization, preprocessing, model training, prediction, and plotting.
