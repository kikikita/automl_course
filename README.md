# AutoML Course

Ссылка на соревнование - [IEEE-CIS Fraud Detection](https://www.kaggle.com/competitions/ieee-fraud-detection/overview)

## Решения
- [EDA + AutoML submission](https://github.com/kikikita/automl_course/blob/main/automl-submission.ipynb) - ноутбук включающий работу с данными и baseline automl

- [Manual submission](https://github.com/kikikita/automl_course/blob/main/manual-submission.ipynb) - ноутбук с собственным решением

## Результаты экспериментов:

[Предсказания](https://github.com/kikikita/automl_course/tree/main/predictions) - 3 csv файла с предсказаниями от трех разных моделей.

| Submission | Private Score | Public Score |
|------------|---------------|--------------|
| AutoML     | 0.895426      | 0.926644     |
| Manual     | 0.903565      | 0.936054     |

Для построения собственного решения были использованы следующие библиотеки машинного обучения, основанные на градиентном бустинге:

- [XGBoost](https://xgboost.readthedocs.io/en/stable/)

Для оптимизации гиперпараметров были использованы следующи фреймворки:

- [Optuna](https://optuna.org/)
