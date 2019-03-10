### 设备列表

> _**www.ibeem.cn/device/page\_list         method: POST        //获取所在页面的设备**_

```js
request body parameter:
                //服务器将从cookie中获取用户ID
                {
                    "pageNo": 所在页数    
                }
response:
         success: 
                {
                    "code"   :  200
                    "list": [{
                        "id"         : "" //设备ID
                        "deviceName" : "" //设备名称
                        "userName"   : "" //设备使用者名称
                        "ownerName"  : "" //设备拥有者名称
                        "latitude"   : "" //设备纬度
                        "longitude"  : "" //设备经度
                        "type"       : "" //设备类型
                        "address"    : "" //设备所在地址
                        "stutas"     : "" //设备状态
                        "waining"    : "" //设备告警状态
                        "description": "" //设备描述
                        "memo"       : "" //备注
                        "pname"      : "" //设备绑定项目名称
                        "gname"      : "" //设备关注者名称
                        "cname"      : "" //设备绑定测点名称
                        "bname"      : "" //设备绑定建筑名称
                    }..]
                    "pageNo"         : ""  //所在页数
                    "amount"         : 600 //设备总数量
                    "maxPage"        : 12  //总页数
                    "pageSize"       : 50  //每页展示设备数
                }
            fail: 
                {
                    "code"   :  1005
                    "messg"  : "系统错误"
                }
```

> _**www.ibeem.cn/device/status            method: POST        //获取设备状态**_

```js
request body parameter:
                {
                    "deviceID": 设备ID    
                }
response:
         success: 
                {
                    "code"    :  200
                    "status"  :  true || false  //设备状态(coclean和ibeem设备都是从设备服务器获取状态)
                }
            fail: 
                {
                    "code"    :  1005
                    "messg"   :  "系统错误"
                }
```

> _**www.ibeem.cn/device/info            method: POST      //点击进入设备信息页面发送该请求获取设备详细信息**_

```js
request body parameter:
                {
                    "deviceID": 设备ID    
                }
response:
         success: 
                {
                    "code"   :  200
                    "device" :  {
                        "id"          :  ""      //设备ID
                        "QRcode"      :  ""      //设备二维码图片路径
                        "address"     :  ""      //设备地址
                        "describe"    :  ""      //设备描述
                        "gname"       :  ""      //设备关注者名称
                        "imageList"   :  ""      //用户上传设备相关图片路径
                        "latitude"    :  40.00   //设备纬度
                        "longitude"   :  116.34  //设备经度
                        "memo"        :  ""      //设备备注
                        "name"        :  ""      //设备名称
                        "onlineStatus":  "0"     //设备在线状态
                        "owner"       :  ""      //设备拥有者名称
                        "type"        :  ""      //设备类型
                        "user"        :  ""      //设备使用者名称
                        "warnning"    :  ""      //设备告警
                        "wechat"      :  ""      //设备绑定微信用户名
                    }
                }
            fail: 
                {
                    "code" :  1005
                    "messg": "系统错误"
                }
```

> _**www.ibeem.cn/device/search              method: POST                //设备搜索**_

```js
request body parameter:
                {
                    "name": ""  //搜索字符串
                }
response:
         success: 
                {
                    "code"   :  200
                    "device" :  {
                        "id"          :  ""      //设备ID
                        "address"     :  ""      //设备地址
                        "describe"    :  ""      //设备描述
                        "deviceName"  :  ""      //设备名称
                        "bname"       :  ""      //设备绑定建筑名称
                        "cname"       :  ""      //设备绑定测点名称
                        "pname"       :  ""      //设备绑定项目名称
                        "gname"       :  ""      //设备关注者名称
                        "imageList"   :  ""      //用户上传设备相关图片路径
                        "latitude"    :  40.00   //设备纬度
                        "longitude"   :  116.34  //设备经度
                        "memo"        :  ""      //设备备注
                        "onlineStatus":  "0"     //设备在线状态
                        "ownerName"   :  ""      //设备拥有者名称
                        "type"        :  ""      //设备类型
                        "userName"    :  ""      //设备使用者名称
                        "warnning"    :  ""      //设备告警
                        "status"      :  ""      //设备状态
                    }
                }
            fail: 
                {
                    "code" :  1005
                    "messg": "系统错误"
                }
```

> _**www.ibeem.cn/admin/device/add                 method: POST                //管理员添加设备**_

```js
request body parameter:
                {
                    "deviceid"  : ""       //设备ID
                    "name"      : ""       //设备名称
                    "type"      : ""       //设备类型
                    "physicalId": ""       //设备MAC
                }
response:
         success: 
                {
                    "code"      :  200
                    "id"        :  1234    //设备存入数据库ID
                }
            fail: 
                {
                    "code" :  1005
                    "messg": "系统错误"
                }
```

> _**www.ibeem.cn/admin/device/import             method: POST           //管理员导入设备**_

```js
request body parameter:
                {
                    "deviceid"  : ""       //设备ID
                    "name"      : ""       //设备名称
                    "type"      : ""       //设备类型
                    "physicalId": ""       //设备MAC
                }
response:
         success: 
                {
                    "code"      :  200
                    "id"        :  1234    //设备存入数据库ID
                }
            fail: 
                {
                    "code" :  1005
                    "messg": "系统错误"
                }
```



