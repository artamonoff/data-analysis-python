# Основы анализа данных в Python

## Jupyter Notebook & Lab

### Запуск

Запуск Jupyter Notebook из командной строки (Anaconda PowerShell Prompt в Windows, Terminal в MacOS) 

|OS|Комманда|
|-|-|
|Windows|`jupyter notebook`|
|Mac OS|`~/miniconda3/bin/jupyter notebook`|

Запуск Jupyter Lab из командной строки (Anaconda PowerShell Prompt в Windows, Terminal в MacOS) 

|OS|Комманда|
|-|-|
|Windows|`jupyter lab`|
|Mac OS|`~/miniconda3/bin/jupyter lab`|

### Jupyter Notebook

|Действие|Что делать|
|-|-|
|Создать новый|Нажать `Новый` -> Python 3|
|Закрыть сессию Jupyter|Нажать `Quit`|
|Закрыть ноутбук и ядро|меню `File` -> `Close and Halt`|

### Jupyter Lab

|Действие|Что делать|
|-|-|
|Создать новый|меню `File` -> `New` -> `Notebook`|
|Закрыть сессию Jupyter|меню `File` -> `Shut Down`|
|Закрыть ноутбук и ядро|меню `File` -> `Close and Shutdown Notebook`|

## Необходимые библиотеки Python

|Бибиотека|Описание|
|-|-|
|[`pandas`](https://pandas.pydata.org)|Табличные данные|
|[`numpy`](https://numpy.org)|Работа с массиванми данных, преобразование данных|
|[`statsmodels`](https://www.statsmodels.org)|Регрессионный анализ|
|[`scipy.stats`](https://docs.scipy.org/doc/scipy/reference/stats.html)|статистические методы (распределения и проч)|
|[`seaborn`](https://seaborn.pydata.org)|Визуализация статистических данных|
|[`matplotlib`](https://matplotlib.org)|Визуалиазция данных|
|[`plotly`](https://plotly.com/python/)|Визуалиазция данных|
|[`yfinance`](https://github.com/ranaroussi/yfinance)|Загрузка данных с `finance.yahoo.com`|
|[`pandas-datareader`](https://pandas-datareader.readthedocs.io/en/latest/)|Загразука данных из внешних БД (`FRED`, `finance.yahoo.com` etc)|

## Установка основных библиотек

В командной строке (Anaconda PowerShell Prompt в Windows, Terminal в MacOS) выполнить следующие команды (это нужно следать только один раз!)

- `conda install -c plotly plotly`
- `conda install pandas numpy scipy statsmodels`
- `conda install -c anaconda jupyter jupyterlab pandas-datareader seaborn`
- `conda install -c conda-forge yfinance matplotlib`
