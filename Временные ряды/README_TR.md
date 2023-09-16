# Прогноз количества заказов для сервиса такси

## Описание проекта

Требуется спрогнозировать количество заказов такси на следующий час, чтобы привлекать больше водителей в период пиковой нагрузки.  Для этого необходимо выполнить  ресемплирование данных по одному часу временного ряда. Проанализировать данные. Обучить разные модели с различными гиперпараметрами. Сделать тестовую выборку размером 10% от исходных данных. Проверить данные на тестовой выборке и сделать выводы.

## Навыки и инструменты

- **python**
- **pandas**
- **numpy**
- statsmodels.tsa.seasonal.**seasonal_decompose**
- sklearn.model_selection.**TimeSeriesSplit**
- sklearn.model_selection.**GridSearchCV**
- sklearn.metrics.**mean_squared_error**
- sklearn.metrics.**make_scorer**
- sklearn.linear_model.**LinearRegression**
- sklearn.ensemble.**RandomForestRegressor**
- catboost.**CatBoostRegressor**
- **matplotlib**
- sklearn.**tune sklearn**
- statsmodels.tsa.stattools.**adfuller**
- statsmodels.tsa.stattools.**kpss**
- TimeSeriesSplit



## Общий вывод

Проведено исследование временного ряда на предмет трендовых и сезонных закономерностей, случайной составляющей. Проведено исследование трёх типов моделей, выбрана линейная регрессия.

