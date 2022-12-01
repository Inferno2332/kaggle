# Summary of Ensemble

[<< Go back](../README.md)


## Ensemble structure
| Model                                 |   Weight |
|:--------------------------------------|---------:|
| 10_RandomForest                       |        1 |
| 11_RandomForest                       |        4 |
| 11_RandomForest_GoldenFeatures        |        1 |
| 11_RandomForest_SelectedFeatures      |        3 |
| 13_NeuralNetwork                      |        1 |
| 3_DecisionTree                        |        1 |
| 6_Default_NeuralNetwork               |        1 |
| 7_Default_RandomForest_GoldenFeatures |        4 |
| 8_Xgboost                             |        1 |
| 9_Xgboost                             |        2 |

## Metric details
|           |     score |   threshold |
|:----------|----------:|------------:|
| logloss   | 0.307693  | nan         |
| auc       | 0.533807  | nan         |
| f1        | 0.173506  |   0.0897609 |
| accuracy  | 0.903     |   0.123295  |
| precision | 0.141509  |   0.123295  |
| recall    | 1         |   0.060899  |
| mcc       | 0.0354346 |   0.0939916 |


## Metric details with threshold from accuracy metric
|           |      score |   threshold |
|:----------|-----------:|------------:|
| logloss   | 0.307693   |  nan        |
| auc       | 0.533807   |  nan        |
| f1        | 0.0180072  |    0.123295 |
| accuracy  | 0.903      |    0.123295 |
| precision | 0.141509   |    0.123295 |
| recall    | 0.00961538 |    0.123295 |
| mcc       | 0.0134546  |    0.123295 |


## Confusion matrix (at threshold=0.123295)
|              |   Predicted as 0 |   Predicted as 1 |
|:-------------|-----------------:|-----------------:|
| Labeled as 0 |            15215 |               91 |
| Labeled as 1 |             1545 |               15 |

## Learning curves
![Learning curves](learning_curves.png)
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
