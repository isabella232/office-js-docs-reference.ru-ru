| Класс | Поля | Описание |
|:---|:---|:---|
|[Application](/javascript/api/excel/excel.application)|[Calculate (Калкулатионтипе: Excel. Калкулатионтипе)](/javascript/api/excel/excel.application#calculate-calculationtype-)|Пересчитывает данные во всех открытых в текущий момент книгах Excel.|
||[калкулатионмоде](/javascript/api/excel/excel.application#calculationmode)|Возвращает режим вычислений, используемый в книге в соответствии с константами в Excel. Калкулатионмоде.|
|[Binding](/javascript/api/excel/excel.binding)|[getRange()](/javascript/api/excel/excel.binding#getrange--)|Возвращает представленный привязкой диапазон.|
||[getTable()](/javascript/api/excel/excel.binding#gettable--)|Возвращает представленную привязкой таблицу.|
||[getText()](/javascript/api/excel/excel.binding#gettext--)|Возвращает представленный привязкой текст.|
||[id](/javascript/api/excel/excel.binding#id)|Представляет идентификатор привязки.|
||[type](/javascript/api/excel/excel.binding#type)|Возвращает тип привязки.|
|[BindingCollection](/javascript/api/excel/excel.bindingcollection)|[getItem(id: string)](/javascript/api/excel/excel.bindingcollection#getitem-id-)|Возвращает объект привязки по идентификатору.|
||[getItemAt(index: number)](/javascript/api/excel/excel.bindingcollection#getitemat-index-)|Возвращает объект привязки с учетом его положения в массиве элементов.|
||[count](/javascript/api/excel/excel.bindingcollection#count)|Возвращает число привязок в коллекции.|
||[items](/javascript/api/excel/excel.bindingcollection#items)|Получает загруженные дочерние элементы в этой коллекции.|
|[Chart](/javascript/api/excel/excel.chart)|[delete()](/javascript/api/excel/excel.chart#delete--)|Удаляет объект диаграммы.|
||[height](/javascript/api/excel/excel.chart#height)|Задает высоту объекта диаграммы (в пунктах).|
||[left](/javascript/api/excel/excel.chart#left)|Расстояние в пунктах от левого края диаграммы до начала листа.|
||[name](/javascript/api/excel/excel.chart#name)|Задает имя объекта диаграммы.|
||[Axes](/javascript/api/excel/excel.chart#axes)|Представляет оси диаграммы.|
||[dataLabels](/javascript/api/excel/excel.chart#datalabels)|Представляет метки данных на диаграмме.|
||[format](/javascript/api/excel/excel.chart#format)|Инкапсулирует свойства формата для области диаграммы.|
||[списком](/javascript/api/excel/excel.chart#legend)|Представляет условные обозначения для диаграммы.|
||[series](/javascript/api/excel/excel.chart#series)|Представляет один ряд данных или коллекцию рядов данных в диаграмме.|
||[заголовок](/javascript/api/excel/excel.chart#title)|Задает название указанной диаграммы, включая текст, видимость, положение и форматирование заголовка.|
||[setData (sourceData: Range, seriesBy?: Excel. Чартсериесби)](/javascript/api/excel/excel.chart#setdata-sourcedata--seriesby-)|Сбрасывает исходные данные для диаграммы.|
||[setPosition (startCell: \| строка диапазона, endCell?: \| строка диапазона)](/javascript/api/excel/excel.chart#setposition-startcell--endcell-)|Располагает диаграмму относительно ячеек на листе.|
||[top](/javascript/api/excel/excel.chart#top)|Задает расстояние от верхнего края объекта до верха строки 1 (на рабочем листе) или в верхней части области диаграммы (на диаграмме).|
||[width](/javascript/api/excel/excel.chart#width)|Задает ширину объекта диаграммы (в пунктах).|
|[ChartAreaFormat](/javascript/api/excel/excel.chartareaformat)|[fill](/javascript/api/excel/excel.chartareaformat#fill)|Представляет формат заливки объекта, включая сведения о форматировании фона.|
||[font](/javascript/api/excel/excel.chartareaformat#font)|Представляет атрибуты шрифта (имя, размер шрифта, цвет и т. д.) для текущего объекта.|
|[ChartAxes](/javascript/api/excel/excel.chartaxes)|[категоряксис](/javascript/api/excel/excel.chartaxes#categoryaxis)|Представляет ось категорий на диаграмме.|
||[сериесаксис](/javascript/api/excel/excel.chartaxes#seriesaxis)|Представляет ось ряда данных для объемной диаграммы.|
||[valueAxis](/javascript/api/excel/excel.chartaxes#valueaxis)|Представляет ось значений для оси.|
|[ChartAxis](/javascript/api/excel/excel.chartaxis)|[majorUnit](/javascript/api/excel/excel.chartaxis#majorunit)|Обозначает интервал между двумя основными делениями.|
||[maximum](/javascript/api/excel/excel.chartaxis#maximum)|Представляет максимальное значение на оси значений.|
||[minimum](/javascript/api/excel/excel.chartaxis#minimum)|Представляет минимальное значение на оси значений.|
||[minorUnit](/javascript/api/excel/excel.chartaxis#minorunit)|Представляет интервал между двумя промежуточными делениями.|
||[format](/javascript/api/excel/excel.chartaxis#format)|Представляет форматирование объекта диаграммы, в том числе форматирование линий и шрифта.|
||[majorGridlines](/javascript/api/excel/excel.chartaxis#majorgridlines)|Возвращает объект линии сетки, который представляет основные линии сетки для указанной оси.|
||[minorGridlines](/javascript/api/excel/excel.chartaxis#minorgridlines)|Возвращает объект Gridlines, который представляет вспомогательные линии сетки для указанной оси.|
||[заголовок](/javascript/api/excel/excel.chartaxis#title)|Обозначает название оси.|
|[ChartAxisFormat](/javascript/api/excel/excel.chartaxisformat)|[font](/javascript/api/excel/excel.chartaxisformat#font)|Задает атрибуты шрифта (имя, размер шрифта, цвет и т. д.) для элемента оси диаграммы.|
||[line](/javascript/api/excel/excel.chartaxisformat#line)|Задает форматирование линии диаграммы.|
|[ChartAxisTitle](/javascript/api/excel/excel.chartaxistitle)|[format](/javascript/api/excel/excel.chartaxistitle#format)|Задает формат заголовка оси диаграммы.|
||[text](/javascript/api/excel/excel.chartaxistitle#text)|Указывает название оси.|
||[visible](/javascript/api/excel/excel.chartaxistitle#visible)|Указывает, является ли название оси Visible.|
|[ChartAxisTitleFormat](/javascript/api/excel/excel.chartaxistitleformat)|[font](/javascript/api/excel/excel.chartaxistitleformat#font)|Задает атрибуты шрифта названия оси диаграммы, такие как имя шрифта, размер шрифта, цвет и т. д.|
|[ChartCollection](/javascript/api/excel/excel.chartcollection)|[Добавить (тип: Excel. ChartType, sourceData: Range, seriesBy?: Excel. Чартсериесби)](/javascript/api/excel/excel.chartcollection#add-type--sourcedata--seriesby-)|Создает диаграмму.|
||[getItem(name: string)](/javascript/api/excel/excel.chartcollection#getitem-name-)|Возвращает диаграмму по ее имени.|
||[getItemAt(index: number)](/javascript/api/excel/excel.chartcollection#getitemat-index-)|Возвращает диаграмму с учетом ее положения в коллекции.|
||[count](/javascript/api/excel/excel.chartcollection#count)|Возвращает количество диаграмм на листе.|
||[items](/javascript/api/excel/excel.chartcollection#items)|Получает загруженные дочерние элементы в этой коллекции.|
|[ChartDataLabelFormat](/javascript/api/excel/excel.chartdatalabelformat)|[fill](/javascript/api/excel/excel.chartdatalabelformat#fill)|Представляет формат заливки для текущей метки данных диаграммы.|
||[font](/javascript/api/excel/excel.chartdatalabelformat#font)|Представляет атрибуты шрифта (имя, размер шрифта, цвет и т. д.) для подписи данных диаграммы.|
|[ChartDataLabels](/javascript/api/excel/excel.chartdatalabels)|[position](/javascript/api/excel/excel.chartdatalabels#position)|Значение DataLabelPosition, которое представляет положение метки данных.|
||[format](/javascript/api/excel/excel.chartdatalabels#format)|Задает формат подписей данных диаграммы, включающий форматирование текста и заливки.|
||[символ](/javascript/api/excel/excel.chartdatalabels#separator)|Строка, представляющая разделитель, который используется для меток данных на диаграмме.|
||[showBubbleSize](/javascript/api/excel/excel.chartdatalabels#showbubblesize)|Указывает, отображается ли размер пузырька метки данных.|
||[showCategoryName](/javascript/api/excel/excel.chartdatalabels#showcategoryname)|Указывает, отображается ли имя категории меток данных.|
||[showLegendKey](/javascript/api/excel/excel.chartdatalabels#showlegendkey)|Указывает, является ли ключ условных обозначений метки данных видимым.|
||[showPercentage](/javascript/api/excel/excel.chartdatalabels#showpercentage)|Указывает, отображается ли процент меток данных.|
||[showSeriesName](/javascript/api/excel/excel.chartdatalabels#showseriesname)|Указывает, отображается ли имя ряда подписей данных.|
||[showValue](/javascript/api/excel/excel.chartdatalabels#showvalue)|Указывает, отображается ли значение метки данных.|
|[ChartFill](/javascript/api/excel/excel.chartfill)|[clear()](/javascript/api/excel/excel.chartfill#clear--)|Очищает цвет заливки элемента диаграммы.|
||[setSolidColor(color: string)](/javascript/api/excel/excel.chartfill#setsolidcolor-color-)|Устанавливает форматирование заливки элемента диаграммы на единый цвет.|
|[ChartFont](/javascript/api/excel/excel.chartfont)|[bold](/javascript/api/excel/excel.chartfont#bold)|Указывает, является ли шрифт полужирным.|
||[color](/javascript/api/excel/excel.chartfont#color)|Цветовое представление текста в формате HTML (например, #FF0000 представляет собой красный цвет).|
||[italic](/javascript/api/excel/excel.chartfont#italic)|Указывает, применяется ли курсив.|
||[name](/javascript/api/excel/excel.chartfont#name)|Имя шрифта (например, "Calibri")|
||[size](/javascript/api/excel/excel.chartfont#size)|Размер шрифта (например, 11).|
||[underline](/javascript/api/excel/excel.chartfont#underline)|Тип подчеркивания, применяемый для шрифта.|
|[ChartGridlines](/javascript/api/excel/excel.chartgridlines)|[format](/javascript/api/excel/excel.chartgridlines#format)|Представляет форматирование линий сетки диаграммы.|
||[visible](/javascript/api/excel/excel.chartgridlines#visible)|Указывает, отображаются ли линии сетки оси.|
|[ChartGridlinesFormat](/javascript/api/excel/excel.chartgridlinesformat)|[line](/javascript/api/excel/excel.chartgridlinesformat#line)|Представляет форматирование линий диаграммы.|
|[ChartLegend](/javascript/api/excel/excel.chartlegend)|[накладывающиеся](/javascript/api/excel/excel.chartlegend#overlay)|Указывает, должно ли легенда диаграммы пересекаться с основной частью диаграммы.|
||[position](/javascript/api/excel/excel.chartlegend#position)|Указывает положение условных обозначений на диаграмме.|
||[format](/javascript/api/excel/excel.chartlegend#format)|Представляет форматирование легенды диаграммы, включая заливку и шрифт.|
||[visible](/javascript/api/excel/excel.chartlegend#visible)|Указывает, является ли ChartLegend видимым.|
|[ChartLegendFormat](/javascript/api/excel/excel.chartlegendformat)|[fill](/javascript/api/excel/excel.chartlegendformat#fill)|Представляет формат заливки объекта, включая сведения о форматировании фона.|
||[font](/javascript/api/excel/excel.chartlegendformat#font)|Представляет атрибуты шрифта, такие как имя шрифта, размер шрифта, цвет и т. д.|
|[ChartLineFormat](/javascript/api/excel/excel.chartlineformat)|[clear()](/javascript/api/excel/excel.chartlineformat#clear--)|Очищает формат линий элемента диаграммы.|
||[color](/javascript/api/excel/excel.chartlineformat#color)|HTML-код цвета, представляющий цвет линий в диаграмме.|
|[ChartPoint](/javascript/api/excel/excel.chartpoint)|[format](/javascript/api/excel/excel.chartpoint#format)|Инкапсулирует свойства формата точки диаграммы.|
||[value](/javascript/api/excel/excel.chartpoint#value)|Возвращает значение точки диаграммы.|
|[ChartPointFormat](/javascript/api/excel/excel.chartpointformat)|[fill](/javascript/api/excel/excel.chartpointformat#fill)|Представляет формат заливки диаграммы, включающий сведения о форматировании фона.|
|[ChartPointsCollection](/javascript/api/excel/excel.chartpointscollection)|[getItemAt(index: number)](/javascript/api/excel/excel.chartpointscollection#getitemat-index-)|Получение точки на основании ее положения в ряду.|
||[count](/javascript/api/excel/excel.chartpointscollection#count)|Возвращает количество точек диаграммы в ряду.|
||[items](/javascript/api/excel/excel.chartpointscollection#items)|Получает загруженные дочерние элементы в этой коллекции.|
|[ChartSeries](/javascript/api/excel/excel.chartseries)|[name](/javascript/api/excel/excel.chartseries#name)|Задает имя ряда в диаграмме.|
||[format](/javascript/api/excel/excel.chartseries#format)|Представляет форматирование ряда диаграммы, включая формат заливки и линий.|
||[этапах](/javascript/api/excel/excel.chartseries#points)|Возвращает коллекцию всех точек ряда.|
|[ChartSeriesCollection](/javascript/api/excel/excel.chartseriescollection)|[getItemAt(index: number)](/javascript/api/excel/excel.chartseriescollection#getitemat-index-)|Возвращает ряд в зависимости от его позиции в коллекции.|
||[count](/javascript/api/excel/excel.chartseriescollection#count)|Возвращает количество рядов в коллекции.|
||[items](/javascript/api/excel/excel.chartseriescollection#items)|Получает загруженные дочерние элементы в этой коллекции.|
|[ChartSeriesFormat](/javascript/api/excel/excel.chartseriesformat)|[fill](/javascript/api/excel/excel.chartseriesformat#fill)|Представляет формат заливки ряда диаграммы, включая сведения о форматировании фона.|
||[line](/javascript/api/excel/excel.chartseriesformat#line)|Представляет форматирование линий.|
|[ChartTitle](/javascript/api/excel/excel.charttitle)|[накладывающиеся](/javascript/api/excel/excel.charttitle#overlay)|Указывает, будет ли название диаграммы накладываться на диаграмму.|
||[format](/javascript/api/excel/excel.charttitle#format)|Представляет форматирование названия диаграммы, включая формат заливки и шрифта.|
||[text](/javascript/api/excel/excel.charttitle#text)|Задает текст заголовка диаграммы.|
||[visible](/javascript/api/excel/excel.charttitle#visible)|Указывает, является ли название диаграммы Visible.|
|[ChartTitleFormat](/javascript/api/excel/excel.charttitleformat)|[fill](/javascript/api/excel/excel.charttitleformat#fill)|Представляет формат заливки объекта, включая сведения о форматировании фона.|
||[font](/javascript/api/excel/excel.charttitleformat#font)|Представляет атрибуты шрифта (имя шрифта, размер шрифта, цвет и т. д.) для объекта.|
|[NamedItem](/javascript/api/excel/excel.nameditem)|[getRange()](/javascript/api/excel/excel.nameditem#getrange--)|Возвращает объект Range, сопоставленный с именем.|
||[name](/javascript/api/excel/excel.nameditem#name)|Имя объекта.|
||[type](/javascript/api/excel/excel.nameditem#type)|Указывает тип значения, возвращаемого формулой имени.|
||[value](/javascript/api/excel/excel.nameditem#value)|Представляет значение, вычисленное по формуле имени.|
||[visible](/javascript/api/excel/excel.nameditem#visible)|Указывает, является ли объект видимым.|
|[NamedItemCollection](/javascript/api/excel/excel.nameditemcollection)|[getItem(name: string)](/javascript/api/excel/excel.nameditemcollection#getitem-name-)|Возвращает объект NamedItem, используя его имя.|
||[items](/javascript/api/excel/excel.nameditemcollection#items)|Получает загруженные дочерние элементы в этой коллекции.|
|[Range](/javascript/api/excel/excel.range)|[clear(applyTo?: Excel.ClearApplyTo)](/javascript/api/excel/excel.range#clear-applyto-)|Очищает значения, формат, заливку, границу диапазона и т. д.|
||[Delete (Shift: Excel. Делетешифтдиректион)](/javascript/api/excel/excel.range#delete-shift-)|Удаляет ячейки, связанные с диапазоном.|
||[formulas](/javascript/api/excel/excel.range#formulas)|Представляет формулу в формате A1.|
||[formulasLocal](/javascript/api/excel/excel.range#formulaslocal)|Представляет формулу в нотации стиля A1 на языке пользователя и в соответствии с его языковым стандартом.|
||[getBoundingRect (anotherRange: \| строка Range)](/javascript/api/excel/excel.range#getboundingrect-anotherrange-)|Возвращает наименьший объект диапазона, включающий в себя заданные диапазоны.|
||[getCell(row: number, column: number)](/javascript/api/excel/excel.range#getcell-row--column-)|Получает объект диапазона, содержащий одну ячейку, по номеру строки и столбца.|
||[getColumn(column: number)](/javascript/api/excel/excel.range#getcolumn-column-)|Возвращает столбец в диапазоне.|
||[getEntireColumn()](/javascript/api/excel/excel.range#getentirecolumn--)|Получает объект, представляющий весь столбец диапазона (например, если текущий диапазон представляет ячейки "B4: E11", `getEntireColumn` а — диапазон, представляющий столбцы "б:е").|
||[getEntireRow()](/javascript/api/excel/excel.range#getentirerow--)|Получает объект, представляющий всю строку диапазона (например, если текущий диапазон представляет ячейки "B4: E11", `GetEntireRow` а — диапазон, представляющий строки "4:11").|
||[пересечение (anotherRange: \| строка Range)](/javascript/api/excel/excel.range#getintersection-anotherrange-)|Возвращает объект диапазона, представляющий собой прямоугольное пересечение заданных диапазонов.|
||[Жетластцелл ()](/javascript/api/excel/excel.range#getlastcell--)|Возвращает последнюю ячейку в диапазоне.|
||[Жетластколумн ()](/javascript/api/excel/excel.range#getlastcolumn--)|Возвращает последний столбец в диапазоне.|
||[Жетластров ()](/javascript/api/excel/excel.range#getlastrow--)|Возвращает последнюю строку в диапазоне.|
||[getOffsetRange(rowOffset: number, columnOffset: number)](/javascript/api/excel/excel.range#getoffsetrange-rowoffset--columnoffset-)|Возвращает объект, представляющий диапазон, который смещен от указанного диапазона.|
||[getRow(row: number)](/javascript/api/excel/excel.range#getrow-row-)|Возвращает строку из диапазона.|
||[INSERT (Shift: Excel. Инсертшифтдиректион)](/javascript/api/excel/excel.range#insert-shift-)|Вставляет ячейку или диапазон ячеек на лист вместо этого диапазона, а также сдвигает другие ячейки, чтобы освободить место.|
||[numberFormat](/javascript/api/excel/excel.range#numberformat)|Представляет код числового формата Excel для заданного диапазона.|
||[address](/javascript/api/excel/excel.range#address)|Указывает ссылку на диапазон в стиле a1.|
||[addressLocal](/javascript/api/excel/excel.range#addresslocal)|Указывает ссылку на диапазон для указанного диапазона на языке пользователя.|
||[cellCount](/javascript/api/excel/excel.range#cellcount)|Задает количество ячеек в диапазоне.|
||[Число](/javascript/api/excel/excel.range#columncount)|Задает общее количество столбцов в диапазоне.|
||[columnIndex](/javascript/api/excel/excel.range#columnindex)|Задает номер столбца первой ячейки в диапазоне.|
||[format](/javascript/api/excel/excel.range#format)|Возвращает объект формата, в который включены шрифт, заливка, границы, выравнивание и другие свойства диапазона.|
||[Стро](/javascript/api/excel/excel.range#rowcount)|Возвращает общее количество строк в диапазоне.|
||[rowIndex](/javascript/api/excel/excel.range#rowindex)|Возвращает номер строки первой ячейки диапазона.|
||[text](/javascript/api/excel/excel.range#text)|Текстовые значения указанного диапазона.|
||[valueTypes](/javascript/api/excel/excel.range#valuetypes)|Указывает тип данных в каждой ячейке.|
||[worksheet](/javascript/api/excel/excel.range#worksheet)|Лист, содержащий текущий диапазон.|
||[select()](/javascript/api/excel/excel.range#select--)|Выбирает указанный диапазон в пользовательском интерфейсе Excel.|
||[values](/javascript/api/excel/excel.range#values)|Представляет необработанные значения указанного диапазона.|
|[RangeBorder](/javascript/api/excel/excel.rangeborder)|[color](/javascript/api/excel/excel.rangeborder#color)|HTML-код, представляющий цвет линии границы в формате #RRGGBB (например, "FFA500") или в виде ключевого слова (например, "orange").|
||[сидеиндекс](/javascript/api/excel/excel.rangeborder#sideindex)|Постоянное значение, указывающее определенную сторону границы.|
||[style](/javascript/api/excel/excel.rangeborder#style)|Одна из констант стиля линии, определяющая стиль линии границы.|
||[weight](/javascript/api/excel/excel.rangeborder#weight)|Определяет толщину границы вокруг диапазона.|
|[RangeBorderCollection](/javascript/api/excel/excel.rangebordercollection)|[GetItem (index: Excel. Бордериндекс)](/javascript/api/excel/excel.rangebordercollection#getitem-index-)|Возвращает объект границы по его имени.|
||[getItemAt(index: number)](/javascript/api/excel/excel.rangebordercollection#getitemat-index-)|Возвращает объект границы по его индексу.|
||[count](/javascript/api/excel/excel.rangebordercollection#count)|Количество объектов границы в коллекции.|
||[items](/javascript/api/excel/excel.rangebordercollection#items)|Получает загруженные дочерние элементы в этой коллекции.|
|[RangeFill](/javascript/api/excel/excel.rangefill)|[clear()](/javascript/api/excel/excel.rangefill#clear--)|Сброс фона диапазона.|
||[color](/javascript/api/excel/excel.rangefill#color)|HTML-код цвета, представляющий цвет фона формы #RRGGBB (например, "FFA500") или в виде именованного цвета HTML (например, "Апельсин")|
|[RangeFont](/javascript/api/excel/excel.rangefont)|[bold](/javascript/api/excel/excel.rangefont#bold)|Указывает, является ли шрифт полужирным.|
||[color](/javascript/api/excel/excel.rangefont#color)|Цветовое представление текста в формате HTML (например, #FF0000 представляет собой красный цвет).|
||[italic](/javascript/api/excel/excel.rangefont#italic)|Задает курсивное начертание шрифта.|
||[name](/javascript/api/excel/excel.rangefont#name)|Имя шрифта (например, "Calibri").|
||[size](/javascript/api/excel/excel.rangefont#size)|размер шрифта|
||[underline](/javascript/api/excel/excel.rangefont#underline)|Тип подчеркивания, применяемый для шрифта.|
|[RangeFormat](/javascript/api/excel/excel.rangeformat)|[horizontalAlignment](/javascript/api/excel/excel.rangeformat#horizontalalignment)|Представляет выравнивание по горизонтали для указанного объекта.|
||[borders](/javascript/api/excel/excel.rangeformat#borders)|Коллекция объектов границ, которые применяются ко всему диапазону.|
||[fill](/javascript/api/excel/excel.rangeformat#fill)|Возвращает объект заливки, определенный для всего диапазона.|
||[font](/javascript/api/excel/excel.rangeformat#font)|Возвращает объект шрифта, определенный для всего диапазона.|
||[verticalAlignment](/javascript/api/excel/excel.rangeformat#verticalalignment)|Представляет выравнивание по вертикали для указанного объекта.|
||[wrapText](/javascript/api/excel/excel.rangeformat#wraptext)|Указывает, переносит ли Excel текст в объекте.|
|[Table](/javascript/api/excel/excel.table)|[delete()](/javascript/api/excel/excel.table#delete--)|Удаляет таблицу.|
||[Жетдатабодиранже ()](/javascript/api/excel/excel.table#getdatabodyrange--)|Получает объект диапазона, связанный с телом данных таблицы.|
||[Жесеадерровранже ()](/javascript/api/excel/excel.table#getheaderrowrange--)|Получает объект диапазона, связанный со строкой заголовков таблицы.|
||[getRange()](/javascript/api/excel/excel.table#getrange--)|Получает объект диапазона, связанный со всей таблицей.|
||[Жеттоталровранже ()](/javascript/api/excel/excel.table#gettotalrowrange--)|Получает объект диапазона, связанный со строкой итогов таблицы.|
||[name](/javascript/api/excel/excel.table#name)|Имя таблицы.|
||[столбцы](/javascript/api/excel/excel.table#columns)|Представляет коллекцию всех столбцов в таблице.|
||[id](/javascript/api/excel/excel.table#id)|Возвращает значение, однозначно идентифицирующее таблицу в данной книге.|
||[строки](/javascript/api/excel/excel.table#rows)|Представляет коллекцию всех строк в таблице.|
||[шовхеадерс](/javascript/api/excel/excel.table#showheaders)|Указывает, отображается ли строка заголовков.|
||[шовтоталс](/javascript/api/excel/excel.table#showtotals)|Указывает, отображается ли строка итогов.|
||[style](/javascript/api/excel/excel.table#style)|Постоянное значение, представляющее стиль таблицы.|
|[TableCollection](/javascript/api/excel/excel.tablecollection)|[Add (Address: \| строка диапазона, hasHeaders: Boolean)](/javascript/api/excel/excel.tablecollection#add-address--hasheaders-)|Создание таблицы.|
||[getItem(key: string)](/javascript/api/excel/excel.tablecollection#getitem-key-)|Получает таблицу по имени или идентификатору.|
||[getItemAt(index: number)](/javascript/api/excel/excel.tablecollection#getitemat-index-)|Получает таблицу на основании ее позиции в коллекции.|
||[count](/javascript/api/excel/excel.tablecollection#count)|Возвращает количество таблиц в книге.|
||[items](/javascript/api/excel/excel.tablecollection#items)|Получает загруженные дочерние элементы в этой коллекции.|
|[TableColumn](/javascript/api/excel/excel.tablecolumn)|[delete()](/javascript/api/excel/excel.tablecolumn#delete--)|Удаляет столбец из таблицы.|
||[Жетдатабодиранже ()](/javascript/api/excel/excel.tablecolumn#getdatabodyrange--)|Получает объект диапазона, связанный с текстом данных столбца.|
||[Жесеадерровранже ()](/javascript/api/excel/excel.tablecolumn#getheaderrowrange--)|Получает объект диапазона, связанный со строкой заголовков столбца.|
||[getRange()](/javascript/api/excel/excel.tablecolumn#getrange--)|Получает объект диапазона, связанный со всем столбцом.|
||[Жеттоталровранже ()](/javascript/api/excel/excel.tablecolumn#gettotalrowrange--)|Получает объект диапазона, связанный со строкой итогов столбца.|
||[name](/javascript/api/excel/excel.tablecolumn#name)|Задает имя столбца таблицы.|
||[id](/javascript/api/excel/excel.tablecolumn#id)|Возвращает уникальный ключ, идентифицирующий столбец в таблице.|
||[index](/javascript/api/excel/excel.tablecolumn#index)|Возвращает номер индекса столбца в коллекции столбцов таблицы.|
||[values](/javascript/api/excel/excel.tablecolumn#values)|Представляет необработанные значения указанного диапазона.|
|[TableColumnCollection](/javascript/api/excel/excel.tablecolumncollection)|[Add (index?: число, Values?: массив<массив<логический \| \| номер строки>> \| логический \| \| номер строки, Name?: строка)](/javascript/api/excel/excel.tablecolumncollection#add-index--values--name-)|Добавляет новый столбец в таблицу.|
||[GetItem (ключ: число \| строка)](/javascript/api/excel/excel.tablecolumncollection#getitem-key-)|Возвращает объект column по имени или идентификатору.|
||[getItemAt(index: number)](/javascript/api/excel/excel.tablecolumncollection#getitemat-index-)|Возвращает столбец на основании его позиции в коллекции.|
||[count](/javascript/api/excel/excel.tablecolumncollection#count)|Возвращает количество столбцов в таблице.|
||[items](/javascript/api/excel/excel.tablecolumncollection#items)|Получает загруженные дочерние элементы в этой коллекции.|
|[TableRow](/javascript/api/excel/excel.tablerow)|[delete()](/javascript/api/excel/excel.tablerow#delete--)|Удаляет строку из таблицы.|
||[getRange()](/javascript/api/excel/excel.tablerow#getrange--)|Получает объект диапазона, связанный со всей строкой.|
||[index](/javascript/api/excel/excel.tablerow#index)|Возвращает номер индекса строки в коллекции строк таблицы.|
||[values](/javascript/api/excel/excel.tablerow#values)|Представляет необработанные значения указанного диапазона.|
|[TableRowCollection](/javascript/api/excel/excel.tablerowcollection)|[Add (index?: число, Values?: массив<массив<логический номер \| строки \|>> \| логический \| \| номер строки)](/javascript/api/excel/excel.tablerowcollection#add-index--values-)|Добавляет одну или несколько строк в таблицу.|
||[getItemAt(index: number)](/javascript/api/excel/excel.tablerowcollection#getitemat-index-)|Получает строку на основании ее позиции в коллекции.|
||[count](/javascript/api/excel/excel.tablerowcollection#count)|Возвращает количество строк в таблице.|
||[items](/javascript/api/excel/excel.tablerowcollection#items)|Получает загруженные дочерние элементы в этой коллекции.|
|[Workbook](/javascript/api/excel/excel.workbook)|[Функцией getselectedrange ()](/javascript/api/excel/excel.workbook#getselectedrange--)|Получает текущий выделенный диапазон из книги.|
||[application](/javascript/api/excel/excel.workbook#application)|Представляет экземпляр приложения Excel, который содержит эту книгу.|
||[bindings](/javascript/api/excel/excel.workbook#bindings)|Представляет коллекцию привязок, включенных в книгу.|
||[псевдоним](/javascript/api/excel/excel.workbook#names)|Представляет коллекцию именованных элементов в книге (именованные диапазоны и константы).|
||[Table](/javascript/api/excel/excel.workbook#tables)|Представляет коллекцию таблиц, сопоставленных с книгой.|
||[листов](/javascript/api/excel/excel.workbook#worksheets)|Представляет коллекцию листов, сопоставленных с книгой.|
|[Worksheet](/javascript/api/excel/excel.worksheet)|[activate()](/javascript/api/excel/excel.worksheet#activate--)|Активация листа в пользовательском интерфейсе Excel.|
||[delete()](/javascript/api/excel/excel.worksheet#delete--)|Удаляет лист из книги.|
||[getCell(row: number, column: number)](/javascript/api/excel/excel.worksheet#getcell-row--column-)|Получает объект диапазона, содержащий одну ячейку, по номеру строки и столбца.|
||[GetString (Address?: строка)](/javascript/api/excel/excel.worksheet#getrange-address-)|Получает объект Range, представляющий отдельный прямоугольный блок ячеек, заданный по адресу или имени.|
||[name](/javascript/api/excel/excel.worksheet#name)|Отображаемое имя листа.|
||[position](/javascript/api/excel/excel.worksheet#position)|Положение листа (начиная с нуля) в книге.|
||[темп](/javascript/api/excel/excel.worksheet#charts)|Возвращает коллекцию диаграмм, которые являются частью листа.|
||[id](/javascript/api/excel/excel.worksheet#id)|Возвращает значение, однозначно идентифицирующее лист в данной книге.|
||[Table](/javascript/api/excel/excel.worksheet#tables)|Коллекция таблиц, имеющихся на листе.|
||[visibility](/javascript/api/excel/excel.worksheet#visibility)|Видимость листа.|
|[WorksheetCollection](/javascript/api/excel/excel.worksheetcollection)|[Добавить (имя?: строка)](/javascript/api/excel/excel.worksheetcollection#add-name-)|Добавляет новый лист в книгу.|
||[Жетактивеворкшит ()](/javascript/api/excel/excel.worksheetcollection#getactiveworksheet--)|Получает текущий активный лист в книге.|
||[getItem(key: string)](/javascript/api/excel/excel.worksheetcollection#getitem-key-)|Получает объект листа по его имени или ИД.|
||[items](/javascript/api/excel/excel.worksheetcollection#items)|Получает загруженные дочерние элементы в этой коллекции.|
