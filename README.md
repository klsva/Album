# README

## Тема, пока обтекаемо: Менюделка и to-buy-list-отправлялка
Доступный функционал:

1. Возможность создания меню на неделю на определенное количество человек.
2. Возможность сохранить меню.
3. Возможность отправить список покупок на почту.
4. Возможность регистрации / авторизации пользователя

***

| Table              | Fields        | Comment |
|--------------------|---------------|---------|
| products           |               |         |
|                    | id            |         |
|                    | name_product  |         |
| ingredients        |               |         |
|                    | id            |         |
|                    | id_dish       |         |
|                    | quantity      |         |
|                    | measure       |         |
| measure            |               |         |
|                    | id            |         |
|                    | unit          |         |
| dish               |               |         |
|                    | id            |         |
|                    | id_category   |         |
|                    | name_dish     |         |
|                    | recipe        |         |
| category           |               |         |
|                    | id            |         |
|                    | name_category |         |
| ingredients_dishes |               |         |
|                    | id_ingredient |         |
|                    | id_dish       |         |
| menu               |               |         |
|                    | id            |         |
|                    | name_menu     |         |
|                    | day           |         |
|                    | id_eating     |         |
|                    | id_dish       |         |
| eating             |               |         |
|                    | id            |         |
|                    | name_eating   |         |
| user_menu          |               |         |
|                    | id_user       |         |
|                    | id_menu       |         |
| user               |               |         |

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
