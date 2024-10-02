# Toxic Comment Classifier

This project is a machine learning-based classifier for detecting toxic comments in Russian texts.

## Features
- Logistic Regression with TF-IDF vectorization
- Grid Search for hyperparameter tuning
- Customizable threshold for precision-recall balance


## Example
```python
comment = "Это очень плохой комментарий"
result = predict_toxicity(grid_search_recall, comment)
print(f"Toxic: {'Yes' if result == 1 else 'No'}")
