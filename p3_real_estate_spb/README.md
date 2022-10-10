# yandex_practicum
## Исследование объявлений о продаже квартир

### Цель исследования
В нашем распоряжении имеются данные сервиса Яндекс.Недвижимость — архив объявлений о продаже квартир в Санкт-Петербурге и соседних населённых пунктах за несколько лет.

Задача — установить параметры, влияющие на рыночную стоимость объектов недвижимости. Это позволит построить автоматизированную систему, которая будет отслеживать аномалии и мошенническую деятельность.

### Используемые инструменты (библиотеки и навыки)
- `python`
- `pandas`
- `matplotlib`
- `seaborn`
- предобработка данных
- категоризация данных
- визуализация данных
- матрица корреляции
- анализ распределения значений признака
- анализ выбросов

### Ход исследования
- Загрузка и обзор данных
- Предобработка данных (пропуски, типы данных)
- Расчет доли жилой площади, доли кухни, цены квадратного метра
- Категоризация количества комнат, количества этажей в доме, общей площади, этажа квартиры, расстояния до центра
- Выделение дня недели, месяца и года из даты публикации отбъявления
- Исследование факторов, влияющих на стоимость квартиры (распределение, выбросы, визуализация)
- Расчет и визуализация матрицы корреляции 
- Анализ количества объявлений и цен за метр квадратный в разрезе населенных пунктов
- Анализ изменения цены по степени удаленности от центра
- Отличия квартир в центре от рынка недвижимости муниципального образования в целом  
- Выводы

В данном учебном проекте основное внимание уделено предобработке данных, анализу распределений и выбросов, визуализации данных.

