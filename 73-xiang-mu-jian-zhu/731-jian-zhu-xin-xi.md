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
                    "climaticProvince"       : "严寒"
                    "image"                  : ""
                    "city"                   : ""
                    "latitude"               : 39.92
                    "longitude"              : 116.46
                    "buildingClass"          : 1
                    "id":                    : 7025
                    "unit"                   : ""
                    "subject"                : ""
                    "people"                 : ""
                    "contact"                : ""
                    "name"                   : ""
                    "type"                   : ""
                    "address"                : ""
                    "province"               : ""
                    "applicationUnit"        : ""
                    "participantOrganization": ""
                    "time"                   : ""
                    "adoptionStandard"       : ""
                    "level"                  : "无星级"
                    "identifying"            : ""
                    "projectTime"            : 1970-01-01
                    "completionTime"         : 1970-01-01
                    "serviceTime"            : 1970-01-01
                    "buildingArea"           : ""
                    "buildingOrientation"    : ""
                    "remark"                 : ""
                    "aca"                    : ""
                    "height"                 : ""
                    "buildingProperty"       : ""
                    "cun"                    : ""
                    "countNumber"            : ""
                    "number"                 : ""
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

> _**www.ibeem.cn/project/single/building/save\_design\_info   method: POST       //保存关键设计评价指标**_

