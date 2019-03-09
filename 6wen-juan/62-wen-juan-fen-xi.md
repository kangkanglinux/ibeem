### **问卷分析**

> _**www.ibeem.cn/survey/getSurveyByID            method: POST           //根据问卷ID获取问卷**_

```js
request body parameter:
                {
                    "surveyID"   :  249    //问卷ID
                }

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



