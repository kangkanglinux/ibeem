### 新建问卷

> _**www.ibeem.cn/survey/increase/commit          method: POST          //新建问卷存入数据库**_

```js
request body parameter:
                //服务器将从cookie中获取用户ID
                {
                    "survey"             :  ""       //问卷内容
                }

response:
         success: 
                {
                    "code"               :  200
                    "survey"             :  {
                        "introduction"   :  ""        //问卷介绍
                        "peoplecount"    :  41        //答题人数
                        "title"          :  ""        //问卷标题
                        "paragraph"      :  [{
                            "order"          :  1
                            "title"          :  ""
                            "questionList": [{
                                "questionID" : 451    //答题ID
                                "required"   : 0
                                "sequence"   : 1      //答题序列号
                                "setting"    : ""     //答题内容
                                "title"      : ""     //答题标题
                                "type"       : 1      //答题类型
                            }...]
                        }...]
                    }

                }
            fail: 
                {
                    "code" :  1005
                    "messg": "系统错误"
                }
```