```js
request body parameter:
                {
                    "id"               : 68
                    "buildingID"       : 7022
                    "landArea"         : ""
                    "buildingArea"     : ""
                    "subsurfaceArea"   : ""
                    "groundFloorArea"  : ""
                    "gas"              : ""
                    "municipalHeating" : ""
                    "electricPower"    : ""
                    "coal"             : ""
                    "ubadtec"          : ""
                    "deer"             : ""
                    "tpi"              : ""
                    "hvaacsdec"        : ""
                    "hvaacsdectr"      : ""
                    "totalWater"       : ""
                    "ncw"              : ""
                    "ntwa"             : ""
                    "blhw"             : ""
                    "rhc"              : ""
                    "tpohwgbre"        : ""
                    "bec"              : ""
                    "renewableCapacity": ""
                    "rege"             : ""
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

> _**www.ibeem.cn/project/single/building/save\_energy\_info     method: POST       //保持节能措施**_

```js
request body parameter:
                {
                    "buildingID"             : 7022
                    "owccbo"                 : "" 
                    "ehr"                    : "" 
                    "awr"                    : "" 
                    "pces"                   : "" 
                    "erStandard"             : "" 
                    "wsStandard"             : "" 
                    "whwhu"                  : "" 
                    "itemizedMetering"       : "" 
                    "cchp"                   : "" 
                    "reu"                    : "" 
                    "ltv"                    : "" 
                    "lightingControl"        : "" 
                    "egceas"                 : "" 
                    "esee"                   : "" 
                    "csh"                    : "" 
                    "vvf"                    : "" 
                    "csf"                    : "" 
                    "tfotds"                 : "" 
                    "endSystem"              : "" 
                    "totalCapacity"          : "" 
                    "rqi"                    : "" 
                    "totalHeat"              : "" 
                    "ci"                     : "" 
                    "cop"                    : "" 
                    "eer"                    : ""
                    "iplv"                   : "" 
                    "bte"                    : "" 
                    "ws"                     : "" 
                    "ewK"                    : "" 
                    "rk"                     : "" 
                    "exteriorWindowK"        : "" 
                    "exteriorWindowSC"       : "" 
                    "buildingOrientation"    : ""  
                    "owcoar"                 : "" 
                    "tcwcoar"                : "" 
                    "dohss"                  : "" 
                    "ehrf"                   : "" 
                    "nwats"                  : "" 
                    "potwcesm"               : "" 
                    "whwhsd"                 : "" 
                    "cchpSystemDesign"       : ""  
                    "reuf"                   : "" 
                    "sk"                     : "" 
                    "ssc"                    : "" 
                    "wwr"                    : "" 
                    "sp"                     : "" 
                    "acscwst"                : "" 
                    "accwrt"                 : "" 
                    "achawst"                : "" 
                    "achwrt"                 : "" 
                    "owccbo"                 : "" 
                    "ehr"                    : "" 
                    "awr"                    : "" 
                    "pces"                   : "" 
                    "erStandard"             : "" 
                    "wsStandard"             : "" 
                    "whwhu"                  : "" 
                    "itemizedMetering"       : ""  
                    "cchp"                   : "" 
                    "reu"                    : "" 
                    "ltv"                    : "" 
                    "lightingControl"        : "" 
                    "egceas"                 : "" 
                    "esee"                   : "" 
                    "csh"                    : "" 
                    "vvf"                    : ""  
                    "csf"                    : "" 
                    "tfotds"                 : "" 
                    "endSystem"              : "" 
                    "totalCapacity"          : "" 
                    "rqi"                    : "" 
                    "totalHeat"              : "" 
                    "ci"                     : "" 
                    "cop"                    : "" 
                    "eer"                    : "" 
                    "iplv"                   : "" 
                    "bte"                    : "" 
                    "ws"                     : "" 
                    "ewK"                    : "" 
                    "rk"                     : "" 
                    "exteriorWindowK"        : "" 
                    "exteriorWindowSC"       : "" 
                    "buildingOrientation"    : "" 
                    "owcoar"                 : "" 
                    "tcwcoar"                : "" 
                    "dohss"                  : "" 
                    "ehrf"                   : "" 
                    "nwats"                  : "" 
                    "potwcesm"               : "" 
                    "whwhsd"                 : "" 
                    "cchpSystemDesign"       : "" 
                    "reuf"                   : "" 
                    "sk"                     : "" 
                    "ssc"                    : "" 
                    "wwr"                    : "" 
                    "sp"                     : "" 
                    "acscwst"                : "" 
                    "accwrt"                 : "" 
                    "achawst"                : "" 
                    "achwrt"                 : "" 
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

> _**www.ibeem.cn/project/single/building/save\_indoor\_info      method: POST       //保存室内环境措施数据**_

```js
request body parameter:
                {
                    "buildingID"             : 7022
                    "naturalVentilation"     : "" 
                    "naturalLighting"        : "" 
                    "shade"                  : "" 
                    "improvedNaturalLighting": ""
                    "aeoa"                   : "" 
                    "airQualityControl"      : "" 
                    "accessibilityFacilities": ""
                    "nvm"                    : "" 
                    "voaarfar"               : "" 
                    "nlsar"                  : ""
                    "shadingForm"            : "" 
                    "inlm"                   : "" 
                    "actcm"                  : "" 
                    "aqcd"                   : "" 
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

> _**www.ibeem.cn/project/single/building/save\_indoor\_parameter\_info   method: POST    //保存室内环境参数设计**_

```js
request body parameter:
                {
                    "buildingID"       : 7022
                    "functionRoom"     : "" 
                    "st"               : "" 
                    "sh"               : "" 
                    "wt"               : ""
                    "wh"               : "" 
                    "fav"              : "" 
                    "svoi"             : ""
                    "ugr"              : "" 
                    "u0"               : "" 
                    "ra"               : ""
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

> _**www.ibeem.cn/project/single/building/save\_water\_info     method: POST       //保存节水设计**_

```js
request body parameter:
                {
                    "id"                      : 92
                    "buildingID"              : 7022
                    "rainWaterSavings"        : ""
                    "rainwaterRecycling"      : ""
                    "municipalWater"          : ""
                    "homemadeWater"           : ""
                    "com"                     : ""
                    "waterSavingIrrigation"   : ""
                    "coolingWaterConservation": ""
                    "rainwaterSavingMeasure"  : ""
                    "uorfr"                   : ""
                    "usow"                    : ""
                    "ntsowu"                  : ""
                    "fowsi"                   : ""
                    "rainWaterReturn"         : ""
                    "wawc"                    : ""
                    "ntwa"                    : ""
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



