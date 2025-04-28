# Titanic Survival Prediction

## Objective
Develop a machine learning model to predict passenger survival on the Titanic based on key features such as age, gender, ticket class, fare, and cabin information.

## Dataset Description
The dataset includes:
- Passenger demographics (Age, Sex)
- Socio-economic status (Pclass, Fare)
- Travel details (Cabin, Embarked)

## Approach

### 1. Data Preprocessing
- Handled missing values appropriately (mean/mode imputation and domain-specific strategies).
- Encoded categorical variables using Label Encoding and One-Hot Encoding.
- Normalized numerical features to improve model convergence.

### 2. Model Development
- Built two classification models:
  - **Logistic Regression** (baseline model)
  - **Random Forest Classifier** (optimized model)
- Hyperparameter tuning using GridSearchCV for Random Forest.

### 3. Model Evaluation
Evaluated models based on:
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

### 4. Visualization
- Feature importance visualized using bar plots.
- 3D scatter plots and PCA visualizations to understand feature interactions and separability.

## Results
- Logistic Regression Accuracy: **XX%**
- Random Forest Accuracy: **YY%**
- Key influential features identified: `Sex`, `Fare`, `Pclass`

## How to Run
1. Clone this repository.
2. Install dependencies:
