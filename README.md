
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

추가바랍니다.


## USER
* [가입하기](/pizza/user/signup.md) : `POST /api/user/signup`
* [유저로그인](/pizza/user/signin.md) : `POST /api/user/signin`
* [유저주문(orderlist)](user/orderlist.md) : `GET /api/user/orderlist`
* [유저정보](user/userinfo.md) : `GET /api/userinfo`

## MENU
* 메뉴리스트 : `GET /api/menu/menulist`
* 주문 : `POST /api/menu/order`

---

## Store
* 가게로그인 : `POST /api/store/signin`
* 가게주문(완료되지 않은 주문) : `GET /api/store/orderlist`
* 가게주문(완료된 주문) : `GET /api/store/soldlist`
* 주문 수락/거절 : `POST /api/store/ordermanage`
* 가게 정보 : `GET /api/store/storeinfo`
* 가게 정보수정 : `PUT /api/store/storeinfo`



