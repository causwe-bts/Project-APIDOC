# 가게주문(완료된 주문)

## Summary

가게 입장에서 완료된 주문에 대한 목록을 가져오는 api입니다.

## info

**URL** : `/api/store/soldlist`

**Method** : `GET`

**Auth required** : YES

## Request Sample
None
## Success Response

```json
{
    "message": "success",
    "orderList": [
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
        }
    ]
}
```