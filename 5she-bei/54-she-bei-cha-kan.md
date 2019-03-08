### 设备数据查看

_**www.ibeem.cn/device/parameter              method: POST         //获取用户下设备数据参数**_

```js
request body parameter:
                //服务器将从cookie中获取用户ID

response:
         success: 
                {
                    "code" :  200
                    "list" :  [{
                        "id"          :    ""    //参数数据ID
                        "maxCo2"      :    ""    //最大CO2值
                        "minCO2"      :    ""    //最小CO2值
                        "maxHum"      :    ""    //最大湿度值
                        "minHum"      :    ""    //最小湿度值
                        "maxLight"    :    ""    //最大光照值
                        "minLight"    :    ""    //最小光照值
                        "maxTem"      :    ""    //最大温度值
                        "minTem"      :    ""    //最小温度值
                        "maxPm25"     :    ""    //最大pm25值
                        "minPm25"     :    ""    //最小pm25值
                        "userId"      :    24    //用户ID
                        "updatedOn"   :    ""    //跟新时间
                    }...]
                }
            fail: 
                {
                    "code" :  1005
                    "messg": "查找失败"
                }
```

> _**www.ibeem.cn/device/view/on\_line\_rate           method: POST           //获取设备在线状态数据**_

```js
request body parameter:
                {
                    "deviceID"  :  58              //设备ID
                    "startTime" :  ""              //查询开始时间
                    "endTime"   :  ""              //查询结束时间
                }

response:
         success: 
                {
                    "code"      :  200
                    "deviceID"  :  58              //设备ID
                    "deviceName": ""               //设备名称
                    "list" :  [{
                        "time"          :    ""    //时间
                        "onlineRate"    :    1     //在线状态(1:在线  0:不在线)
                    }...]
                }
            fail: 
                {
                    "code" :  1005
                    "messg": "系统错误"
                }
```

> _**www.ibeem.cn/device/view/environment      method: POST           //获取设备采集的数据**_

```js
request body parameter:
                {
                    "deviceId"          : 58        //设备ID
                    "startTime"         : ""        //查询开始时间
                    "endTime"           : ""        //查询结束时间
                    "startWorkTime"     : ""        //查询开始上班时间
                    "endWorkTime"       : ""        //查询结束上班时间
                    "workDay"           : ""        //是否是工作日(1: 工作日  0:非工作日  2:工作日和非工作日)
                }

response:
         success: 
                {
                    "result"            : "success" //获取成功
                    "deviceId"          : 58        //设备ID
                    "deviceName"        : ""        //设备名称
                    "data" :  [{
                        "co2"           : ""        //co2值
                        "hum"           : 1         //湿度值
                        "lightIntensity": 1         //光照值
                        "pm"            : 6         //pm2.5值
                        "tem"           : 22.2      //温度值
                        "time"          : ""        //时间
                    }...]
                }
            fail: 
                {
                    "code" :  1005
                    "messg": "系统错误"
                }
```

> _**www.ibeem.cn/device/view/environment\_data\_align           method: POST           //数据对齐**_

```js
request body parameter:
                {
                    "deviceId"          : 58        //设备ID
                    "startTime"         : ""        //查询开始时间
                    "endTime"           : ""        //查询结束时间
                    "startWorkTime"     : ""        //查询开始上班时间
                    "endWorkTime"       : ""        //查询结束上班时间
                    "workDay"           : ""        //是否是工作日(1: 工作日  0:非工作日  2:工作日和非工作日)
                    "step"              : ""        //对齐时间间隔(分)
                }

response:
         success: 
                {
                    "result"            : "success" //获取成功
                    "deviceId"          : 58        //设备ID
                    "deviceName"        : ""        //设备名称
                    "data" :  [{
                        "co2"           : ""        //co2值
                        "hum"           : 1         //湿度值
                        "lightIntensity": 1         //光照值
                        "pm"            : 6         //pm2.5值
                        "tem"           : 22.2      //温度值
                        "time"          : ""        //时间
                    }...]
                }
            fail: 
                {
                    "code" :  1005
                    "messg": "系统错误"
                }
```



