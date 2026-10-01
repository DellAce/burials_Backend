# Backend API

## Общая информация

Авторизация:

`Authorization: Bearer <token>`

---

# Endpoints

## POST /auth/login

Авторизация пользователя.

### Request

```json
{
  "email": "user@example.com",
  "password": "secret"
}
```
