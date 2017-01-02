# README

## Описание проекта
Сайт для проведения конкурсов между фотографами.

1. Возможность создать конкурс.
2. Возможность загрузить фотографии.
3. Возможность прокомментировать фотографию, оценить ее.
4. Возможность регистрации / авторизации пользователя.
5. Возможность переписки между пользователями через ЛС.

***
Описание сущностей

| Table              | Fields        | Comment |
|--------------------|---------------|---------|
| User               |               |Таблица пользователей
|                    |               |
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

* ...
