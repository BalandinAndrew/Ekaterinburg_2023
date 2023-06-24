# Ekaterinburg_2023
Решение кейса "Самолет"

В наборе GitHub приложены последовательно:
Обработка данных датасета.lgp - файл программы Логином (бесплатной, общедоступной, г.Рязань) в котором расставлены метки "больше-меньше" по трейну.
train_out.csv - входной трейн из предобработки Логиномом для подачи в блокнот train
test_out.csv - входной тест из предобработки Логиномом для подачи в блокнот train
train.ipynb - блокнот выполнения прогнозной модели
catboost_model.bin - сохраненные веса обученной модели
Выполненный прогноз тренда.csv - выходная сабмиссия модели (прогнозы тренда цен)
Выполненный прогноз тренда цвет.csv - выходная сабмиссия прогноза тренда с показом принципа применения и подсчетом экономического эффекта
main.ipynb - выполнение прогноза из обученной модели и применение алгоритма формирования заказа на закупку
submission.xlsx - выходная сабмиссия алгоритма закупок (в форме, требуемой ТЗ)
test.xlsx - входной файл теста для main, без изменений от предоставленного организаторами
metric.py - функция подсчета цены для main, без изменений от предоставленного организаторами 

Подробно выполнение обоих действующих блокнотов приведено в скринкасте команды, тестовый прогон выполнен в colab и не требует каких-либо дополнительных действий.

