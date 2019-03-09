### 设备

> _**www.ibeem.cn/weinxin/device/detail       method: POST          //微信获取设备详情**_

```js
request body parameter:
                {
                    "deviceId"          : ""     //设备ID     
                }

response:
         success: 
                {
                    "code"    : 200
                    "device"  : {
                        "name"     :   ""        //设备名称
                        "describe" :   ""        //设备描述
                        "memo"     :   ""        //设备备注
                        "address"  :   ""        //设备地址
                        "latitude" :   ""        //设备纬度
                        "longitude":   ""        //设备经度
                        "imageList":   ""        //设备图片
                        "warning"  :   ""        //设备告警
                    }
                }
            fail: 
                {
                    "code"   : 1005
                    "meg"    :  "未知错误"
                }
```



