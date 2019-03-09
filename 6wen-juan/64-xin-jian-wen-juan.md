### 新建问卷

> _**www.ibeem.cn/survey/increase/commit          method: POST          //新建问卷存入数据库**_

```js
request body parameter:
                //服务器将从cookie中获取用户ID
                {
                    "survey" :  ""       //问卷内容
                }

response:
         success: 
                {
                    "code"   :  200
                }
            fail: 
                {
                    "code"   :  1005
                    "messg"  : "系统错误"
                }
```



