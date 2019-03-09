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
                    "list" :  [{
                        "answerTime"   : ""       //答卷创建时间
                        "deviceID"     : ""       //绑定设备ID
                        "deviceName"   : ""       //绑定设备名称
                        "deviceStatus" : ""       //绑定设备状态
                        "endTime"      : ""       //测点结束时间
                        "id"           : 161      //测点ID
                        "image"        : ""       //测点图片地址
                        "name"         : "123"    //测点名称
                        "positionDesc" : "123"    //测点描述
                        "startTime"    : ""       //测点开始时间
                        "surveyID"     : ""       //绑定问卷时间 
                        "surveyTitle"  : ""       //绑定问卷标题 
                    }...]
                }
            fail: 
                {
                    "code" :  1005
                    "messg": "系统错误"
                }
```

> _**www.ibeem.cn/project/single/building/point\_del         method: POST        //删除测点**_

```js
request body parameter:
                {
                    "buildingPointID"  :  7027    //建筑测点ID
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



