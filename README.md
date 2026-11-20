# Random Forest Glass Classification

## Project Overview
This project implements a Random Forest Classifier to classify different types of glass based on their chemical and physical properties.

## Dataset
- Source: Glass Identification Dataset (OpenML)
- Samples: 214
- Features: 9
- Target: Glass Type
- Classes: 6

## Methodology
1. Data Exploration and Preprocessing
2. Train-Test Split (80% / 20%)
3. Random Forest Classification
4. Model Evaluation using Accuracy, Precision, Recall, F1-Score, and Confusion Matrix
5. Feature Importance Analysis
6. Hyperparameter Tuning using RandomizedSearchCV
7. Comparison of Original and Tuned Models

## Results
- Original Training Accuracy: 100%
- Original Testing Accuracy: 81.4%
- Original Weighted F1-Score: Approximately 81%
- Most Important Features: Mg, Al, RI

## Tools and Libraries
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- Kaggle

## Project Links
**Kaggle Notebook:** https://www.kaggle.com/code/dimaw03/random-forest-glass-classification

**GitHub Repository:** https://github.com/Dimaalshraah/Random-Forest-Glass-Classification

## Conclusion
The Random Forest model achieved 81.4% test accuracy on the Glass Identification dataset. Hyperparameter tuning was performed using RandomizedSearchCV to explore alternative model configurations. The project demonstrates multiclass classification, model evaluation, feature importance analysis, and hyperparameter optimization.
