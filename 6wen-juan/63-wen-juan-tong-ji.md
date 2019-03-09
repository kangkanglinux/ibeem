### 问卷统计

> www.ibeem.cn/survey/statistics              method: POST             //问卷统计

```js
request body parameter:
                {
                    "surveyID"           :  249       //问卷ID
                    "beginTime"          :  ""        //开始时间
                    "endTime"            :  ""        //结束时间
                    "relation"           :  1         //问卷与项目，建筑，测点关系(1: 问卷绑定项目  2：问卷绑定建筑  3：问卷绑定测点)
                    "objectID"           :  -1        //建筑或项目或测点ID
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
                    "messg": "系统错误" || "没有此 survey id"
                }
```



