### 建筑问卷

> _**www.ibeem.cn/project/single/building/survey           method: POST          //获取建筑问卷列表**_

```js
request body parameter:
                {
                    "buildingID"      :  7027   //建筑ID
                }

response:
         success: 
                {
                    "code" :  200
                    "list" :  [{
                        "id"          : ""     //问卷ID
                        "title"       : ""     //问卷标题
                        "introduction": ""     //问卷介绍 
                        "name"        : ""     //问卷创建者名称
                        "count"       : 12     //问卷答卷数
                    }...]
                }
            fail: 
                {
                    "code" :  1005
                    "messg": "系统错误"
                }
```

> _**www.ibeem.cn/project/single/building/survey\_add          method: POST        //获取建筑可以绑定的问卷**_

```js
request body parameter:
                {
                    "buildingID"      :  7027   //建筑ID
                }

response:
         success: 
                {
                    "code" :  200
                    "list" :  [{
                        "id"          : ""     //问卷ID
                        "title"       : ""     //问卷标题
                    }...]
                }
            fail: 
                {
                    "code" :  1005
                    "messg": "系统错误"
                }
```

> _**www.ibeem.cn/project/single/building/survey\_bind      method: POST         //建筑绑定问卷**_

```js
request body parameter:
                {
                    "buildingID"      :  7027   //建筑ID
                    "surveyID"        :  123    //问卷ID
                }

response:
         success: 
                {
                    "code" :  200
                }
            fail: 
                {
                    "code" :  1005
                    "messg": "系统错误"
                }
```

> _**分析问卷，下载问卷，统计问卷实现同&lt;6.问卷&gt;里一样**_



