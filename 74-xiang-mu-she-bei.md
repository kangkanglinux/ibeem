### 项目设备

> _**www.ibeem.cn/project/single/device             method: POST           //获取项目设备列表**_

```js
request body parameter:
                {
                    "projectID"       : 111   //项目ID
                }

response:
         success: 
                {
                    "code" :  200
                    "list" :  [{
                        "address"    : "北京市海淀区中关村东路6-3号"      //设备地址
                        "bname"      : ""                             //设备绑定建筑名称
                        "cname"      : ""                             //设备绑定测点名称
                        "description": "测试详细地址"                   //设备描述
                        "gname"      : "管理员"                        //设备关注者
                        "id"         : 3                              //设备ID
                        "latitude"   : 40.014392                      //设备纬度
                        "longitude"  : 116.34002229355                //设备经度
                        "memo"       : "测试详细信息"                   //设备备注
                        "name"       : "L00001"                       //设备名称
                        "ownerName"  : "管理员"                        //设备拥有者
                        "pname"      : "123"                          //设备绑定项目名称
                        "status"     : "0"                            //设备状态
                        "type"       : "coclean"                      //设备类型
                        "userName"   : ""                             //设备使用者名称
                        "warning"    : ""                             //设备告警
                    }...]
                }
            fail: 
                {
                    "code" :  1005
                    "messg": "系统错误"
                }
```



