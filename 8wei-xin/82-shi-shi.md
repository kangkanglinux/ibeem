### 实时

> _**www.ibeem.cn/weixin/device/realtime\_data          method: POST          //获取实时数据**_

```js
request body parameter:
                {
                    "deviceId"        : ""     //设备ID     
                }

response:
         success: 
                {
                    "status" :  0
                    "devicelist" :  [{
                        "id"          : 216    //设备ID
                        "name"        : ""     //设备名称
                        "address"     : ""     //设备地址
                        "latitude"    : 111.11 //纬度
                        "longitude"   : 40.0   //经度
                        "onlineStatus": ""     //设备在线状态                      
                    }...]
                }
            fail: 
                {
                    "status" :  1005
                }
```



