# 가게 가입하기

## Summary

가게 가입하기 api입니다.

## info

**URL** : `/api/store/signup`

**Method** : `POST`

**Auth required** : NO

## Request Sample

**Content examples**

* username : string
* password : string
* phonenumber : string

```json
// body
{
    "username" : "abc@abc.com",
    "password" : "1q2w3e4r",
    "phonenumber": "01012345678"
}
```
## Success Response

**Code** : `200 OK`
```
void
```
