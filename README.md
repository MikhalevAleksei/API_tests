## Дипломный проект. Задание 2: API-тесты
tests for API https://stellarburgers.nomoreparties.site/

### Автотесты для проверки программы, которая помогает заказать бургер в Stellar Burgers

### Реализованные сценарии

Созданы API-тесты, используется библиотека requests.  
### Структура проекта

- `tests` - пакет, содержащий тесты
### Запуск автотестов

**Установка зависимостей**

> `$ pip install -r requirements.txt`

**Запуск автотестов и создание allure-отчета 

>  
pytest tests.py --alluredir=allure_results
allure serve allure_results




