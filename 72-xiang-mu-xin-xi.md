### 项目信息

> _**www.ibeem.cn/project/single/info             method: POST            //获取项目信息**_

```js
request body parameter:
                {
                    "projectID"       :  157   //项目ID
                }

response:
         success: 
                {
                    "code" :  200
                    "project" :  {
                        "id"          : 157    //项目ID
                        "decribe"     : ""     //项目描述
                        "image"       : ""     //项目图片地址
                        "name"        : ""     //项目名称
                        "peopleCount" : ""     //项目下用户数                        
                    }
                }
            fail: 
                {
                    "code" :  1005
                    "messg": "系统错误"
                }
```



