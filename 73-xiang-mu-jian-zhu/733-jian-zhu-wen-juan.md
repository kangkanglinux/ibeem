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



