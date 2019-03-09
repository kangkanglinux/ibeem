### 问卷列表

> _**www.ibeem.cn/survey/list                 method: POST                 //获取用户下问卷信息**_

```js
request body parameter:
                //服务器将从cookie中获取用户ID

response:
         success: 
                {
                    "code" :  200
                    "list" :  [{
                        "id"          : 216    //问卷ID
                        "count"       : 0      //答卷数量
                        "introduction": ""     //问卷介绍
                        "isFinishd"   : 1      //问卷是否编辑完成（0： 未完成   1： 完成）
                        "name"        : ""     //问卷创建者名称
                        "title"       : ""     //问卷标题
                    }...]
                }
            fail: 
                {
                    "code" :  1005
                    "messg": "系统错误"
                }
```

> _**下载答卷功能实现：**_

> _**www.ibeem.cn/survey/download/question        method: POST         //获取问卷答题**_

> _**www.ibeem.cn/survey/download/answer         method: POST        //获取问卷答卷**_



