# Tree-Based Machine Learning Algorithms

Tree-based algorithms are a popular class of machine learning methods that use decision trees as their core structure. They are widely used for both classification and regression tasks due to their interpretability and strong performance.

## Common Algorithms

- **Decision Tree**: A simple, interpretable model that splits data based on feature values.
- **Random Forest**: An ensemble of decision trees that improves accuracy and reduces overfitting.
- **Gradient Boosted Trees (e.g., XGBoost, LightGBM, CatBoost)**: Sequentially build trees to correct errors of previous trees, achieving high predictive power.
- **Extra Trees (Extremely Randomized Trees)**: Similar to random forests but with more randomness in feature splits.

## Advantages

- Handle both numerical and categorical data
- Require little data preprocessing
- Capture non-linear relationships
- Feature importance estimation

## Disadvantages

- Can overfit on noisy data (especially single trees)
- Ensemble methods can be computationally intensive

## Example Libraries

- `scikit-learn`
- `xgboost`
- `lightgbm`
- `catboost`

## References

- [scikit-learn Decision Trees](https://scikit-learn.org/stable/modules/tree.html)
- [XGBoost Documentation](https://xgboost.readthedocs.io/)
- [LightGBM Documentation](https://lightgbm.readthedocs.io/)
