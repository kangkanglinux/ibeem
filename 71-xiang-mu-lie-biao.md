### 项目列表

> _**www.ibeem.cn/project/list                method: POST          //获取用户下项目**_

```js
request body parameter:
                //服务器将从cookie中获取用户ID

response:
         success: 
                {
                    "code" :  200
                    "list" :  [{
                        "id"          : 216    //项目ID
                        "decribe"     : ""     //项目描述
                        "image"       : ""     //项目图片地址
                        "name"        : ""     //项目名称                        
                    }...]
                }
            fail: 
                {
                    "code" :  1005
                    "messg": "系统错误"
                }
```



