# Визуализация с Seaborn & Plotly

Библиотека [`seaborn`](https://seaborn.pydata.org) позволяет визуализировать статистические данные и быстро строить широкий спектр 2D графиков.

Библиотека [`plotly`](https://plotly.com/python/) позволяет сроить широкий спектр 2D и 3D графиков с элементами интерактива.

Базовые графики:

- диаграмма рассеяния, в том том числе с подогнанной кривой (scatter plot)
- линейная диаграмма (line plot)
- гистограмма (histogram)
- столбчатая диаграмма (bar chart)
- коробчатая диаграмма, "ящик с усами" (box plot)
- круговая/кольцевая диаграмма (pie/doughnut chart)
- температурная диаграмма (heatmap)
- пузырькова диаграмма (bubble chart, фактически частный случай рассеяния)

## Библиотека Seaborn

`import seaborn as sns`

Основные методы `seaborn`

|График|Метод|Ссылка|
|-|-|-|
|диаграмма рассеяния|`.scatterplot()`|[ссылка](https://seaborn.pydata.org/generated/seaborn.scatterplot.html#seaborn.scatterplot)|
|диаграмма рассеяния с регрессией|`.regplot()`|[ссылка](https://seaborn.pydata.org/generated/seaborn.regplot.html#seaborn.regplot)|
|линейная диаграмма|`.lineplot()`|[ссылка](https://seaborn.pydata.org/generated/seaborn.lineplot.html#seaborn.lineplot)|
|гистограмма|`.histplot()`|[ссылка](https://seaborn.pydata.org/generated/seaborn.histplot.html#seaborn.histplot)|
|столбчатая диаграмма|`.histplot()`|[ссылка](https://seaborn.pydata.org/generated/seaborn.histplot.html#seaborn.histplot)|
|коробчатая диаграмма|`.boxplot()`|[ссылка](https://seaborn.pydata.org/generated/seaborn.boxplot.html#seaborn.boxplot)|
|температурная диаграмма|`.heatmap()`|[ссылка](https://seaborn.pydata.org/generated/seaborn.heatmap.html#seaborn.heatmap)|

Общие параметры графиков

|Параметр|Описание|
|-|-|
|`x,y`|переменные по осям|
|`hue`|от какой переменной будет зависеть цвет|
|`size`|от какой переменной будет зависеть размер|
|`style`|от какой переменной будет зависеть форма точки|
|`marker(s)`|форма точки|

## Библиотека Plotly

`import plotly.express as px`

|График|Метод|Ссылка|
|-|-|-|
|2d диаграмма рассеяния|`.scatter()`|[ссылка](https://plotly.com/python/line-and-scatter)|
|2d диаграмма рассеяния с регрессией|`.scatter()`|[ссылка](https://plotly.com/python/line-and-scatter)|
|линейная диаграмма|`.line()`|[ссылка](https://plotly.com/python/line-and-scatter)|
|гистограмма|`.histogram()`|[ссылка](https://plotly.com/python/histograms/)|
|столбчатая диаграмма|`.bar()`|[ссылка](https://plotly.com/python/bar-charts/)|
|коробчатая диаграмма|`.box()`|[ссылка](https://plotly.com/python/box-plots/)|
|круговая|`.pie()`|[ссылка](https://plotly.com/python/pie-charts/)|
|3d диаграмма рассеяния|`.scatter_3d()`|[ссылка](https://plotly.com/python/line-and-scatter)|

***Замечание*: интерфейс для построение графиков в `plotly`
`fig = ax.method()`
`# fig.update_layout()`
`fir.show()`