# Проект 1. Анализ базы данных резюме с сайта HeadHunter


## Оглавление
[1. Описание проекта](#Описание-проекта)  
[2. Какой кейс решаем?](#Какой-кейс-решаем)   
[3. Требования к оформлению ноутбука-решения](#требования-к-оформлению-ноутбука-решения)  
[4. Результаты](#результаты)   
[5. Использованные инструменты и библиотеки](#использованные-инструменты-и-библиотеки)  
[6. Графики в plotly](#графики-в-plotly)   
[7. Ссылки на данные](#ссылки-на-данные)

## Описание проекта
Работа происходит с базой данных соискателей с сайта HeadHunter. 

⭐ Компания HeadHunter хочет построить модель, которая бы автоматически определяла примерный уровень заработной платы, подходящей пользователю, исходя из информации, которую он указал о себе. Но, как вы знаете, прежде чем построить модель, данные необходимо преобразовать, исследовать и очистить. В этом и состоит наша с вами задача!

[к оглавлению](#Оглавление)

## Какой кейс решаем?

Наш проект будет состоять из четырёх частей:

1. Базовый анализ структуры данных

2. Преобразование данных

3. Разведывательный анализ

4. Очистка данных

[к оглавлению](#Оглавление)

## Требования к оформлению ноутбука-решения

* Решение оформляется только в Jupyter Notebook.
* Решение оформляется в соответствии с ноутбуком-шаблоном.
* Каждое задание выполняется в отдельной ячейке, выделенной под задание (в шаблоне они помечены как ваш код здесь). Не следует создавать множество ячеек для решения задачи — это создаёт неудобства при проверке.
* Код для каждого задания оформляется в одной-двух jupyter-ячейках (не стоит создавать множество ячеек для решения задачи, это усложняет проверку).
* Решение должно использовать только пройденный материал: переменные, основные структуры данных (списки, словари, множества), циклы, функции, библиотеки numpy, pandas, matplotlib, seaborn, plotly. Если вы думаете, что для решения необходимо воспользоваться сторонними библиотеками или инструментами (например Excel), другими языками программирования или неизученными конструкциями, вы ошибаетесь :) Все задания решаются с помощью уже знакомых методов.
* Код должен быть читаемым и понятным: имена переменных и функций отражают их сущность, важно избегать многострочных конструкций и условий.
* Пользуйтесь руководством PEP 8.
* Графики оформляются в соответствии с теми правилами, которые мы приводили в модуле по визуализации данных.
* Обязательное требование: графики должны содержать название, отражающее их суть, и подписи осей.
* Выводы к графикам оформляются в формате Markdown под самим графиком в отдельной ячейке (в шаблоне они помечены как ваши выводы здесь). Выводы должны быть представлены в виде небольших связанных предложений на русском языке.

[к оглавлению](#Оглавление)

## Результаты:

Проведен анализ и очистка данных, также составлен отчет о заимосвязях данных

## Выводы:

Получен практический опыт по работе с реальными данными

[к оглавлению](#Оглавление)

## Использованные инструменты и библиотеки:
* numpy
* pandas
* seaborn
* plotly
* matplotlib

[к оглавлению](#Оглавление)

## Графики в plotly

* [Графики в plotly](https://nbviewer.org/github/MariaKhanova/HeadHunterProject/tree/master/plotly/)

    * ['Распределение возраста соискателей'](https://nbviewer.org/github/MariaKhanova/HeadHunterProject/blob/master/plotly/histogram_1.html)
    * ['Распределение опыта работы(месяц) соискателей'](https://nbviewer.org/github/MariaKhanova/HeadHunterProject/blob/master/plotly/histogram_2.html)
    * ['Распределение желаемой з/п соискателей'](https://nbviewer.org/github/MariaKhanova/HeadHunterProject/blob/master/plotly/histogram_3.html)
    * ['Медианная з/п по уровню образования'](https://nbviewer.org/github/MariaKhanova/HeadHunterProject/blob/master/plotly/bar_1.html)
    * ['Распределение з/п по городам'](https://nbviewer.org/github/MariaKhanova/HeadHunterProject/blob/master/plotly/box.html)
    * ['Медианная з/п по готовности к командировкам/переезду'](https://nbviewer.org/github/MariaKhanova/HeadHunterProject/blob/master/plotly/bar_2.html)
    * ['Медианная з/п по образованию и возрасту'](https://nbviewer.org/github/MariaKhanova/HeadHunterProject/blob/master/plotly/heatmap_1.html)
    * ['Зависимость опыта работы от возраста'](https://nbviewer.org/github/MariaKhanova/HeadHunterProject/blob/master/plotly/scatter_1.html)
    * ['Количество соискателей готовых к удаленной работе и перездам по городам'](https://nbviewer.org/github/MariaKhanova/HeadHunterProject/blob/master/plotly/scatter_2.html)
    * ["Медианная з/п по признакам 'Пол' и 'Oпыт работы (год)'"](https://nbviewer.org/github/MariaKhanova/HeadHunterProject/blob/master/plotly/heatmap_2.html)

[к оглавлению](#Оглавление)

## Ссылки на данные:

* [Данные поиска вакансий](https://drive.google.com/drive/folders/12lBX1DDcScC5uJl7sNZYyVJMeKjviv8_)
* [Данные валют](https://drive.google.com/drive/folders/12lBX1DDcScC5uJl7sNZYyVJMeKjviv8_)

[к оглавлению](#Оглавление)