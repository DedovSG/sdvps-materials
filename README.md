## Домашнее задание к занятию «Что такое DevOps. СI/СD»

# Задание 1
Что нужно сделать:

- Установите себе jenkins по инструкции из лекции или любым другим способом из официальной документации. Использовать Docker в этом задании нежелательно.
- Установите на машину с jenkins golang.
- Используя свой аккаунт на GitHub, сделайте себе форк репозитория. В этом же репозитории находится дополнительный материал для выполнения ДЗ.
- Создайте в jenkins Freestyle Project, подключите получившийся репозиторий к нему и произведите запуск тестов и сборку проекта go test . и docker build ..
В качестве ответа пришлите скриншоты с настройками проекта и результатами выполнения сборки.

# Задание 2
Что нужно сделать:

- Создайте новый проект pipeline.
- Перепишите сборку из задания 1 на declarative в виде кода.
В качестве ответа пришлите скриншоты с настройками проекта и результатами выполнения сборки.

# Задание 3
Что нужно сделать:

- Установите на машину Nexus.
- Создайте raw-hosted репозиторий.
- Измените pipeline так, чтобы вместо Docker-образа собирался бинарный go-файл. Команду можно скопировать из Dockerfile.
- Загрузите файл в репозиторий с помощью jenkins.
В качестве ответа пришлите скриншоты с настройками проекта и результатами выполнения сборки.


# Решение 1

![alt text](https://github.com/DedovSG/sdvps-materials/blob/main/img/Jenkins%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B51%D0%B0.png)

![alt text](https://github.com/DedovSG/sdvps-materials/blob/main/img/Jenkins%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B51%D0%B1.png)

![alt text](https://github.com/DedovSG/sdvps-materials/blob/main/img/Jenkins%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B51%D0%B2.png)

![alt text](https://github.com/DedovSG/sdvps-materials/blob/main/img/Jenkins%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B51%D0%B3.png)

![alt text](https://github.com/DedovSG/sdvps-materials/blob/main/img/Jenkins%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B51%D0%B4.png)


# Решение 2

![alt text](https://github.com/DedovSG/sdvps-materials/blob/main/img/Jenkins%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B52%D0%B0.png)

![alt text](https://github.com/DedovSG/sdvps-materials/blob/main/img/Jenkins%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B52%D0%B1.png)

# Решение 3

![alt text](https://github.com/DedovSG/sdvps-materials/blob/main/img/Jenkins%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B53%D0%B0.png)

![alt text](https://github.com/DedovSG/sdvps-materials/blob/main/img/Jenkins%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B53%D0%B1.png)