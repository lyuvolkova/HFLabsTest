# Перенос таблицы из Confluence в Google-таблицы

## Задание
В [базе знаний](https://confluence.hflabs.ru/pages/viewpage.action?pageId=1181220999) есть информация о кодах ответа нашего API.

Необходимо написать скрипт, который парсит эту табличку и переносит ее в гуглодоку. Предусмотреть, что в будущем необходимо будет синхронизировать данные в гуглодоке, если что-то изменится в базе знаний.

В результате нужно прислать:

* ссылку на код на гитхабе;

* ссылку на гуглодоку с перенесенной табличкой;

* информацию, сколько времени заняло выполнение задания.

Предпочтительный язык для выполнения задания — go. Допустимые языки — python, ruby.


## Решение

Задание выполнено в двух вариантах: 
1. Запрос таблицы по API Confluence, парсинг HTML и сохранение в Google-таблицу без форматирования.
2. Сохранение формулы в Google-таблицу.

## Результат

[Google-таблицa](https://docs.google.com/spreadsheets/d/19yimGlxzvTzFAzAf6WmdFSrKpuWvRFFVPDRTteGC8Rw/edit#gid=0)

* [Лист1](https://docs.google.com/spreadsheets/d/19yimGlxzvTzFAzAf6WmdFSrKpuWvRFFVPDRTteGC8Rw/edit#gid=0) соответствует варианту 1
* [Лист2](https://docs.google.com/spreadsheets/d/19yimGlxzvTzFAzAf6WmdFSrKpuWvRFFVPDRTteGC8Rw/edit#gid=1854544084) - варианту 2 