
# Подготовка сервера, сборка и выкладка сайта "Выбор фильма"


## Содержание
- [Требования](#requirements)
- [Технологии](#technologies)
- [Начало работы](#start)
- [Теги запуска playbook](#tag_methods)
- [To Do](#todo)
- [Команда проекта](#command)


## <a id="requirements">Требования</a>
Для установки и запуска проекта, необходимо:
- python 3.9
- ansible
- docker
- openssl

## <a id="technologies">Технологии</a>
- docker, docker build, ansible, nodejs, js, nginx

## <a id="start">Начало работы</a>

- Скачать репозиторий проекта
```
git clone https://github.com/rudikrudik/chooseMovie-devops.git
```
- Перейти в каталог проекта
```
cd chooseMovie-devops
```
- В файле inventory указать ip адрес сервера
  - Сборка докер образа и запуск происходит на одном хосте

## <a id="tag_methods">Теги запуска playbook</a>
```
main.yml # подготавливает систему, собирает и разворачивает сервис
main.yml --tags="build" # сборка образа 
main.yml --tags="deploy" # выкладка сервиса
```

## <a id="todo">To do</a>
- ~~health check для контейнера~~
- мониторинг

## <a id="command">Команда проекта</a>
- Бахман Рудольф - DevOps engineer
  - telegram - https://t.me/rudik_rudik
  - email - rudik.login@gmail.com
