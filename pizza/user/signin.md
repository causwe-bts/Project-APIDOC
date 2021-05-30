# 유저로그인

Used to collect a Token for a registered User.

**URL** : `/api/user/signin`

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

**Code** : `200 OK`

**Content example**
* token : string
```json
{
    "message": "success",
    "body": {
        "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJfaWQiOiI2MGIwZWYzN2M2ZGRkM2E3ZjAyMGRkZmIiLCJ1c2VybmFtZSI6InNhbmdyeXVsIiwiYWRtaW4iOnRydWUsImlhdCI6MTYyMjMzODExNVySW5mbyJ9.jC1KW1fXiutyokDMMCOtX3Uf2-KKYPbY3BV6EtLkhSo"
    }
}
```

