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
                        "address"    : "北京市海淀区中关村东路6-3号"
                        "bname"      : ""
                        "cname"      : ""
                        "description": "测试详细地址"
                        "gname"      : "管理员"
                        "id"         : 3
                        "latitude"   : 40.014392
                        "longitude"  : 116.34002229355
                        "memo"       : "测试详细信息"
                        "name"       : "L00001"
                        "ownerName"  : "管理员"
                        "pname"      : "123"
                        "status"     : "0"
                        "type"       : "coclean"
                        "userName"   : ""
                        "warning"    : ""                     
                    }...]
                }
            fail: 
                {
                    "code" :  1005
                    "messg": "系统错误"
                }
```



