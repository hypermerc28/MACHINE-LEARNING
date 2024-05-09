# Wine Quality Prediction Project

## Overview
This project is dedicated to predicting the quality of Portuguese wines using physicochemical attributes from separate datasets for red and white wines. It utilizes advanced machine learning techniques to determine how different characteristics such as acidity, sugar levels, and alcohol content influence wine quality. The goal is to provide accurate predictions that can assist winemakers and quality assurance processes in evaluating wine quality.

## Approach

### Data Loading and Preprocessing
- **Data Sources**: The project uses datasets for red and white Portuguese wines.
- **Preprocessing Steps**: Data normalization through scaling and handling missing values to prepare the data for modeling.

### Modeling
1. **Baseline Model with Logistic Regression**
   - Initial predictions are made using Logistic Regression to establish a baseline for model performance.
2. **Advanced Modeling with RandomForest**
   - A RandomForestClassifier is used for its ability to handle complex dataset features and improve prediction accuracy.
3. **Hyperparameter Optimization**
   - Grid search is implemented to find the optimal parameters (`max_depth`, `n_estimators`) for the RandomForest model.

### Evaluation
- The models are evaluated using the F1 score, which balances precision and recall, providing a comprehensive measure of model accuracy.
- The performance improvement is quantified by comparing the F1 scores of the baseline and optimized models.

## Results
- The optimized RandomForest model shows significant improvement over the baseline Logistic Regression model.
- Predictions are exported to a `predictions.csv` file for further analysis or application.

## Conclusion
The use of RandomForest after establishing a baseline with Logistic Regression demonstrates a structured and effective approach to predicting wine quality based on physicochemical data. This project highlights the capabilities of machine learning in enhancing predictive accuracy and offers a replicable methodology for similar analytical tasks.

## Dependencies
- Python 3
- Pandas
- Scikit-learn
- Jupyter

