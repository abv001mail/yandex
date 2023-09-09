# Определение стоимости автомобилей.

### Тема обучения
Численные методы.

### Задачи проекта
Разработка системы рекомендации стоимости автомобиля на основе его описания.  
Значение метрики RMSE должно быть меньше 2500.

### Описание проекта
Сервис по продаже автомобилей с пробегом разрабатывает приложение, чтобы привлечь новых клиентов. В нём можно будет узнать рыночную стоимость своего автомобиля. Необходимо построить модель, которая умеет её определять. В нашем распоряжении данные о технических характеристиках, комплектации и ценах других автомобилей.

### Используемые библиотеки
catboost, lightgbm, sklearn, pandas, numpy, tqdm.

### Итог
Лучший результат показала модель LightGBM.  
Метрика RMSE = 1573.
