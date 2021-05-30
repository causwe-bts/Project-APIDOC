# 가게주문(완료되지 않은 주문)

## Summary

가게 입장에서 완료되지 않은 주문에 대한 목록을 가져오는 api입니다.

## info

**URL** : `/api/store/orderlist`

**Method** : `GET`

**Auth required** : YES

## Request Sample
None
## Success Response

```json
{
    "message": "success",
    "body": {
        "orderList": [
            {
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
                "status": "ordered",
                "datetime": "2021-05-29T05:21:31.764Z",
                "__v": 0
            },
            {
                "_id": "60b1edfdc6ddd3a7f020de06",
                "orderer": "sangryul",
                "order": [
                    {
                        "_id": "60b1edfdc6ddd3a7f020de07",
                        "menu_id": "60ad3c8b27d1db4b0dc2950f",
                        "quantity": 2
                    },
                    {
                        "_id": "60b1edfdc6ddd3a7f020de08",
                        "menu_id": "60ad401af456ef4d0fc2bd19",
                        "quantity": 3
                    }
                ],
                "status": "Cooking",
                "datetime": "2021-05-29T07:32:13.738Z",
                "__v": 0
            },
            {
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
        ]
    }
}
```