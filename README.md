# name-ranking
同じ苗字の人が何人いるのかなって

同じ階層に data.js を配置する
構造は slack api の users.list
https://api.slack.com/methods/users.list

var data= {
    "ok": true,
    "members": [
        {
            ...
            "name": "なまえ"
            ...
         },
        {
            ...
            "name": "なまえ"
            ...
         },
       ]
     }
