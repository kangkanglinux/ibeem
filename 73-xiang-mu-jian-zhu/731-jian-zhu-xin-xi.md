### 建筑信息

> www.ibeem.cn/project/single/building/infomation        method: POST        //获取建筑相关数据

```js
request body parameter:
                {
                    "buildingID"      : 7025   //建筑ID
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



