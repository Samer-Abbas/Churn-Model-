# README

## Customer Churn Prediction Project

This project analyzes customer churn using various machine learning models. The goal is to predict which customers are likely to leave the bank, using features from the provided dataset.

### Project Structure

- `Churn Model Project.ipynb`: Main Jupyter notebook containing data loading, preprocessing, model training, evaluation, and analysis.
- `Churn_Modelling.csv`: Dataset with customer information and churn labels.

### Workflow Overview

1. **Data Loading**  
   The dataset is loaded from `Churn_Modelling.csv` using pandas.

2. **Data Cleaning & Exploration**  
   - Checks for missing values and duplicates.
   - Explores data types and distributions.

3. **Preprocessing**  
   - Encodes categorical variables (`Gender`, `Geography`).
   - Selects relevant features for modeling.
   - Splits data into training and test sets.
   - Scales features using `StandardScaler`.

4. **Model Training & Evaluation**  
   Trains and evaluates several models:
   - Random Forest
   - Logistic Regression
   - Support Vector Machine (SVM)
   - K-Nearest Neighbors (KNN)
   - Decision Tree
   - Gradient Boosting (with Grid Search)

   Evaluation metrics include confusion matrix, accuracy, and classification report.

5. **Feature Importance**  
   Analyzes which features are most important for predicting churn.

6. **Conclusion**  
   Summarizes findings and suggests possible improvements.

### How to Run

1. Open `Churn Model Project.ipynb` in Jupyter Notebook or VS Code.
2. Ensure `Churn_Modelling.csv` is in the same directory.
3. Run all cells to reproduce the analysis and results.

### Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

Install dependencies with:
```sh
pip install pandas numpy matplotlib seaborn scikit-learn
```

### Notes

- The notebook is self-contained and does not require additional scripts.
- For best results, review and adjust feature selection or model parameters as needed.

---