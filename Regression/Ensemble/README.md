# Summary of Ensemble

[<< Go back](../README.md)


## Ensemble structure
| Model                  |   Weight |
|:-----------------------|---------:|
| 1_Baseline             |        2 |
| 6_Default_RandomForest |        3 |

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.637739 |  nan        |
| auc       | 0.590278 |  nan        |
| f1        | 0.590164 |    0.284983 |
| accuracy  | 0.678571 |    0.475037 |
| precision | 0.666667 |    0.475037 |
| recall    | 1        |    0.198183 |
| mcc       | 0.282523 |    0.284983 |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.637739 |  nan        |
| auc       | 0.590278 |  nan        |
| f1        | 0.307692 |    0.475037 |
| accuracy  | 0.678571 |    0.475037 |
| precision | 0.666667 |    0.475037 |
| recall    | 0.2      |    0.475037 |
| mcc       | 0.223772 |    0.475037 |


## Confusion matrix (at threshold=0.475037)
|              |   Predicted as 0 |   Predicted as 1 |
|:-------------|-----------------:|-----------------:|
| Labeled as 0 |               34 |                2 |
| Labeled as 1 |               16 |                4 |

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
