# sberbank-covid19-forecast-2020
Моё решение соревнования прогнозирования [covid19](https://ods.ai/competitions/sberbank-covid19-forecast)

Лучшее публичное решение. Лучшее решение в 1 туре, 4 место во втором

Интервью про модель [nplus1](https://nplus1.ru/blog/2020/04/29/black-box-wanga)

[![Интервью](https://img.youtube.com/vi/wYDMYt135no/0.jpg)](https://www.youtube.com/watch?v=wYDMYt135no)

## covid_simple.ipynb
- Прогноз для мира, регионов России и Америки
- Каждый день предсказывается последовательно 
- Обработка данных
- Добавление новых фич
- Модели (Линейная регрессия, Adaboost Regressor, Случайный лес, Xgboost, SGDRegressor, catboost, Lightgbm, keras, pytorch)
- Оценка ошибки MALE
- Сравнение моделей
- Графики
- Создание submission
## covid_delta7.ipynb
- Семь моделей на каждый день(завтра, послезавтра и тд)


![Графики](https://github.com/vlomme/sberbank-covid19-forecast-2020/blob/master/img/1.jpg)
![Графики](https://github.com/vlomme/sberbank-covid19-forecast-2020/blob/master/img/4.jpg)
![Графики](https://github.com/vlomme/sberbank-covid19-forecast-2020/blob/master/img/3.jpg)
![Графики](https://github.com/vlomme/sberbank-covid19-forecast-2020/blob/master/img/2.jpg)
