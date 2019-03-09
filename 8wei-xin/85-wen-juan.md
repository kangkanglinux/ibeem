### 问卷

> _**www.ibeem.cn/weixin/survey/release              method: POST             //获取发布问卷**_

```js
request body parameter:
                {
                    "deviceId"     :   ""        //设备ID
                    "startTime"    :   ""        //设备数据搜索开始时间
                    "endTime"      :   ""        //设备数据搜索结束时间     
                }

response:
         success: 
                {
                    "result"       : "success"
                    "deviceId"     : ""        //设备ID
                    "deviceName"   : ""        //设备名称
                    "data"  : {
                        "tem"           : 21.6 //温度
                        "hum"           : 21   //湿度
                        "pm"            : 21   //pm25
                        "co2"           : 21   //co2
                        "lightIntensity": 21   //光照   
                    }
                }
            fail: 
                {
                    "result"   : "error"
                }
```



