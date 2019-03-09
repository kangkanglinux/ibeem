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
>
> _**www.ibeem.cn/survey/download/question        method: POST         //获取问卷答题**_
>
> _**www.ibeem.cn/survey/download/answer         method: POST        //获取问卷答卷**_

```js
//获取问卷答题

request body parameter:
                {
                    "surveyID"      :  249   //问卷ID
                }

response:
         success: 
                {
                    "code"          :  200
                    "createTime"    :  ""    //问卷创建时间
                    "introduction"  :  ""    //问卷描述
                    "pagingNum"     :  0     //页数
                    "pagingType"    :  1
                    "surveyID"      :  249   //问卷ID
                    "title"         :  ""    //问卷标题
                    "list" :  [{
                        "questionID":  451   //答题ID
                        "required"  :  0
                        "sequence"  :  1     //答题序列号
                        "setting"   :  ""    //答题内容
                        "title"     :  ""    //答题标题
                        "type"      :  1     //答题类型
                    }...]
                }
            fail: 
                {
                    "code" :  1005
                    "messg": "系统错误"
                }
```

```js
//获取问卷答卷

request body parameter:
                {
                    "surveyID"      :  249   //问卷ID
                    "startTime"     :  ""    //开始时间
                    "endTime"       :  ""    //结束时间
                    "relation"      :  0     //问卷与项目，建筑，测点关系(1: 问卷绑定项目  2：问卷绑定建筑  3：问卷绑定测点)
                }

response:
         success: 
                {
                    "code"          :  200
                    "createTime"    :  ""    //问卷创建时间
                    "introduction"  :  ""    //问卷描述
                    "pagingNum"     :  0     //页数
                    "pagingType"    :  1
                    "surveyID"      :  249   //问卷ID
                    "title"         :  ""    //问卷标题
                    "list" :  [{
                        "questionID":  451   //答题ID
                        "required"  :  0
                        "sequence"  :  1     //答题序列号
                        "setting"   :  ""    //答题内容
                        "title"     :  ""    //答题标题
                        "type"      :  1     //答题类型
                    }...]
                }
            fail: 
                {
                    "code" :  1005
                    "messg": "系统错误"
                }
```



