### 问卷

> _**www.ibeem.cn/weixin/survey/release              method: POST             //获取发布问卷**_

```js
request body parameter:

response:
         success: 
                {
                    "code"   :  200
                    "list"   :  {
                        "id"          :   ""   //问卷ID
                        "title"       :   ""   //问卷标题
                        "introduction":   ""   //问卷简介
                    }
                }
            fail: 
                {
                    "code"   : 1005
                    "messg"  : "系统错误"
                }
```



