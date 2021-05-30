# 유저정보

## Summary

유저 본인의 정보를 담고 있는 API입니다.

## info

**URL** : `/api/userinfo`

**Method** : `GET`

**Auth required** : YES

## Request Sample
None
## Success Response
```json
{
    "message": "success",
    "body": {
        "userInfo": {
            "admin": true,
            "username": "sangryul",
            "phonenumber": "01012341234"
        }
    }
}
```

