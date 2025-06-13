# API для социальной сети YaTube

## Инструкция по запуску проекта

### 1. Подготовка репозитория
Скопируйте репозиторий проекта и перейдите в его директорию:
```bash
git clone https://github.com/LandLordME/api_final_yatube
```
### 2.Настройка виртуального окружения

```
python -m venv venv
source venv/bin/activate  # Для Linux/MacOS
venv\Scripts\activate     # Для Windows
```
###  3.Установка зависимостей
```
pip install --upgrade pip
pip install -r requirements.txt
```
###  4.Настройка базы данных
```
python manage.py migrate
```
###  5. Запуск сервера
```
python manage.py runserver
```
### 6. После успешного запуска сервер будет доступен по адресу:
```
http://127.0.0.1:8000/