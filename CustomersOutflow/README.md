# Отток клиентов из банка

Из «Бета-Банка» стали уходить клиенты. Каждый месяц. Немного, но заметно. Банковские маркетологи посчитали: сохранять текущих клиентов дешевле, чем привлекать новых.

## Цель исследования:

Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. Вам предоставлены исторические данные о поведении клиентов и расторжении договоров с банком.

Постройте модель с предельно большим значением F1-меры. Чтобы сдать проект успешно, нужно довести метрику до 0.59.

## Итог исследования:

Для полученных данных, чтобы получить наибольшие и необходимые значения F1-меры, необходимо использовать:

Модель случайного леса
Увеличение обучающей выборки
Подбор порога вероятности положительного класса
В таком случае метрики на протестированной модели получили данные значения:

F1-мера - 0.962
Площадь под кривой ROC - 0.83
Полнота - 0.85
Точность - 0.84

## Стек технологий:

`pandas`, `matplotlib`, `numpy`, `seaborn`, `scikit-learn`, `imbalanced-learn`.