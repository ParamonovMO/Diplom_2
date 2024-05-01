# Дипломный проект. Задание 2: API

Автотесты для сервиса  "Stellar Burger".

## Файлы:
- allure_results - каталог с отчетом о тестировании
- tests/test_create_order.py - файл с проверками создания заказов 
- tests/test_create_user.py - файл с проверками создания пользователя
- tests/test_get_orders.py - файл с проверками получения заказов
- tests/test_login.py - файл с проверками логина пользователя
- tests/test_update_user.py - файл с проверками изменения данных пользователя
- data/data.py - файл с методами генерации данных для регистрации
- data/ingredients.py -  файл с данными ингредиентов
- data/status_code.py - файл со статус-кодами ответов
- data/urls - файл с URL сервиса и ручками
- requirements.txt - файл с внешними зависимостями
- conftest.py - файл с фикстурой

Перед работой с репозиторием требуется установить зависимости 
```
pip install -r requirements.txt
```
Запустить все тесты
```
pytest tests --alluredir=allure_results
```
Посмотреть отчет о тестировании
```
allure serve allure_results
```
