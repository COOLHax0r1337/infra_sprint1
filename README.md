# Kittygram - проект для публикации фото котиков, их имен, года рождения и цвета, ну можна еще ачивок докинуть по желанию

## Tech
```
django
drf
nginx
gunicorn
```
### Как запустить проект
```
включите капютер
```
Клонируйте репу
```
git clone git@github.com:COOLHax0r1337/infra_sprint1.git
```
```
cd infra_sprint1
```
Активируйте venv (лучше делать из корневой, в ином случае пакеты могут криво ставиться, можно и из бэка, но тогда лучше явно указывать путь установки зависимостей)
```
python3 -m venv venv
``` 
```
source venv/bin/activate
```
Установить зависимости (список дополнен для корректного функционала dotenv)
```
pip install -r requirements.txt
```
Выполнить миграции
## Если нужен деплой, то порядок таков
```
connect github
```
```
запуск бэка
```
```
запуск фронта
```
```
gunicorn
```
```
nginx
```

[author](https://github.com/COOLHax0r1337)
