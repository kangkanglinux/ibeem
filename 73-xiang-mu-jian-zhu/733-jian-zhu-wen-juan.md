### 建筑问卷

> _**www.ibeem.cn/project/single/building/survey           method: POST          //获取建筑问卷列表**_

```js
request body parameter:
                {
                    "buildingID"       :  7027   //建筑ID
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



