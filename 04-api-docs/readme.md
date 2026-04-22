# HelpDesk API Documentation
Это документация REST API для HelpDesk-портала (учебный проект).
API позволяет создавать заявки, управлять ими, добавлять комментарии и просматривать справочную информацию.
## Технологии
- OpenAPI 3.0.0
- JSON Schema
- Swagger UI / Swagger Editor
## Эндпоинты
- POST /tickets — создание заявки
- GET /tickets — список заявок (с пагинацией)
- GET /tickets/{id} — получить заявку
- PUT /tickets/{id} — полное обновление
- PATCH /tickets/{id} — частичное обновление
- DELETE /tickets/{id} — удаление
- GET /tickets/{id}/comments — комментарии
- POST /tickets/{id}/comments — добавить комментарий
- PATCH /tickets/{ticketId}/comments/{commentId} — редактировать комментарий
- DELETE /tickets/{ticketId}/comments/{commentId} — удалить комментарий
- GET /users — список пользователей
- GET /users/{id} — информация о пользователе

## Результаты:
- Разработана OpenAPI-спецификация (`openapi.json`), включающая 9 эндпоинтов и 7 схем данных.
- Настроена интерактивная документация с возможностью тестирования запросов.

## Посмотреть документацию:
🔗 [Интерактивная документация API (Swagger UI)](https://natalyfei.github.io/natalia-sa-portfolio/04-api-docs/)

## Исходный код спецификации:
📁 [JSON `04-api-docs`](https://github.com/natalyFei/natalia-sa-portfolio/blob/master/04-api-docs/openapi.json)


