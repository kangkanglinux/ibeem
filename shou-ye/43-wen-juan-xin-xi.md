### 问卷信息

> _**www.ibeem.cn/index/survey\_list                method: POST             //获取用户下问卷及答卷信息**_

```js
request body parameter:
                //服务器将从cookie中获取用户ID

response:
         success: 
                {
                    "code" :  200
                    "list" :  [{
                        "id"          :    "123"         //答卷ID
                        "lat"         :    111.11        //答卷纬度
                        "lon"         :    40.00         //答卷经度
                        "name"        :    "123"         //问卷名称
                        "introduction":    "123"         //问卷介绍
                        "province"    :    "北京"         //答卷所在省份
                        "time"        :    "2019-1-1"    //答卷提交时间
                    }...]
                }
            fail: 
                {
                    "code" :  1005
                    "messg": "系统错误"
                }
```



