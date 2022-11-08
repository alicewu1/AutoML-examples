# Summary of Ensemble

[<< Go back](../README.md)


## Ensemble structure
| Model             |   Weight |
|:------------------|---------:|
| 3_Default_Xgboost |        1 |

### Metric details
|           |   Black/African American |   Multi-racial |   Other Race |       White |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|-------------------------:|---------------:|-------------:|------------:|-----------:|------------:|---------------:|----------:|
| precision |                 0.655172 |       0.357143 |     0.688172 |    0.784594 |   0.745138 |    0.62127  |       0.733477 |  0.631893 |
| recall    |                 0.476134 |       0.111111 |     0.627451 |    0.893609 |   0.745138 |    0.527076 |       0.745138 |  0.631893 |
| f1-score  |                 0.551486 |       0.169492 |     0.65641  |    0.835561 |   0.745138 |    0.553237 |       0.733625 |  0.631893 |
| support   |               838        |      45        |  1020        | 2519        |   0.745138 | 4422        |    4422        |  0.631893 |


## Confusion matrix
|                                   |   Predicted as Black/African American |   Predicted as Multi-racial |   Predicted as Other Race |   Predicted as White |
|:----------------------------------|--------------------------------------:|----------------------------:|--------------------------:|---------------------:|
| Labeled as Black/African American |                                   399 |                           1 |                       112 |                  326 |
| Labeled as Multi-racial           |                                     0 |                           5 |                        23 |                   17 |
| Labeled as Other Race             |                                   101 |                           4 |                       640 |                  275 |
| Labeled as White                  |                                   109 |                           4 |                       155 |                 2251 |

## Learning curves
![Learning curves](learning_curves.png)
## Confusion Matrix

![Confusion Matrix](confusion_matrix.png)


## Normalized Confusion Matrix

![Normalized Confusion Matrix](confusion_matrix_normalized.png)


## ROC Curve

![ROC Curve](roc_curve.png)


## Precision Recall Curve

![Precision Recall Curve](precision_recall_curve.png)



[<< Go back](../README.md)
