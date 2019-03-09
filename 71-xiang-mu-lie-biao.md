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

> _**www.ibeem.cn/project/increase        method: POST       //创建项目**_

```js
request body parameter:
                //服务器将从cookie中获取用户ID
                {
                    "projectName"     : ""     //项目名称
                    "describe"        : ""     //项目描述
                    "image"           : ""     //项目图片
                }

response:
         success: 
                {
                    "code" :  200
                }
            fail: 
                {
                    "code" :  1005
                    "messg": "系统错误"
                }
                ||
                {
                    "code" :  1001
                    "messg":  "项目名重复"
                }
```

> _**www.ibeem.cn/project/single/delete      method: POST     //删除项目**_

```js
request body parameter:
                {
                    "projectID"     : ""     //项目ID
                }

response:
         success: 
                {
                    "code" :  200
                }
            fail: 
                {
                    "code" :  1005
                    "messg": "系统错误"
                }
```



