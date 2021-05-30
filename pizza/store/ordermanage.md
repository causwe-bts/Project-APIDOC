# 주문 수락/거절

## Summary
주문 수락/거절에 대한 api입니다.

## info

**URL** : `/api/store/ordermanage`

**Method** : `POST`

**Auth required** : NO

## Request Sample
**Data example**
* order_id : string
* status : string
```json
{
    "order_id":"60b1cf5bc6ddd3a7f020de00",
    "status":"cooking"
}
```

## Success Response

```json
{
    "message": "success",
    "body": {
        "order": {
            "_id": "60b1cf5bc6ddd3a7f020de00",
            "orderer": "sangryul",
            "order": [
                {
                    "_id": "60b1cf5bc6ddd3a7f020de01",
                    "menu_id": "60ad3c8b27d1db4b0dc2950f",
                    "quantity": 2
                },
                {
                    "_id": "60b1cf5bc6ddd3a7f020de02",
                    "menu_id": "60ad401af456ef4d0fc2bd19",
                    "quantity": 1
                }
            ],
            "status": "cooking",
            "datetime": "2021-05-29T05:21:31.764Z",
            "__v": 0
        }
    }
}
```

