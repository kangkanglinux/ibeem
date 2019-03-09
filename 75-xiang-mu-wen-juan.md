### 项目问卷

> _**www.ibeem.cn/project/single/survey           method: POST           //获取项目下问卷列表**_

```js
request body parameter:
                {
                    "projectID"       : 111   //项目ID
                }

response:
         success: 
                {
                    "code" :  200
                    "list" :  [{
                        "id"          :  12       //问卷ID
                        "title"       :  ""       //问卷标题
                        "introduction":  ""       //问卷简介
                        "name"        :  ""       //问卷创建者名称
                        "count"       :  123      //答卷数量
                    }...]
                }
            fail: 
                {
                    "code" :  1005
                    "messg": "系统错误"
                }
```

> _**绑定问卷**_
>
> _**www.ibeem.cn/project/single/survey/search        method: POST           //搜索该项目能绑定的问卷**_
>
> _**www.ibeem.cn/project/single/survey/bind             method:POST           //绑定问卷**_

```js
//搜索该项目能绑定的问卷
request body parameter:
                {
                    "projectID"       : 111   //项目ID
                    "surveyID"        : 23    //问卷ID
                }

response:
         success: 
                {
                    "code" :  200
                    "list" :  [{
                        "id"          :  12       //问卷ID
                        "title"       :  ""       //问卷标题
                    }...]
                }
            fail: 
                {
                    "code" :  1005
                    "messg": "系统错误"
                }
```

```js
//绑定问卷
request body parameter:
                {
                    "projectID"       : 111   //项目ID
                    "surveyID"        : 23    //问卷ID
                }

response:
         success: 
                {
                    "code" :  200
                    "list" :  [{
                        "id"          :  12       //问卷ID
                        "title"       :  ""       //问卷标题
                    }...]
                }
            fail: 
                {
                    "code" :  1005
                    "messg": "系统错误"
                }
```



