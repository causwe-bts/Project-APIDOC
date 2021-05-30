# 메뉴리스트조회, 메뉴생성

## Summary

매뉴리스트와 매뉴 생성에 대한 API모음입니다.

---

## 메뉴리스트

## info

**URL** : `/api/menu/menulist`

**Method** : `GET`

**Auth required** : YES

## Request Sample
None
## Success Response

```json
{
    "message": "success",
    "body": {
        "menuList": [
            {
                "_id": "60af94aec6ddd3a7f020ddfa",
                "name": "청년피자",
                "description": "청년피자",
                "price": 14000,
                "imgURL": "https://caupizza.shop/api/IeH8QpIt7M6XzxC16znCn9G5L.jpg",
                "__v": 0
            }
        ]
    }
}
```
---
## 메뉴생성

## info

**URL** : `/api/menu/menulist`

**Method** : `POST`

**Auth required** : YES

## Request Sample

**Content examples**

* image : fileObject
* name : string
* description : string
* price : string

```json
// body
{
    "image" : "[fileObject]",
    "name" : "청년피자",
    "description" : "청년피자",
    "price": "14000"
}
```
## Success Response

```json
{
    "message": "success",
    "body": {
        "menuInfo": {
            "_id": "60b2eefc218e49074cc4071c",
            "name": "청년피자222",
            "description": "청년피자",
            "price": 14000,
            "imgURL": "https://caupizza.shop/api/lbMf5vySxw6V2MTBFQbvB1Q0r.jpg",
            "__v": 0
        }
    }
}
```