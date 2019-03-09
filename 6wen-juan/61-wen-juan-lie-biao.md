### 问卷列表

> _**www.ibeem.cn/survey/list                 method: POST                 //获取用户下问卷信息**_

```js
request body parameter:
                //服务器将从cookie中获取用户ID

response:
         success: 
                {
                    "code" :  200
                    "list" :  device    //所在页面下设备信息
                }
            fail: 
                {
                    "code" :  1005
                    "messg": "系统错误"
                }
```



