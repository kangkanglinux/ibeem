### 建筑信息

> _**www.ibeem.cn/project/single/building/infomation        method: POST        //获取建筑相关数据**_

```js
request body parameter:
                {
                    "buildingID"      : 7025   //建筑ID
                }

response:
         success: 
                {
                    "code" :  200
                    "building" :  {
                        "aca"                    : ""
                        "address"                : ""
                        "adoptionStandard"       : ""
                        "applicationUnit"        : ""
                        "buildingArea"           : ""
                        "buildingClass"          : 1
                        "buildingOrientation"    : ""
                        "buildingProperty"       : ""
                        "city"                   : "北京"
                        "climaticProvince"       : "严寒"
                        "completionTime"         : 0
                        "contact"                : ""
                        "countNumber"            : ""
                        "createdOn"              : "2019-03-02T17:39:46.000Z"
                        "cun"                    : ""
                        "d2"                     : ""
                        "d9"                     : ""
                        "d13"                    : ""
                        "d15"                    : ""
                        "d16"                    : ""
                        "d17"                    : ""
                        "d21"                    : ""
                        "d22"                    : ""
                        "d25"                    : ""
                        "d27"                    : ""
                        "designIndicators"       : ""
                        "ecm"                    : ""
                        "height"                 : ""
                        "id"                     : 7025
                        "identifying"            : ""
                        "iepd"                   : ""
                        "image"                  : ""
                        "indoorEnvironment"      : ""
                        "latitude"               : 39.92
                        "level"                  : "无星级"
                        "longitude"              : 116.46
                        "name"                   : "1111"
                        "number"                 : ""
                        "participantOrganization": ""
                        "people"                 : ""
                        "projectTime"            : 0
                        "province"               : ""
                        "remark"                 : ""
                        "serviceTime"            : 0
                        "subject"                : ""
                        "time"                   : ""
                        "type"                   : "办公"
                        "unit"                   : ""
                        "updatedOn"              : "2019-03-02T17:46:44.000Z"
                        "waterSavingDesign"      : ""
                    }
                }
            fail: 
                {
                    "code" :  1005
                    "messg": "系统错误"
                }
```

> _**www.ibeem.cn/project/single/building/save\_base\_info      method: POST        //保存建筑基本信息**_

```js
request body parameter:
                {
                    "buildingID"      : 7025   //建筑ID
                }

response:
         success: 
                {
                    "code" :  200
                    "building" :  {
                        "aca"                    : ""
                        "address"                : ""
                        "adoptionStandard"       : ""
                        "applicationUnit"        : ""
                        "buildingArea"           : ""
                        "buildingClass"          : 1
                        "buildingOrientation"    : ""
                        "buildingProperty"       : ""
                        "city"                   : "北京"
                        "climaticProvince"       : "严寒"
                        "completionTime"         : 0
                        "contact"                : ""
                        "countNumber"            : ""
                        "createdOn"              : "2019-03-02T17:39:46.000Z"
                        "cun"                    : ""
                        "d2"                     : ""
                        "d9"                     : ""
                        "d13"                    : ""
                        "d15"                    : ""
                        "d16"                    : ""
                        "d17"                    : ""
                        "d21"                    : ""
                        "d22"                    : ""
                        "d25"                    : ""
                        "d27"                    : ""
                        "designIndicators"       : ""
                        "ecm"                    : ""
                        "height"                 : ""
                        "id"                     : 7025
                        "identifying"            : ""
                        "iepd"                   : ""
                        "image"                  : ""
                        "indoorEnvironment"      : ""
                        "latitude"               : 39.92
                        "level"                  : "无星级"
                        "longitude"              : 116.46
                        "name"                   : "1111"
                        "number"                 : ""
                        "participantOrganization": ""
                        "people"                 : ""
                        "projectTime"            : 0
                        "province"               : ""
                        "remark"                 : ""
                        "serviceTime"            : 0
                        "subject"                : ""
                        "time"                   : ""
                        "type"                   : "办公"
                        "unit"                   : ""
                        "updatedOn"              : "2019-03-02T17:46:44.000Z"
                        "waterSavingDesign"      : ""
                    }
                }
            fail: 
                {
                    "code" :  1005
                    "messg": "系统错误"
                }
```



