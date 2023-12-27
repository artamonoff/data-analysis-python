# Кластеризация данных в Python

Базовые методы машинного обучения реализованы в библиотеке [scikit-learn](https://scikit-learn.org/stable/)

Основные методы [кластеризации](https://scikit-learn.org/stable/modules/clustering.html#clustering) (обучение без учителя)
- [K-средних](https://scikit-learn.org/stable/modules/clustering.html#k-means)
- [Иерархическая](https://scikit-learn.org/stable/modules/clustering.html#hierarchical-clustering)
- [DBSCAN](https://scikit-learn.org/stable/modules/clustering.html#dbscan)

## Алгоритм кластеризации

1. Предварительная обработка данных: удаление пропущенных значений и нормировка (z-нормировка, min/max-нормировка, робастная нормировка)
2. Выбор метода и его инициализация (задаём число кластеров)
3. Разбивка данных на кластеры (`.fit(X)`, `.predict(X)` или сразу `.fit_predict(X)`). Получаем кластерную переменную
4. Интерпретация кластеров (если получится)/Визуалиазция
5. По необходимости выбираем оптимально число кластеров (относительно выбранных метрик)

__Замечание__: можно выбрать как считать расстояние между объектами (обычно евклидово)

## Кластеризация в `scikit-leart`

Нормализация данных: `sklearn.preprocessing`

Кластеризация: `sklearn.cluster`

Метрики качества разбиения: `sklearn.metrics`