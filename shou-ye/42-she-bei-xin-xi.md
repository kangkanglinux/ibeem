### 设备信息

> _**www.ibeem.cn/index/device\_list              method: POST          获取用户下设备信息并展示**_

```js
request body parameter:
                //服务器将从cookie中获取用户ID

response:
         success: 
                {
                    "code" :  200
                    "list" :  [{
                        "id"        : "123"      //设备ID
                        "deviceName": "test"     //设备名称      
                        "latitude"  : "111.11"   //设备纬度
                        "longitude" : "40.00"    //设备经度
                        "address"   : "test"     //设备所在地址
                        "status"    : "1"        //设备在线状态
                        "province"  : "北京"     //设备所在城市
                    }...]
                }
            fail: 
                {
                    "code" :  1005
                    "messg": "系统错误"
                }device数据说明:
```





