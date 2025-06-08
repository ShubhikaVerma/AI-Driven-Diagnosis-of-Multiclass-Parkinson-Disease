## 🧪 PD vs HC – Performance Metrics
| Classifier          | Macro Precision | Macro Recall | Macro F1 | Weighted Precision | Weighted Recall | Weighted F1 |
| ------------------- | --------------- | ------------ | -------- | ------------------ | --------------- | ----------- |
| Logistic Regression | 0.91            | 0.91         | 0.91     | 0.92               | 0.91            | 0.91        |
| SVM                 | 0.88            | 0.88         | 0.88     | 0.89               | 0.88            | 0.88        |
| CatBoost            | 0.91            | 0.91         | 0.91     | 0.92               | 0.91            | 0.91        |
| XGBoost             | 0.88            | 0.88         | 0.88     | 0.89               | 0.88            | 0.88        |
| Random Forest       | 0.91            | 0.91         | 0.91     | 0.92               | 0.91            | 0.91        |

## SMOTE APPLIED
| Classifier          | Macro Precision | Macro Recall | Macro F1 | Weighted Precision | Weighted Recall | Weighted F1 |
| ------------------- | --------------- | ------------ | -------- | ------------------ | --------------- | ----------- |
| Logistic Regression | 0.93            | 0.95         | 0.93     | 0.93               | 0.95            | 0.93        |
| SVM                 | 0.93            | 0.93         | 0.93     | 0.93               | 0.94            | 0.93        |
| CatBoost            | 0.96            | 0.94         | 0.93     | 0.94               | 0.95            | 0.95        |
| XGBoost             | 0.93            | 0.93         | 0.93     | 0.93               | 0.94            | 0.93        |
| Random Forest       | 0.93            | 0.93         | 0.93     | 0.93               | 0.94            | 0.93        |

## RFE +SMOTE
| Classifier          | Macro Precision | Macro Recall | Macro F1 | Weighted Precision | Weighted Recall | Weighted F1 |
| ------------------- | --------------- | ------------ | -------- | ------------------ | --------------- | ----------- |
| Logistic Regression | 0.88            | 0.95         | 0.91     | 0.95               | 0.93            | 0.93        |
| SVM                 | 0.89            | 0.93         | 0.93     | 0.94               | 0.93            | 0.91        |
| CatBoost            | 0.81            | 0.85         | 0.83     | 0.88               | 0.87            | 0.88        |
| XGBoost             | 0.86            | 0.95         | 0.89     | 0.94               | 0.92            | 0.92        |
| Random Forest       | 0.85            | 0.94         | 0.88     | 0.93               | 0.90            | 0.91        |

## 🧪 PD vs OTHER – Performance Metrics
| Classifier          | Macro Precision | Macro Recall | Macro F1 | Weighted Precision | Weighted Recall | Weighted F1 |
| ------------------- | --------------- | ------------ | -------- | ------------------ | --------------- | ----------- |
| Logistic Regression | 0.80            | 0.75         | 0.76     | 0.82               | 0.82            | 0.81        |
| AdaBoost            | 0.80            | 0.75         | 0.76     | 0.82               | 0.82            | 0.81        |
| Gradient            | 0.71            | 0.70         | 0.70     | 0.75               | 0.76            | 0.75        |
| SVM                 | 0.67            | 0.63         | 0.64     | 0.71               | 0.73            | 0.71        |
| CatBoost            | 0.65            | 0.62         | 0.63     | 0.70               | 0.72            | 0.70        |

## SMOTE Applied:
| Classifier          | Macro Precision | Macro Recall | Macro F1 | Weighted Precision | Weighted Recall | Weighted F1 |
| ------------------- | --------------- | ------------ | -------- | ------------------ | --------------- | ----------- |
| Logistic Regression | 0.78            | 0.78         | 0.78     | 0.82               | 0.82            | 0.82        |
| AdaBoost            | 0.77            | 0.76         | 0.77     | 0.81               | 0.81            | 0.81        |
| Gradient            | 0.72            | 0.72         | 0.72     | 0.77               | 0.77            | 0.77        |
| SVM                 | 0.67            | 0.63         | 0.64     | 0.71               | 0.73            | 0.71        |
| CatBoost            | 0.71            | 0.68         | 0.69     | 0.74               | 0.76            | 0.75        |

## ANOVA + SMOTE:

| Classifier          | Macro Precision | Macro Recall | Macro F1 | Weighted Precision | Weighted Recall | Weighted F1 |
| ------------------- | --------------- | ------------ | -------- | ------------------ | --------------- | ----------- |
| Logistic Regression | 0.76            | 0.73         | 0.74     | 0.79               | 0.79            | 0.79        |
| AdaBoost            | 0.72            | 0.70         | 0.71     | 0.76               | 0.77            | 0.76        |
| Gradient            | 0.80            | 0.81         | 0.80     | 0.84               | 0.83            | 0.83        |
| SVM                 | 0.82            | 0.82         | 0.82     | 0.85               | 0.85            | 0.85        |
| CatBoost            | 0.82            | 0.82         | 0.82     | 0.85               | 0.85            | 0.85        |

## 🧪 PD vs HC vs OTHER – Performance Metrics

| Classifier          | Macro Precision | Macro Recall | Macro F1 | Weighted Precision | Weighted Recall | Weighted F1 |
| ------------------- | --------------- | ------------ | -------- | ------------------ | --------------- | ----------- |
| Logistic Regression | 0.61            | 0.59         | 0.58     | 0.65               | 0.67            | 0.65        |
| AdaBoost            | 0.67            | 0.65         | 0.63     | 0.72               | 0.69            | 0.69        |
| XGBoost             | 0.60            | 0.58         | 0.58     | 0.65               | 0.66            | 0.64        |
| CatBoost            | 0.68            | 0.63         | 0.63     | 0.71               | 0.71            | 0.69        |

## SMOTE Applied

| Classifier          | Macro Precision | Macro Recall | Macro F1 | Weighted Precision | Weighted Recall | Weighted F1 |
| ------------------- | --------------- | ------------ | -------- | ------------------ | --------------- | ----------- |
| Logistic Regression | 0.61            | 0.63         | 0.61     | 0.66               | 0.67            | 0.66        |
| AdaBoost            | 0.58            | 0.59         | 0.56     | 0.66               | 0.63            | 0.62        |
| XGBoost             | 0.63            | 0.63         | 0.61     | 0.64               | 0.64            | 0.63        |
| CatBoost            | 0.63            | 0.63         | 0.61     | 0.68               | 0.68            | 0.67        |


## Backward Elimination + SMOTE:

| Classifier          | Macro Precision | Macro Recall | Macro F1 | Weighted Precision | Weighted Recall | Weighted F1 |
| ------------------- | --------------- | ------------ | -------- | ------------------ | --------------- | ----------- |
| Logistic Regression | 0.66            | 0.63         | 0.63     | 0.70               | 0.69            | 0.68        |
| AdaBoost            | 0.60            | 0.60         | 0.56     | 0.68               | 0.64            | 0.63        |
| XGBoost             | 0.63            | 0.66         | 0.62     | 0.69               | 0.67            | 0.67        |
| CatBoost            | 0.64            | 0.62         | 0.59     | 0.69               | 0.67            | 0.67        |
