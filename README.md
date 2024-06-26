# README

## Cхема API в Swagger:
![image](https://github.com/antnamve/uchiru-api/assets/143155099/93ace28a-df39-499b-a568-c88619a2df2c)

!Важно:
- нельзя создать ученика с параметрами school_id = 0 и class_id = 0, поскольку модель ученика принадлежит моделям школа и класс, попробуйте school_id = 1 и class_id = 1

Фунционал приложения:
 - возможность добавлять школы и их классы
 - возможность добавлять учеников, связывая их с конкретным классом и школой
 - после добавления ученика создаётся привязанный к нему токен, по этому токену ученик может авторизоваться в приложении, затем в своём профиле указать свой email и пароль, по которым он также может войти в приложение (при первой смене данных нужно указать автоматически сгенерированный при создании ученика пароль (сейчас '123456'))
 - в профиле ученика можно менять и другие его данные
 - возможна регистрация новых пользователей
 - все CRUD операции над моделями школы, класса и ученика
 - работают все запросы, указаные в API
 - запуск через docker compose up

# Api этого проекта можно найти по ссылке
[https://github.com/uchiru/internship-api-schema-task/blob/master/openapi.yaml](https://github.com/uchiru/internship-api-schema-task/blob/master/openapi.yaml)
