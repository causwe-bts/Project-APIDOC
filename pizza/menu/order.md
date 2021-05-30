# 주문하기

## Summary
주문을 하는 api입니다.

## 메뉴생성

## info

**URL** : `/api/menu/order`

**Method** : `POST`

**Auth required** : YES

## Request Sample
**Content examples**

* orderer : string
* order : array
* status : string

```json
// body
{
    "orderer" : "sangryul",
    "order" : [
        {
            "menu_id" : "60ad3c8b27d1db4b0dc2950f",
            "quantity" : 2
        },
        {
            "menu_id" : "60ad401af456ef4d0fc2bd19",
            "quantity" : 1
        }
    ],
    "status" : "ordered"
}
```
## Success Response

```json
{
    "message": "success",
    "body": {
        "orderInfo": {
            "_id": "60b2ef48218e49074cc4071d",
            "orderer": "sangryul",
            "order": [
                {
                    "_id": "60b2ef48218e49074cc4071e",
                    "menu_id": "60ad3c8b27d1db4b0dc2950f",
                    "quantity": 2
                },
                {
                    "_id": "60b2ef48218e49074cc4071f",
                    "menu_id": "60ad401af456ef4d0fc2bd19",
                    "quantity": 1
                }
            ],
            "status": "ordered",
            "datetime": "2021-05-30T01:50:00.621Z",
            "__v": 0
        }
    }
}
```