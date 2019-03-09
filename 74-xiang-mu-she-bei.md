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

> _**项目添加设备**_
>
> _**www.ibeem.cn/project/single/device/search         method: POST             //搜索设备**_
>
> _**www.ibeem.cn/project/single/device/add             method: POST             //添加设备**_

```js
//搜索设备
request body parameter:
                //服务器将从cookie中获取用户ID


response:
         success: 
                {
                    "code" :  200
                    "list" :  [{
                        "id"   : 10    //设备ID
                        "name" : ""    //设备名称
                    }...]
                }
            fail: 
                {
                    "code" :  1005
                    "messg": "系统错误"
                }
```

```js
//添加设备
request body parameter:
                {
                    "projectID":  123   //项目ID
                    "ids"      :  "1,2" //设备ID
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

> _**www.ibeem.cn/project/single/device/recycle      method: POST        //回收设备**_

```js
request body parameter:
                //服务器将从cookie中获取用户ID
                {
                    "ids"      :  "1,2" //设备ID
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

> _**设置关注者**_
>
> _**www.ibeem.cn/project/single/device/attention                  method: POST        //获取能成为该项目关注者的用户**_
>
> _**www.ibeem.cn/project/single/device/addAttention          method: POST        //添加关注者**_

```js
//获取能成为该项目关注者的用户
request body parameter:
                {
                    "projectID"  :  123   //项目ID
                }

response:
         success: 
                {
                    "code" :  200
                    "user" :  {
                        "id"      :  123  //用户ID
                        "name"    :  ""   //用户名称
                        "portrait":  ""   //用户头像
                    }
                }
            fail: 
                {
                    "code" :  1005
                    "messg": "系统错误"
                }
```

```js
//添加关注者
request body parameter:
                {
                    "ids"         :  "1,2" //设备ID
                    "userID"      :  123   //用户ID       
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

> _**www.ibeem.cn/project/single/device/relieve         method: POST         //接触关注者**_

```js
request body parameter:
                {
                    "deviceID"         :  "1,2" //设备ID  
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



