# Аналитика в авиакомпании
В данной работе произведен анализ данных двух запросов из базз данных авиакомпании «F9», выполняющей внутренние пассажирские авиаперевозки. 
В работе был проанализирован спрос пассажиров на рейсы в различные города и на рейсы, выполняющиеся различными моделями самолетов.

## Описание данных 
В работе использовались результаты двух запросов. В первом содержится информация о:
- model — модели самолета
- flights_amount — количество рейсов для каждой модели самолетов model в сентябре 2018 года

Во втором запроме содержится информация о:
- city — городах
- average_flights — среднем количестве рейсов, прибывающих в город city за день в августе 2018 года

## Цель работы
Определить предпочтения пассажиров, покупающих билеты, относительно модели самолета и пункта назначения

## Используемые инструменты 
- библиотеки pandas, numpy
- визуализация выполнена  с помощью matplotlib и seaborn
- данные обогащены при помощи requests, BeautifulSoup