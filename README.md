# Food Nutrition Classification Project

## Overview

This project classifies food items based on their nutritional features using various machine learning algorithms. The workflow covers data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and model persistence for deployment.

---

## 1. Data Preprocessing & Exploratory Data Analysis

### 1.1. Importing Libraries

- pandas, numpy, matplotlib, seaborn, scikit-learn, xgboost, pickle

### 1.2. Data Loading

- Loaded raw data from `food_data.csv`.

### 1.3. Initial Exploration

- Inspected data shape, head, and descriptive statistics.
- Checked for null values and calculated their percentage.

### 1.4. Null Values Treatment

- Dropped rows with missing values due to their small number.

### 1.5. Variable Identification

- Identified numerical and categorical variables.

### 1.6. Distribution Analysis

- Plotted distributions for continuous variables (KDE plots).
- Plotted counts for categorical variables (count plots).

### 1.7. Outlier Detection & Treatment

- Visualized outliers using boxplots.
- Applied IQR capping to limit outliers.

### 1.8. Duplicate Removal

- Checked for and removed duplicate entries.

### 1.9. Feature Scaling

- Standardized numerical features using `StandardScaler`.

### 1.10. Categorical Encoding

- Boolean columns (`Is_Vegan`, `Is_Gluten_Free`) encoded as 0/1.
- Other categorical columns label-encoded.

### 1.11. Feature Importance

- Used `RandomForestClassifier` to rank features.
- Selected top 9 features for modeling.

---

## 2. Model Building & Evaluation

### 2.1. Data Preparation

- **Features:** Sodium, Serving_Size, Cholesterol, Sugar, Is_Gluten_Free, Glycemic_Index, Protein, Calories, Fat
- **Target:** Food_Name
- Data split into training and testing sets.

### 2.2. Models Trained

| Model                     | File Saved As         |
|---------------------------|----------------------|
| Logistic Regression       | Logistic_reg         |
| Decision Tree Classifier  | DecisionTree_model   |
| Random Forest Classifier  | rand_forest          |
| K-Nearest Neighbors       | kn_model             |
| Support Vector Machine    | SVM_model            |
| XGBoost Classifier        | XGB_model            |
| Gradient Boosting Class.  | GBC_model            |

### 2.3. Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

Each model was evaluated on both training and testing data using these metrics.

### 2.4. Model Persistence

- All trained models were saved using Python’s `pickle` module for future inference and deployment.

---

