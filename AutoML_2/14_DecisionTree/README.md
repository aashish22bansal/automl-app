# Summary of 14_DecisionTree

[<< Go back](../README.md)


## Decision Tree
- **n_jobs**: -1
- **criterion**: friedman_mse
- **max_depth**: 4
- **explain_level**: 1

## Validation
 - **validation_type**: kfold
 - **k_folds**: 5
 - **shuffle**: True

## Optimized metric
rmse

## Training time

11.1 seconds

### Metric details:
| Metric   |     Score |
|:---------|----------:|
| MAE      | 0.161804  |
| MSE      | 0.0471706 |
| RMSE     | 0.217188  |
| R2       | 0.918267  |
| MAPE     | 0.209923  |



## Learning curves
![Learning curves](learning_curves.png)

## Permutation-based Importance
![Permutation-based Importance](permutation_importance.png)
## True vs Predicted

![True vs Predicted](true_vs_predicted.png)


## Predicted vs Residuals

![Predicted vs Residuals](predicted_vs_residuals.png)



[<< Go back](../README.md)
