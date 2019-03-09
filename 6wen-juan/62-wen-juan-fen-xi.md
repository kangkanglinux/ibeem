### **问卷分析**

> _**www.ibeem.cn/survey/getSurveyByID            method: POST           //根据问卷ID获取问卷**_

```js
request body parameter:
                {
                    "surveyID"           :  249   //问卷ID
                }

response:
         success: 
                {
                    "code"               :  200
                    "createTime"         :  ""    //问卷创建时间
                    "introduction"       :  ""    //问卷描述
                    "pagingNum"          :  0     //页数
                    "pagingType"         :  1
                    "surveyID"           :  249   //问卷ID
                    "title"              :  ""    //问卷标题
                    "list" :  [{
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
            fail: 
                {
                    "code" :  1005
                    "messg": "系统错误"
                }
```



