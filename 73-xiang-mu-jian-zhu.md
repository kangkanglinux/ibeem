### 项目建筑

> _**www.ibeem.cn/project/single/building              method: POST            //项目建筑信息**_

```js
request body parameter:
                {
                    "projectID"       :  157   //项目ID
                }

response:
         success: 
                {
                    "code" :  200
                    "list" : [{
                        "id"        : 1570    //建筑ID
                        "latitude"  : 39.92   //建筑纬度
                        "longitude" : 116.46  //建筑经度
                        "name"      : ""      //建筑名称
                        "type"      : ""      //建筑类别
                        "city"      : ""      //建筑城市
                    }...]
                }
            fail: 
                {
                    "code" :  1005
                    "messg": "系统错误"
                }
```

> _**www.ibeem.cn/project/single/building/increase         method: POST       //添加建筑**_

```js
request body parameter:
                {
                    "projectID"     :  157    //项目ID
                    "name"          :  ""     //建筑名称
                    "buildingType"  :  ""     //建筑类型
                    //ibeem项目有下面的参数
                    "city"          :  ""     //城市
                    "latitude"      :  ""     //纬度
                    "longitude"     :  ""     //经度
                    "climatic"      :  ""     //气候
                    "buildingClass" :  ""     //建筑类型（公共建筑 || 居住建筑）
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

> _**www.ibeem.cn/project/single/building/delete       method: POST        //删除建筑**_

```js
request body parameter:
                {
                    "type"             :  ""    //建筑类型
                    "buildingID"       :  157   //建筑ID
                    //top建筑ID如下
                    "topBuildingID"    :  157   //top建筑ID
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

> _**www.ibeem.cn/project/single/building/import      method: POST      //导入建筑**_

```js
query parameter:
                {
                    "projectID"  :  ""   //项目ID
                    "type"       :  ""   //建筑类型
                    "filepath"   :  ""   //模板路径
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
                ||
                {
                    "code" : 1001
                    "messg": "模板数据不对"
                }
                ||
                {
                    "code" : 1000
                    "messg": "模板没有数据"
                }
                ||
                {
                    "code" : 1003
                    "messg": "建筑名称必须填"
                }
```



