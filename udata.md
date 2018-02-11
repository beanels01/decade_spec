# /UDATA

```js
{
        "name": "<使用者暱稱>"(字串、非必填),
        "address": "<住家地址>"(字串、非必填),
        "phone": "<連絡電話>"(字串、非必填),
        "region": <所屬地區>(數字、非必填),
        "intro": "<自我介紹>"(字串、非必填),
        "photo": "<相片連結>"(IMGURL、非必填),
        "favStock": [](stock id陣列、非必填),
        "favPost": [](post id陣列、非必填),
        "favCoupon": [](coupon id陣列、非必填),

        --------

        "Author_Stat":{
                "FollowBy":[](user id陣列),
                "FollowNum":<追蹤數>(數字),
                "coop_stocks":["<合作商品id>"](stock id陣列),
                "coop_suppliers":["<合作廠商uid>"](uid陣列),
                "notifications":[
                        {
                        "MessageCode":<訊息狀態>,
                        "Message":"<通知內容>",
                        "IsRead":<已讀狀態>(布林)
                        }
                ](通知陣列),

        }
        "Supplier_Stat":{
                "RelatedSeller":[
                        {
                        "name":"<窗口名稱>",
                        "email":"<窗口email>"
                        }
                ]
                "notifications":[
                        {
                        "MessageCode":<訊息狀態>,
                        "Message":"<通知內容>",
                        "IsRead":<已讀狀態>(布林)
                        }
                ](通知陣列),
                "ship_type":[
                        
                ]
        }
        "User_Stats":{
                "notifications":[
                        {
                        "MessageCode":<訊息狀態>,
                        "Message":"<通知內容>",
                        "IsRead":<已讀狀態>(布林)
                        }
                ](通知陣列),
                "follow_list":[
                        "編輯uid"
                ](uid陣列)
        }
}
```



