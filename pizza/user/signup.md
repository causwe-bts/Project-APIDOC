# 유저로그인

Used to collect a Token for a registered User.

**URL** : `/api/user/signin`

**Method** : `POST`

**Auth required** : NO

**Data example**
* email : string
* password : string
```json
//body
{
    "username": "iloveauth@example.com",
    "password": "abcd1234"
}
```

## Success Response

**Code** : `200 OK`

**Content example**
* token : string
```json
{
    "token": "93144b288eb1fdccbe46d6fc0f241a51766ecd3d"
}
```

## Error Response

