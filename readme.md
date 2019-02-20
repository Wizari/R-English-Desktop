#Получение access token

Для получения access token нужно отправить POST запрос на адрес http://188.227.5.111:3565/oauth/token
тип параметров x-www-form-urlencoded

## Параметры

* grant_type  - password
* username    - ivanov
* password    - secret

## Авторизационный заголовок клиента
Authorization - Basic hash по алгоритму Base64

e.g Authorization Basic YmFyYW5vdjppdmFu


## Получение следующего вопроса

GET http://188.227.5.111:3565/default/next