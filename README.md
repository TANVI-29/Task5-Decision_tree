# Heart Disease Prediction using Decision Tree and Random Forest
## Project Overview
#### This project uses the Heart Disease Dataset to train and evaluate Decision Tree and Random Forest classifiers. The goal is to predict whether a patient has heart disease based on various medical attributes, analyze overfitting, interpret feature importance, and evaluate performance using cross-validation.

## Steps Implemented
1. Train a Decision Tree Classifier and visualize the tree.

2. Control Tree Depth to reduce overfitting and compare accuracy.

3. Train a Random Forest Classifier and compare results.

4. Interpret Feature Importances from the Random Forest model.

5. Evaluate with Cross-Validation to ensure model generalization.

## Key Results
Decision Tree → Accuracy = 1.0

Decision Tree (max_depth=4) → Accuracy ≈ 0.8967 

Cross-Validation Mean Accuracy → ~0.997

## Visualizations
Decision Tree Plot – Shows how the model splits features.

Feature Importance Chart – Displays which features most affect predictions.

## To Run notebook
### 1. Install dependencies:
```python
pip install pandas numpy matplotlib scikit-learn
```

## Conclusion
The Random Forest model performed slightly better and was more robust compared to a deep Decision Tree. Limiting tree depth helped reduce overfitting.
