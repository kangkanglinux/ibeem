### 问卷题库

> _**www.ibeem.cn/survey/question\_list          method: POST       //获取题库列表**_

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



