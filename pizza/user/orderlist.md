# 주분하기

## Summary

본인의 주문목록을 확인하기 위한 API입니다.

## info

**URL** : `/api/user/orderlist`

**Method** : `GET`

**Auth required** : YES

## Request Sample

None

## Success Response
**Content examples**

```json
{
    "message": "success",
    "body": {
        "userOrders": [
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
                "_id": "60b1eddfc6ddd3a7f020de03",
                "orderer": "sangryul",
                "order": [
                    {
                        "_id": "60b1eddfc6ddd3a7f020de04",
                        "menu_id": "60ad3c8b27d1db4b0dc2950f",
                        "quantity": 2
                    },
                    {
                        "_id": "60b1eddfc6ddd3a7f020de05",
                        "menu_id": "60ad401af456ef4d0fc2bd19",
                        "quantity": 1
                    }
                ],
                "status": "Received",
                "datetime": "2021-05-29T07:31:43.547Z",
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
            }
        ]
    }
}
```
