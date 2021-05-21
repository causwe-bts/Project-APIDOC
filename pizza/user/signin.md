# 가입하기

## Summary

유저 가입하기 api입니다.

## info

**URL** : `/api/user/`

**Method** : `POST`

**Auth required** : NO

## Request Sample

**Content examples**

* email : string
* password : string
* name : string
* phone : string

```json
// body
{
    "email" : "abc@abc.com",
    "password" : "1q2w3e4r",
    "name" : "Harry",
    "phone": "01012345678"
}
```
## Success Response

**Code** : `200 OK`
```
void
```

## Error Response
