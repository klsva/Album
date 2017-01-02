# README

## Описание проекта
Сайт для проведения конкурсов между фотографами.

1. Возможность создать конкурс.
2. Возможность загрузить фотографии.
3. Возможность прокомментировать фотографию, оценить ее.
4. Возможность регистрации / авторизации пользователя.
5. ***Возможность переписки между пользователями через ЛС.

***
Описание сущностей

| User    |                   | Таблица пользователей             |
|---------|-------------------|-----------------------------------|
|         | id                | PK                                |
|         | name              | имя на сайте                      |
|         | email             | используется для рег/авт          |
|         | password          |                                   |
| Album   |                   | Таблица альбомов/конкурсов        |
|         | id                | PK                                |
|         | album_name        | Название конкурса                 |
|         | album_description | Описание альбома/конкурса         |
| Photo   |                   | Таблица фотографий                |
|         | id                | PK                                |
|         | photo_name        | Название фотографии               |
|         | album_id          | FK                                |
|         | photo_description | Описание фотографии               |
|         | file              | путь к файлу                      |
|         | ave_value         |                                   |
| Value   |                   | Таблица оценок фотографии         |
|         | id                | PK                                |
|         | user_id           | FK1                               |
|         | image_id          | FK2                               |
|         | value             |                                   |
| Comment |                   | Таблица комментариев к фотографии |
|         | id                | PK                                |
|         | user_id           | FK1                               |
|         | photo_id          | FK2                               |
|         | content           |                                   |

* ...
