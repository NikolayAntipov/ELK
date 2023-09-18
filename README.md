# Домашнее задание к занятию «ELK» - Антипов Н.С.

## Задание 1. Elasticsearch
Установите и запустите Elasticsearch, после чего поменяйте параметр cluster_name на случайный.

Приведите скриншот команды 'curl -X GET 'localhost:9200/_cluster/health?pretty', сделанной на сервере с установленным Elasticsearch. Где будет виден нестанд>

Скриншот до
[Текст ссылки](https://github.com/NikolayAntipov/ELK/blob/main/img/1_1JPG.JPG)

Скриншот после изменения настроек
[Текст ссылки](https://www.example.com)


## Задание 2. Kibana
Установите и запустите Kibana.

Приведите скриншот интерфейса Kibana на странице http://<ip вашего сервера>:5601/app/dev_tools#/console, где будет выполнен запрос GET /_cluster/health?pret>

Скриншот
[Текст ссылки](https://www.example.com)

## Задание 3. Logstash
Установите и запустите Logstash и Nginx. С помощью Logstash отправьте access-лог Nginx в Elasticsearch.

Приведите скриншот интерфейса Kibana, на котором видны логи Nginx.

[Текст ссылки](https://www.example.com)

## Задание 4. Filebeat.
Установите и запустите Filebeat. Переключите поставку логов Nginx с Logstash на Filebeat.

Приведите скриншот интерфейса Kibana, на котором видны логи Nginx, которые были отправлены через Filebeat.

[Текст ссылки](https://www.example.com)
