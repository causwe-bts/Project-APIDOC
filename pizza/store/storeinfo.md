# 가게정보조회, 가게정보수정

## Summary

가게정보조회와 가게정보 수정에 대한 API입니다.

---

## 가게정보조회

## info

**URL** : `/api/store/storeinfo`

**Method** : `GET`

**Auth required** : YES

## Request Sample
None
## Success Response

```json
{
    "message": "success",
    "body": {
        "storeInfo": {
            "_id": "60b20ef8218e49074cc40717",
            "name": "CAU Pizza",
            "time": "24hr",
            "location": "흑석동",
            "__v": 0
        }
    }
}
```
---
## 가게정보수정

## info

**URL** : `/api/menu/menulist`

**Method** : `POST`

**Auth required** : YES

## Request Sample
**Data example**
* time : "24hr"

```json
{
    "time":"24hr"
}
```

추가바람
## Success Response

```json
{
    "message": "success"
}
```