# Разработать метод преобразования данных для защиты персональной информации

## Описание проекта

Нужно защитить данные клиентов страховой компании. Для этого необходимо разработать такой метод преобразования данных, чтобы по ним было сложно восстановить персональную информацию. После этого обосновать корректность его работы.
Нужно защитить данные, чтобы при преобразовании качество моделей машинного обучения не ухудшилось. Подбирать наилучшую модель не требуется.

## Описание данных

**Признаки**: пол, возраст и зарплата застрахованного, количество членов его семьи.
**Целевой признак**: количество страховых выплат клиенту за последние 5 лет.

## Используемые инструменты

`sklearn` `pandas` `numpy` `seaborn`

### Модели

`LinearRegression`

### Метрики

`r2_score`