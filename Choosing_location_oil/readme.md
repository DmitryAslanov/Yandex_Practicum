# Выбор локации для разработки нефтяного месторождения

Статус проекта: | В плане :black_square_button: | Выполняется :black_square_button: | Завершён :white_check_mark: | 
:------------ | :-------------| :-------------| :-------------

## Задача:

Как сотруднику в добывающей компании, поставлена задача по выбору места разработки нефтяного месторождения, обеспечивающего наибольшую прибыль.

В нашем распоряжении исторические данные по пробам нефти в трёх регионах: в каждом 100 000 скважин, где измерили качество нефти и объём её запасов. Необходимо построить модель машинного обучения, которая поможет определить регион, где добыча принесёт наибольшую прибыль. При разработке нового месторождения планируется произвести разведочное бурение 500 скважин, оценить объём запасов нефти в них с помощью модели машинного обучения. Для добычи выбрать 200 скважин с наибольшими оценочными запасами нефти. Бюджет на разработку месторождения составляет 10 милиардов рублей. Доход с 1000 барелей нефти составляет 450 тысяч рублей. 

## Данные:

Данные геологоразведки трёх регионов находятся в файлах:
Структура данных:
- id — уникальный идентификатор скважины;
- f0, f1, f2 — три признака отражающих характеристики качества и объёма нефти;
- product — объём запасов в скважине (тыс. баррелей).

## Используемые библиотеки
- pandas
- numpy
- sklearn
- matplotlib
- seaborn

## Отработанные методы и навыки
- Исследовательский анализ данных;
- Построение моделей машинного обучения;
- Анализ техникой Bootstrap;
- Визуализация данных.
