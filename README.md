
# Online Pizza Ordering

## notice
* Token 모든 리퀘스트에서 같이 보냄(Header)
* Response의 Body 형식은 다음과 같다
```json
{
    message : "unsuccess",
    body : {
        // 내용은 여기에 포함합니다.
    }
}
```
* status code 역시 header로 따로 전달합니다.

## BASEURL

https://caupizza.shop


## USER
* [가입하기](/pizza/user/signup.md) : `POST /api/user/signup`
* [유저로그인](/pizza/user/signin.md) : `POST /api/user/signin`
* [유저주문](user/orderlist.md) : `GET /api/user/orderlist`
* [유저정보](user/userinfo.md) : `GET /api/userinfo`

## MENU
* [메뉴리스트조회](/pizza/menu/menulist.md) : `GET /api/menu/menulist`
* [메뉴생성](/pizza/menu/menulist.md) : `POST /api/menu/menulist`
* [주문하기](/pizza/menu/order.md) : `POST /api/menu/order`
---

## Store
* [가게 가입하기](/pizza/store/signup.md) : `POST /api/store/signup`
* [가게 로그인](/pizza/store/signin.md) : `POST /api/store/signin`
* [가게주문(완료되지 않은 주문)](/pizza/store/orderlist.md) : `GET /api/store/orderlist`
* [가게주문(완료된 주문)](/pizza/store/soldlist.md) : `GET /api/store/soldlist`
* [주문 수락/거절](/pizza/store/ordermanage.md) : `POST /api/store/ordermanage`
* [가게정보조회](/pizza/store/storeinfo.md) : `GET /api/store/storeinfo`
* [가게정보수정](/pizza/store/storeinfo.md) : `PUT /api/store/storeinfo`



