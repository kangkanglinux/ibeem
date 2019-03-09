### 建筑测点

> _**www.ibeem.cn/project/single/building/point             method: POST           //获取建筑测点信息**_

```js
request body parameter:
                {
                    "buildingID"      :  7027  //建筑ID
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



