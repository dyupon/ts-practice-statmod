# Общая структура

- Файлы с отдельными секциями лежат в папках ch<ch_num>
- Названия файлов имеют вид: ch<ch_num>-sect<sect_num>-<shortdescription>.tex
- Метадата лежит в таблице chdata.csv
- Добавлен PDF с оригинальными названиями тем (ts_questions.pdf)
- Готовность отдельных тем и общий прогресс можно дополнительно отмечать в README, изменяя [ ] на [x]

# Содержание

## Общая часть.
1. [x] Что такое периодограмма?
2. [x] Что такое тренд (разные варианты определения)? Как выглядит периодограмма тренда?
3. [x] Что такое периодическая компонента? Как выглядит ее периодограмма?
4. [x] Что такое шум? Как выглядит его периодограмма?
5. [x] Периодограмма как оценка спектральной плотности. Распределение значений. Сглаживание
периодограммы.
6. [x] Чем отличается сглаживание от выделения тренда?
7. [x] Что такое линейный фильтр, импульсная характеристика? Причинный фильтр, FIR.
 Характеристики фильтра через его воздействие на cos(2\pi \omega n) (или на комплексную
экспоненту) – АЧХ, ФЧХ.
9. [x] AЧХ фильтра скользящего среднего, зависимость от длины окна.
10. [x] АЧХ фильтра перехода к разностям (дифференцирования).
11. [x] Что такое запаздывание и отчего оно может возникать (на примере скользящего среднего)?
12. [x] Смещение при сглаживании фильтром скользящего среднего. Роль второй производной.
13. [x] Фильтр для подавления шума. Роль нормы коэффициентов фильтра.
14. [x] Как связаны периодограммы ряда до применения фильтра и после применения фильтра?
15. [x] Модели данных – аддитивная и мультипликативная.
16. [x] Методы стабилизации дисперсии в разных моделях (логарифмирование, извлечение квадратного
корня, …).
17. [x] Выделение тренда у ряда с сезонностью (выбор длины окна в скользящем среднем).
18. [x] Переход к разностям – плюсы и минусы (устранение тренда, превращение ряда в стационарный,
усиление вклада высоких частот).
19. [x] Скользящее среднее и скользящая медиана.
20. [x] Растекание частоты в периодограмме. Подправка длины ряда для ее устранения.
21. [x] Выделение тренда с помощью параметрической регрессии.
22. [x] Выделение тренда с помощью метода LOESS.
23. [x] Нахождение огибающей периодического ряда с помощью выделения тренда.
24. [x] Оценивание поведения дисперсии шума с помощью выделения тренда.
25. [x] Метод разложения Classical seasonal decomposition.
26. [x] Метод разложения STL.

## Метод SSA
1. [x] Как выбирать L.
2. [x] Последовательный SSA.
3. [ ] Слабая и сильная разделимость.
4. [ ] Компоненты смешались. Как понять, это слабая или сильная разделимость?
5. [x] Как идентифицировать тренд?
6. [x] Как идентифицировать периодичность?
7. [x] Использование матрицы взвешенных корреляций.
8. [x] Элементарные восстановленные компоненты.
9. [x] Корни хар.полинома, сигнальные и лишние.
10. [x] Оценка параметров в SSA
11. [x] Прогноз.
12. [x] Доверительные интервалы.
13. [x] Автоматическая идентификация.
14. [x] Заполнение пропусков (на 30.04.2016 еще не было рассказано).
15. [x] Теплиц SSA для стац. рядов.
16. [x] Projection SSA, выделение лин.тренда.
17. [x] Улучшение разделимости с помощью вращения в выбранном подпространстве: Iterative
O-SSA (слабая и сильная разделимость) и DerivSSA (сильная разделимость).
18. [x] Аппроксимация Cadzow SSA.
19. [x] MSSA для анализа многомерных временных рядов. Когда лучше анализировать ряды
вместе, а когда отдельно?
20. [x] 2D-SSA для разложения изображения.

## ARIMA и прочее
1. [x] AR(p) – модель, запись в виде с оператором сдвига.
2. [x] AR(p) и модель сигнала в SSA.
3. [x] Вид автоковариационной функции acf для AR(p).
4. [x] Вид pacf для AR(p).
5. [x] Модель MA(q), вид acf и pacf.
6. [x] ARMA(p,q).
7. [x] Дифференцирование, ARIMA(p,d,q).
8. [x] Seasonal ARIMA(p,d,q)(P,D,Q).
9. [x] Exponential smoothing, модели тренда, ES и ARIMA.
