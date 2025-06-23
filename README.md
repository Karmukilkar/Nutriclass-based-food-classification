# 🍎 Food Nutrition Classification

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-1.0%2B-orange.svg)](https://scikit-learn.org/)
[![Pandas](https://img.shields.io/badge/Pandas-1.0%2B-yellow.svg)](https://pandas.pydata.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-3.0%2B-green.svg)](https://matplotlib.org/)
[![Seaborn](https://img.shields.io/badge/Seaborn-0.11%2B-cyan.svg)](https://seaborn.pydata.org/)

## 📊 Project Overview

This project develops a robust machine learning system to classify food items into multiple categories based on nutritional attributes such as calories, proteins, carbohydrates, fats, and sugar. The workflow covers data preprocessing, feature engineering, exploratory data analysis, model building (Logistic Regression, Decision Tree, Random Forest, KNN, SVM, XGBoost, Gradient Boosting), evaluation, and model saving. The goal is to accurately label food types and gain insights into what makes each food category distinct, supporting dietary management systems.

---

## 🛠️ Technical Tags

- Data Preprocessing
- Classification Modeling
- Feature Engineering
- Hyperparameter Tuning
- Visualization
- Python
- Scikit-learn
- Pandas
- Matplotlib/Seaborn

---

## 🚀 Approach

1. **Data Preprocessing:**  
   - Load and clean raw data
   - Handle missing values, outliers, and duplicates
   - Convert data types and encode categorical variables
2. **Feature Engineering:**  
   - Select top features using feature importance
   - Standardize numerical features
3. **Exploratory Data Analysis:**  
   - Visualize distributions, outliers, and category frequencies
   - Analyze feature correlations and importance
4. **Modeling:**  
   - Train and evaluate Logistic Regression, Decision Tree, Random Forest, KNN, SVM, XGBoost, and Gradient Boosting models
5. **Evaluation:**  
   - Use Accuracy, Precision, Recall, F1 Score, and Confusion Matrix for model comparison
6. **Model Saving:**  
   - Serialize trained models for future use

---

---

## 📈 Key Insights

- **Distinctive Features:** Calories, protein, fat, and sugar are the most significant for classifying food categories.
- **Model Performance:** Ensemble models (Random Forest, XGBoost, Gradient Boosting) outperform simpler models.
- **Data Quality:** Clean, well-annotated data with minimal missing values and outliers is crucial for high accuracy.
- **Practical Use:** The system can be integrated into dietary management apps and nutritional recommendation platforms.

---

## 📝 How to Run

1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/food-nutriclass-project.git
    cd food-nutriclass-project
    ```

2. **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
    *(Create `requirements.txt` with pandas, numpy, scikit-learn, matplotlib, seaborn, xgboost, etc.)*

3. **Run Notebooks:**
    - Open [preprocessing.ipynb](http://_vscodecontentref_/3) for data cleaning and feature engineering.
    - Open [ML_CLASSIFICATION-1.ipynb](http://_vscodecontentref_/4) for model training and evaluation.

---

## 📊 Visualization Examples

- Distribution plots for all nutritional features
- Category frequency barplots
- Correlation heatmap
- Boxplots for outlier detection

---

## 🤖 Model Evaluation

| Model                | Accuracy | Precision | Recall | F1 Score |
|----------------------|----------|-----------|--------|----------|
| Logistic Regression  | 0.980486 | 0.980527  | 0.9804 | 0.980479 |
| Decision Tree        | 0.988996 | 0.989009  | 0.9889 | 0.988988 |
| Random Forest        | 0.994498 | 0.994521  | 0.9944 | 0.994501 |
| KNN                  | 0.989507 | 0.989526  | 0.9895 | 0.989491 |
| SVM                  | 0.989251 | 0.989373  | 0.9892 | 0.989271 |
| XGBoost              | 0.99501  | 0.995035  | 0.9950 | 0.99501  |
| Gradient Boosting    | 0.99501  | 0.995035  | 0.9950 | 0.995009 |


---

## 💡 Recommendations

- Add more features (e.g., fiber, vitamins) for improved classification
- Use hyperparameter tuning for optimal model performance
- Consider robust scaling or outlier removal for stability
- Deploy the best model for real-time food classification

---

## 📚 References

- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [Scikit-learn Documentation](https://scikit-learn.org/stable/documentation.html)
- [Matplotlib Documentation](https://matplotlib.org/stable/contents.html)
- [Seaborn Documentation](https://seaborn.pydata.org/)

---

## © License

This project is licensed under the MIT
