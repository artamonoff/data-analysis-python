# Домашнее задание №3

обновите пакет `seaborn` выполнив команду `conda install seaborn -c conda-forge`

## №1

Загрузите с `finance.yahoo.com` цену акций компании Google с 01 января 2005 по н.в.
Нарисуйте график для цены закрытия с использованием библиотеки `seaborn`

## №2

Загрузите из БД FRED **месячные** данные по следующим ставкам в один датафрейм (с 2000 г. по н.в.)
- 1-Year Treasury Bill
- Market Yield on U.S. Treasury Securities at 2-Year Constant Maturity
- Moody's Seasoned Aaa Corporate Bond Yield
- Moody's Seasoned Baa Corporate Bond Yield

Задайте месячный временной индекс и нарисуйте график со всеми ставками с использованием библиотеки `seaborn`

## №3

Для датафрейма из предыдущего задания нарисуйте диаграммы рассеяния с подогнанной прямой
- 1-Year Treasury Bill против Market Yield on U.S. Treasury Securities at 2-Year Constant Maturity
- Moody's Seasoned Aaa Corporate Bond Yield против Moody's Seasoned Baa Corporate Bond Yield

## №4

Импортируйте данные из файла `diamonds.csv`.
- Нарисуйте диаграмму рассеяния `carat против price` т.ч. цвет зависит от `cut` и форма зависит от `color`


