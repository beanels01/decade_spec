```js
{
        "type": <商品類型>(數字、1為商品、3為票卷),
     //修正名稱   "category": <分類ID>(數字),
        "comboList": [
            "<商品id>"
        ](字串陣列),
        "img": [<imgurl>](字串陣列),
        "name": "<商品名稱>"(字串),
        -------
     //新增   
             "summary":"<商品簡介>",
             "discription":"<商品敘述>",
             "note":"<產品備註>",
             "event":{
                 "name":"<場次名稱>",
                 "time_start":<開始時間>,
                 "time_end":<結束時間>
                 }
             }        

        -------
     //刪除   "count": 79,
     //刪除   "available": false,
     //刪除   "price": {},
        "spec": [
            {
                "name": "西服訂製體驗服務",
                "priceDefault": <原價>(數字),
                "priceOnSale": <折扣價>(數字),
                "count": 10
                "imageURL":[<imgurl>](字串陣列)
            }
        ],
        "related": {
            "stock":[
            "<商品id>"
            ],
            "post":[
            "文章id"
            ]
        },
        "seller": [
            "5a5b52b56bcc085a4e730072"
        ],
        "status": <文章狀態、0為草稿、1為已發布>

        "tag": []
    }
```



