## Проект api_final_yatube - backend-часть соцсети Yatube.

В данном проекте реализована вся необходимая структура API для ее дальнейшего использования в frontend-части.

**Как запустить проект:**

Клонировать репозиторий и перейти в него в командной строке:
```
git clone git@github.com:Helliur/yatube_api.git
```
```
cd yatube_api
```
Установить виртуальное окружение и запустить его:
```
python -m venv venv
```
```
source vevn/scripts/activate
```
Установить зависимости:
```
pip install -r requirements
```
Перейти в папку с manage.py:
```
cd yatube_api
```
Применение миграций:
```
python manage.py migrate
```
Запуск backend-сервера:
```
python manage.py runserver
```
#### После запуска сервера по ссылке http://127.0.0.1:8000/redoc/ будет доступна документация и примеры запросов.

**Для запуска проекта требуется наличие SECRET_KEY, который необходимо записать в файле .env в той же директории, в которой расположен файл settings.py**
