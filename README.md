Авторизацию для получения пользователя сделала при помощи добавления динамической переменной токена в Headers:

3.1 - код создания переменной с токеном.

3.2 - получение пользователя.

---

1. Response at registration:

{
    "user": {
        "username": "vladimirar",
        "email": "vladimira_ra@mail.ru",
        "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjYzOTA4MjcxMjA3NTk0MWIwMGU0NzMwNCIsInVzZXJuYW1lIjoidmxhZGltaXJhciIsImV4cCI6MTY3NTU5ODk2MSwiaWF0IjoxNjcwNDE0OTYxfQ.QdnuVnk6P7klvj8rfYx78dVnubq3wQ_030LJ_aikgF4"
    }
}

2. Response on login:

{
    "user": {
        "username": "vladimirar",
        "email": "vladimira_ra@mail.ru",
        "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjYzOTA4MjcxMjA3NTk0MWIwMGU0NzMwNCIsInVzZXJuYW1lIjoidmxhZGltaXJhciIsImV4cCI6MTY3NTYxNTE4NCwiaWF0IjoxNjcwNDMxMTg0fQ.ajilbtjh9XeBpjPHvt5lJHdbIu5zqFHv_WeuqXfKtuE"
    }
}

3. Response when getting user:

{
    "user": {
        "username": "vladimirar",
        "email": "vladimira_ra@mail.ru",
        "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjYzOTA4MjcxMjA3NTk0MWIwMGU0NzMwNCIsInVzZXJuYW1lIjoidmxhZGltaXJhciIsImV4cCI6MTY3NTYxNTIxMSwiaWF0IjoxNjcwNDMxMjExfQ.Py_-w_-YuWSZQAw0vsyvfQ_tqFEeJMws-AlhnOb72uc"
    }
}