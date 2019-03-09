### 问卷题库

> _**www.ibeem.cn/survey/question\_list          method: POST       //获取题库列表**_

```js
request body parameter:
                //服务器将从cookie中获取用户ID

response:
         success: 
                {
                    "code"   :  200
                    "list"   :  [{
                        "id"     :  1   //答题ID
                        "type"   :  ""  //答题类型
                        "setting":  ""  //答题内容
                        "title"  :  ""  //答题标题
                    }...]
                }
            fail: 
                {
                    "code"   :  1005
                    "messg"  : "系统错误"
                }
```

> _**www.ibeem.cn/survey/library/add      method: POST     //往题库添加答题**_

```js
request body parameter:
                {
                    "setting" : ""  //答题参数数据
                    "name"    : ""  //答题名称
                    "type"    : 1   //答题类型
                    "html"    : ""  //答题页面展示内容
                }

response:
         success: 
                {
                    "code"   :  200
                    "list"   :  [{
                        "id"     :  1   //答题ID
                        "type"   :  ""  //答题类型
                        "setting":  ""  //答题内容
                        "title"  :  ""  //答题标题
                    }...]
                }
            fail: 
                {
                    "code"   :  1005
                    "messg"  : "系统错误"
                }
```



