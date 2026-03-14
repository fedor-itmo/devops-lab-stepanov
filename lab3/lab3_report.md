University: [ITMO University](https://itmo.ru/ru/)  
Faculty: [FICT](https://fict.itmo.ru)  
Course: [Введение в веб технологии](https://itmo-ict-faculty.github.io/introduction-in-web-tech/)  
Year: 2025/2026  
Group: U4125  
Author: Stepanov Fedor Aleksandrovich  
Lab: Lab3   
Date of create: 13.03.2026  
Date of finished:   

# Лабораторная работа 3
## Отчет:
1. Создал папку prometheus и в ней файл prometheus.yml с нужным содержимым
![Снимок экрана](images%20lab3/Снимок%20экрана%20(188).png?raw=true)
2. Запустил контейнер для сбора системных метрик
![Снимок экрана](images%20lab3/Снимок%20экрана%20(189).png?raw=true)
3. Проверил, что метрики собираются с помощью команды curl
![Снимок экрана](images%20lab3/Снимок%20экрана%20(190).png?raw=true)
4. Создал том данных, а также общую сеть для Node Exporter, Prometheus и Grafana
![Снимок экрана](images%20lab3/Снимок%20экрана%20(191).png?raw=true)
5. Запустил контейнер Prometheus для чего пришлось создать файл prometheus.yml в блокноте
![Снимок экрана](images%20lab3/Снимок%20экрана%20(192).png?raw=true)
![Снимок экрана](images%20lab3/Снимок%20экрана%20(193).png?raw=true)
6. Проверил работу в браузере, все с первого раза открылось корректно
![Снимок экрана](images%20lab3/Снимок%20экрана%20(194).png?raw=true)
7. Создал том данных и запустил контейнер Grafana
![Снимок экрана](images%20lab3/Снимок%20экрана%20(195).png?raw=true)
8. Проверил работу в браузере
![Снимок экрана](images%20lab3/Снимок%20экрана%20(196).png?raw=true)
![Снимок экрана](images%20lab3/Снимок%20экрана%20(197).png?raw=true)
9. Добавил источник данных Prometheus
![Снимок экрана](images%20lab3/Снимок%20экрана%20(198).png?raw=true)
10. Проверил работу всех контейнеров
![Снимок экрана](images%20lab3/Снимок%20экрана%20(199).png?raw=true)
11. Убедился что метрики собираются
![Снимок экрана](images%20lab3/Снимок%20экрана%20(200).png?raw=true)
12. Создал графики для разных метрик: CPU Usage, Total Memory, Memory Available, Disk I/O
![Снимок экрана](images%20lab3/Снимок%20экрана%20(201).png?raw=true)

## Результаты лабораторной работы:
Я научился собирать метрики со своего ноутбука с помощью Prometheus и визуализировать их в виде графиков через Grafana



