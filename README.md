# Logistic_Regression

### **1. Multiclass Classification Notebook**
- **Total Cells:** 24
- **Content Focus:**
  - **Dataset:** Uses the `load_digits` dataset from `sklearn.datasets`, a built-in dataset for handwritten digit recognition.
  - **Key Steps:**
    1. **Data Exploration:** 
       - Imports the dataset and explores its structure (`digits.data`, `digits.images`).
       - Displays sample images using Matplotlib to understand the data visually.
    2. **Data Splitting:** 
       - Splits the dataset into training and testing sets using `train_test_split`.
    3. **Model Training:** 
       - Implements logistic regression using `LogisticRegression` from `sklearn`.
       - Trains the model on the training set and evaluates its performance on the testing set.
    4. **Prediction and Metrics:** 
       - Predicts outcomes for test data.
       - Evaluates the model using a confusion matrix, which is visualized using Seaborn.
    5. **Additional Analysis:** 
       - Explores prediction probabilities for both training and testing datasets using the `predict_proba` method.
  - **Visualizations:** 
    - Displays images of handwritten digits.
    - Heatmap for the confusion matrix to assess model performance.
  - **Libraries Used:** `Matplotlib`, `Seaborn`, `sklearn.datasets`, `sklearn.linear_model`, `sklearn.metrics`.

---

### **2. Binary Classification Notebook**
- **Total Cells:** 13
- **Content Focus:**
  - **Dataset:** Uses a CSV file (`diabetes.csv`) as the data source, likely containing information for diabetes prediction.
  - **Key Steps:**
    1. **Data Import and Exploration:** 
       - Reads the dataset using `pandas`.
       - Visualizes relationships between features using scatter plots (`Glucose` vs. `Age`).
    2. **Data Splitting:**
       - Splits the dataset into training and testing sets, with features like `Age` and target variable `Glucose`.
    3. **Model Training:**
       - Implements logistic regression for binary classification using `LogisticRegression`.
       - Fits the model to the training data and calculates prediction probabilities.
    4. **Evaluation:**
       - Measures model accuracy using the `score` method.
       - Explores probabilities for the test dataset (`predict_proba`).
  - **Visualizations:** Scatter plots for feature relationships.
  - **Libraries Used:** `pandas`, `numpy`, `matplotlib`, `sklearn.linear_model`, `sklearn.model_selection`.

---

### Key Differences:
- **Objective:**
  - Multiclass classification predicts multiple classes (e.g., digits 0–9).
  - Binary classification handles two outcomes (e.g., presence or absence of a condition).
- **Dataset:**
  - Multiclass uses a built-in digit recognition dataset.
  - Binary uses a custom dataset (`diabetes.csv`).
