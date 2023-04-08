# Описание, для реализации проекта

# Скачать проект по ссылке 

# git clone https://github.com/klanet/prometheus_stack.git

Выполняем в директории проекта 

# docker-compose up -d

Для настройки Grafana

Переходим по http://<IP-адрес сервера>:3000

Для авторизации вводим admin / illchangeitanyway
Настроим связку с Prometheus. Кликаем по иконке Configuration - Data Sources
Переходим к добавлению источника, нажав по Add data source
Среди списка источников данных находим и выбираем Prometheus, кликнув по Select
Задаем параметры для подключения к Prometheus (http://localhost:9090/ или хост машины, на которую проброшен порт)
Сохраняем настройки, кликнув по Save & Test
Добавим дашборд для мониторинга с node exporter. Кликаем по изображению плюса и выбираем Import. Вводим идентификатор дашборда. Для Node Exporter это 1860.
Кликаем Load — Grafana подгрузит дашборд из своего репозитория — выбираем в разделе Prometheus наш источник данных и кликаем по Import.

# Доступы к Jbpmn

 http://<адрес сервера>:8080/business-central/

webadmin/webadmin
