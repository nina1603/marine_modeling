1. Файл First.ipynb (можно посмотреть здесь:
http://nbviewer.jupyter.org/github/nina1603/marine_modeling/blob/master/First.ipynb )

Здесь содержится основной аналитический код. В самом конце пока что конечный вариант определения ячейки сетки, в которой находится выбранная точка. Я пока не додумалась, как использовать здесь minimize из scipy.optimize, так что пока что это топорная работа поиска ячейки, на которой функционал примет минимальное значение. Работает на одной точке порядка 1.5 часа, что, естественно, не очень. Буду думать над оптимизацией.

2.Файл visualisation.ipynb ( http://nbviewer.jupyter.org/github/nina1603/marine_modeling/blob/master/visualisation.ipynb )

Просто картиночки. Не могу это воспроизвести на windows, так как туда у меня лично не устанавливается basemap, на linux он почему-то виснет на визуализации сетки на карте, так что пока - в маленьком формате.

3. Файл cellIdentificator.ipynb (http://nbviewer.jupyter.org/github/nina1603/marine_modeling/blob/master/cellIdentificator.ipynb)

Это старая версия First, но пусть пока побудет тут.
