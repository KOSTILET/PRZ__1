# Практическая работа № 1: Сбор логов
## Цель работы: 
- Создать 2 виртуальные машины на базе ОС Debian 12
- Обеспечить между ними сетевой обмен
- Включить на 1й из ВМ передачу логов по протоколу rsyslog на 2ю ВМ
- Установить и настроить получение логов на сервер с использованием Loki
- Установить и настроить получение логов на сервер с использованием Loki (signoz.io)

## Ход работы

## `rsyslog`

### Установка `rsyslog` на сервер

![image](https://i.imgur.com/Hx0ZQwl.png)

### Настройка модулей и добавление правил`rsyslog`

![image](https://i.imgur.com/5yxWZco.png)
![image](https://i.imgur.com/r4UQ21z.png)

### Применение конфигурации `rsyslog`

![image](https://i.imgur.com/mV6Bnpi.png)

### Установка `rsyslog` на клиент

![image](https://i.imgur.com/ebqJl7D.png)

### Добавление правила пересылки логов на сервер

![image](https://i.imgur.com/88FaeeH.png)

### Применение конфигурации `rsyslog`

![image](https://i.imgur.com/12wbcXJ.png)

### Просмотр полученных логов на сервере

![image](https://i.imgur.com/wIHehVk.png)

## Loki

### Запуск Loki

![image](https://i.imgur.com/F4s1hKh.png)
![image](https://i.imgur.com/Yxg1jmf.png)

### Редактирование и запуск `promtail` на клиенте

![image](https://i.imgur.com/aJXapXE.png)
![image](https://i.imgur.com/rJBW1G1.png)

### Просмотр логов клиента в Grafana

![image](https://i.imgur.com/cS4p8No.png)

## Signoz

### Запуск Signoz

### Установка `Signoz` на сервер

![image](https://i.imgur.com/cLfImsv.png)

### Рабочая панель Signoz

![image](https://i.imgur.com/hIulihU.png)

### Редактирование конфигурации клиентского приложения для отправки данных в Signoz

![image](https://i.imgur.com/PSIjlyj.png)

![image](https://i.imgur.com/pcDQc3h.png)

### Запуск клиентского приложения

![image](https://i.imgur.com/TAPpcpW.png)

### Информация о приложении в Signoz

![image](https://i.imgur.com/NRgjXRk.png)




PRZ-1
