### 实时

> _**www.ibeem.cn/weixin/device/realtime\_data          method: POST          //获取实时数据**_

```js
request body parameter:
                {
                    "deviceId"          : ""     //设备ID     
                }

response:
         success: 
                {
                    "status"            :  0 
                    "zt"                :  true  //设备状态
                    "devicelist" :  [{
                        "tem"           : 21.6   //温度
                        "hum"           : 21     //湿度
                        "pm"            : 21     //pm25
                        "co2"           : 21     //co2
                        "lightIntensity": 21     //光照                    
                    }...]
                }
            fail: 
                {
                    "status" :  -1
                    "meg"    :  "未知错误"
                }
```



