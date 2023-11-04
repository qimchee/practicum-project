## Прогнозирование заказов такси на следующий час. 

### Цель проекта
Чтобы привлекать больше водителей в период пиковой нагрузки, нужно спрогнозировать количество заказов такси на следующий час. Построить модель для такого предсказания.

### Навыки и инструменты

pandas

matplotlib.pyplot

catboost

numpy.logspace

statsmodels.tsa.seasonal.seasonal_decompose

statsmodels.tsa.stattools.adfuller

statsmodels.graphics.tsaplots.plot_acf

sklearn.model_selection.cross_val_score, GridSearchCV , train_test_split, TimeSeriesSplit 

sklearn.linear_model.LinearRegression 

sklearn.ensemble.RandomForestRegressor 

sklearn.metrics.make_scorer, mean_squared_error 

### Общий вывод

Был проведён анализ временных рядов. Лучшая тестовая метрика RMSE 44,03
