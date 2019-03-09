### 项目信息

> _**www.ibeem.cn/project/single/info             method: POST            //获取项目信息**_

```js
request body parameter:
                {
                    "projectID"       :  157   //项目ID
                }

response:
         success: 
                {
                    "code" :  200
                    "project" :  {
                        "id"          : 157    //项目ID
                        "decribe"     : ""     //项目描述
                        "image"       : ""     //项目图片地址
                        "name"        : ""     //项目名称
                        "peopleCount" : ""     //项目下用户数                        
                    }
                }
            fail: 
                {
                    "code" :  1005
                    "messg": "系统错误"
                }
                ||
                {
                    "code" :  4005
                    "messg":  "该项目已被删除"
                }
```

> _**www.ibeem.cn/project/single/building     method: POST         //项目下建筑信息**_

```js
request body parameter:
                {
                    "projectID"       :  157   //项目ID
                }

response:
         success: 
                {
                    "code" :  200
                    "list" :  [{
                        "id"          : 1570    //建筑ID
                        "latitude"    : 39.92   //建筑纬度
                        "longitude"   : 116.46  //建筑经度
                        "name"        : ""      //建筑名称
                        "type"        : ""      //建筑类别
                        "city"        : ""      //建筑城市                     
                    }...]
                }
            fail: 
                {
                    "code" :  1005
                    "messg": "系统错误"
                }
```

> _**www.ibeem.cn/project/single/survey    method: POST         //项目下问卷信息**_

```js
request body parameter:
                {
                    "projectID"       :  157   //项目ID
                }

response:
         success: 
                {
                    "code" :  200
                    "list" :  [{
                        "id"          : 1570    //问卷ID
                        "title"       : ""      //问卷标题
                        "name"        : ""      //问卷名称
                        "introduction": ""      //问卷描述
                        "count"       : ""      //答卷数量                     
                    }...]
                }
            fail: 
                {
                    "code" :  1005
                    "messg": "系统错误"
                }
```



