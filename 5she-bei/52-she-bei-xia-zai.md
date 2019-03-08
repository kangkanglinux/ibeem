### 设备下载

> _**www.ibeem.cn/device/download/history               method: POST             //获取用户工单下载历史**_

```js
request body parameter:
                //服务器将从cookie中获取用户ID

response:
         success: 
                {
                    "code" :  200
                    "list" :  [{
                        "id"          :    ""    //工单ID
                        "deviceName"  :    ""    //设备名称
                        "estimateTime":    ""    //预估时间
                        "startTime"   :    ""    //工单开始时间
                        "endTime"     :    ""    //工单下载完成时间
                        "percent"     :    ""    //工单完成度
                        "status"      :    ""    //工单处理状态(finish || unfinish || fail)
                        "time"        :    ""    //工单创建时间
                        "url"         :    ""    //工单数据文件包路径
                    }...]
                }
            fail: 
                {
                    "code" :  1005
                }
```

> _**www.ibeem.cn/device/download/create\_work\_order          method: POST          //创建下载工单**_

```js
request body parameter:
                {
                    "deviceids"      :     ""    //设备ID
                    "startTime"      :     ""    //工单数据开始时间
                    "endTime"        :     ""    //工单数据结束时间
                    "workDay"        :     ""    //是否是工作日  (1: 工作日   0: 非工作日  2:工作日和非工作日)
                    "startWorkTime"  :     ""    //上班时间
                    "endWorkTime"    :     ""    //下班时间
                    "d1"             :     ""    //温度 (0:未选   1:已选)
                    "d2"             :     ""    //湿度 (0:未选 1:已选)
                    "d3"             :     ""    //PM2.5   (0:未选 1:已选)
                    "d4"             :     ""    //CO2     (0:未选 1:已选)
                    "d5"             :     ""    //光照强度 (0:未选 1:已选)
                }

response:
         success: 
                {
                    "code" :  200
                    "workOrder" :  [{
                        "id"          :    ""    //工单纪录ID
                        "deviceName"  :    ""    //设备名称
                        "startTime"   :    ""    //工单开始时间
                        "endTime"     :    ""    //工单下载完成时间
                        "time"        :    ""    //工单创建时间
                        "status"      :    ""    //工单状态
                        "url"         :    ""    //工单数据文件包路径
                        "workid"      :    ""    //工单ID
                    }...]
                }
            fail: 
                {
                    "code" :  1001
                    "messg": "系统错误"
                }
```



