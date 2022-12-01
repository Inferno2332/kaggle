# Summary of 12_NeuralNetwork

[<< Go back](../README.md)


## Neural Network
- **n_jobs**: -1
- **dense_1_size**: 32
- **dense_2_size**: 4
- **learning_rate**: 0.05
- **explain_level**: 2

## Validation
 - **validation_type**: split
 - **train_ratio**: 0.75
 - **shuffle**: True
 - **stratify**: True

## Optimized metric
logloss

## Training time

33.1 seconds

## Metric details
|           |     score |   threshold |
|:----------|----------:|------------:|
| logloss   | 0.318136  | nan         |
| auc       | 0.48944   | nan         |
| f1        | 0.169326  |   0.0029984 |
| accuracy  | 0.89713   |   0.125305  |
| precision | 0.0924938 |   0.0029984 |
| recall    | 1         |   0.0029984 |
| mcc       | 0         |   0.0029984 |


## Metric details with threshold from accuracy metric
|           |       score |   threshold |
|:----------|------------:|------------:|
| logloss   |  0.318136   |  nan        |
| auc       |  0.48944    |  nan        |
| f1        |  0.0147643  |    0.125305 |
| accuracy  |  0.89713    |    0.125305 |
| precision |  0.0646766  |    0.125305 |
| recall    |  0.00833333 |    0.125305 |
| mcc       | -0.0105445  |    0.125305 |


## Confusion matrix (at threshold=0.125305)
|              |   Predicted as 0 |   Predicted as 1 |
|:-------------|-----------------:|-----------------:|
| Labeled as 0 |            15118 |              188 |
| Labeled as 1 |             1547 |               13 |

## Learning curves
![Learning curves](learning_curves.png)

## Permutation-based Importance
![Permutation-based Importance](permutation_importance.png)
## Confusion Matrix

![Confusion Matrix](confusion_matrix.png)


## Normalized Confusion Matrix

![Normalized Confusion Matrix](confusion_matrix_normalized.png)


## ROC Curve

![ROC Curve](roc_curve.png)


## Kolmogorov-Smirnov Statistic

![Kolmogorov-Smirnov Statistic](ks_statistic.png)


## Precision-Recall Curve

![Precision-Recall Curve](precision_recall_curve.png)


## Calibration Curve

![Calibration Curve](calibration_curve_curve.png)


## Cumulative Gains Curve

![Cumulative Gains Curve](cumulative_gains_curve.png)


## Lift Curve

![Lift Curve](lift_curve.png)



[<< Go back](../README.md)
