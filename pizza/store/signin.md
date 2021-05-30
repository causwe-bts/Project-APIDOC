# 가게 로그인

## Summary
가게 로그인에 대한 api입니다.

## info

**URL** : `/api/store/signin`

**Method** : `POST`

**Auth required** : NO

**Data example**
* username : string
* password : string
```json
//body
{
    "username": "iloveauth",
    "password": "abcd1234"
}
```

## Success Response

```json
{
    "message": "success",
    "body": {
        "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJfaWQiOiI2MGIwZWYzN2M2ZGRkM2E3ZjAyMGRkZmIiLCJ1c2VybmFtZSI6InNhbmdyeXVsIiwiYWRtaW4iOnRydWUsImlhdCI6MTYyMjMzODExNywiZXhwIjoxNjIyOTQyOTE3LCJpc3MiOiJjYXVwaXp6YS5jb20iLCJzdWIiOiJ1c2VySW5mbyJ9"
    }
}
```

