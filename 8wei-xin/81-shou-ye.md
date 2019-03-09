### 首页

> _**www.ibeem.cn/weixin/device/list                       method: POST             //获取设备列表**_

```js
request body parameter:
                //服务器将从cookie中获取用户ID

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

> _**www.ibeem.cn/weixin/device/addAttention        method: POST        //关注设备**_

```js
request body parameter:
                {
                    "deviceID"    :   ""  //设备ID
                }

response:
         success: 
                {
                    "code" :  200
                    "devicelist" :  [{
                        "id"        :  ""       //评估数据ID
                        "device_id" :  ""       //设备ID
                        "content"   :  ""       //评估内容 
                        "created_on":  ""       //创建时间                 
                    }...]
                }
            fail: 
                {
                    "code" :  1005
                    "messg":  "未知错误"
                }
```



