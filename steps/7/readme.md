# Возвращаемся к фукнции-сокращателю. 

## Правим код функции index.py - https://github.com/beeeeemaya/yandex-scale-2020-lab-serverless/blob/master/steps/7/index.py

## Переменные окружения
Теперь создадим у функции три переменные окружения: 
* название базы данных
* endpoint
* USE_METADATA_CREDENTIALS, выставив этой переменной значение 1.

Важно: в эндпоинте нужно указать протокол grpcs://(добавить ручками), а база данных должна начинаться с /ru-central1/...). 
В примере будут использоваться database и endpoint. 

## Добавляем файлик requirements.txt
После этого кладем рядом с index.py файл requirements.txt https://github.com/beeeeemaya/yandex-scale-2020-lab-serverless/blob/master/steps/7/requirements.txt


