### 建筑信息

> _**www.ibeem.cn/index/building\_list           method: POST            获取用户下建筑信息**_

```js
request body parameter:
                //服务器将从cookie中获取用户ID

response:
         success: 
                {
                    "code" :  200
                    "list" :  [{
                        "id"              : "1"        //建筑ID
                        "name"            : "test"     //建筑名称
                        "lat"             : 111.11     //建筑纬度
                        "lon"             : 40.00      //建筑经度
                        "city"            : "北京"     //建筑所在城市
                        "climaticProvince": ""        //建筑所在气候
                        "type"            : "ibeem"   //建筑类型
                        "level"           : "五星"     //建筑级别
                        "projectID"       : "123"     //建筑所在项目ID
                        "projectName"     : "123"     //建筑所在项目名称
                        "surveyCount"     : "12"      //建筑绑定问卷数
                        "deviceCount"     : "12"      //建筑绑定设备数
                    }...]
                }
            fail: 
                {
                    "code" :  1005
                    "messg": "系统错误"
                }
```





