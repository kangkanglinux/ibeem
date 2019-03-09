### 建筑能耗

> _**www.ibeem.cn/project/single/building/energy         method: POST         //获取建筑能耗数据**_

```js
request body parameter:
                {
                    "buildingID"      :  157   //建筑ID
                }

response:
         success: 
                {
                    "code" :  200
                    "energyConsumption" :  {
                        "id"              :  ""
                        "aeu"             :  ""
                        "elecDs"          :  ""
                        "elecComment"     :  ""
                        "secEs"           :  ""
                        "secAu"           :  ""
                        "secDs"           :  ""
                        "secComment"      :  ""
                        "thiEs"           :  ""
                        "thiAu"           :  ""
                        "thiDs"           :  ""
                        "thiCommen"       :  ""
                        "fouEs"           :  ""
                        "fouAu"           :  ""
                        "fouDs"           :  ""
                        "fouComment"      :  ""
                        "siteSource"      :  ""
                        "siteAu"          :  ""
                        "siteSd"          :  ""
                        "siteDs"          :  ""
                        "siteComment"     :  ""
                        "siteChpMm"       :  ""
                        "siteChpFs"       :  ""
                        "siteChpRp"       :  ""
                        "siteChpAfc"      :  ""
                        "siteChpAeg"      :  ""
                        "siteChpAhg"      :  ""
                        "siteChpComment"  :  ""
                        "seuDesc"         :  ""
                        "seuPs"           :  ""
                        "seuAeu"          :  ""
                        "seuComment"      :  ""
                        "ohWd"            :  ""
                        "nwd"             :  ""
                        "ohHd"            :  ""
                        "nhd"             :  ""
                    }
                }
            fail: 
                {
                    "code" :  1005
                    "messg": "系统错误"
                }
```

> _**www.ibeem.cn/project/single/building/energy\_update      method: POST        //更新建筑能耗数据**_

```js
request body parameter:
                {
                    "buildingID"      : 7022
                    "aeu"             : ""
                    "elecDs"          : ""
                    "elecComment"     : ""
                    "secEs"           : ""
                    "secAu"           : ""
                    "secDs"           : ""
                    "secComment"      : ""
                    "thiEs"           : ""
                    "thiAu"           : ""
                    "thiDs"           : ""
                    "thiComment"      : ""
                    "fouEs"           : ""
                    "fouAu"           : ""
                    "fouDs"           : ""
                    "fouComment"      : ""
                    "siteSource"      : ""
                    "siteAu"          : ""
                    "siteSd"          : ""
                    "siteDs"          : ""
                    "siteComment"     : ""
                    "siteChpMm"       : ""
                    "siteChpFs"       : ""
                    "siteChpRp"       : ""
                    "siteChpAfc"      : ""
                    "siteChpAeg"      : ""
                    "siteChpAhg"      : ""
                    "siteChpComment"  : ""
                    "seuDesc"         : ""
                    "seuPs"           : ""
                    "seuAeu"          : ""
                    "seuComment"      : ""
                    "ohWd"            : ""
                    "nwd"             : ""
                    "ohHd"            : ""
                    "nhd"             : ""
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



