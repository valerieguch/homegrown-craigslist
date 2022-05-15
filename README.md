# Доска объявлений для поиска работы
[На хостинге Heroku](https://homegrown-craigslist.herokuapp.com)

### Установка и запуск на локальном сервере
pip:
```shell
pip install -r requirements.txt
```

[Poetry](https://python-poetry.org/):
```shell
poetry install
```

Запуск:
```shell
uvicorn main:app
```