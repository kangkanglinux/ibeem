### 项目设备

> _**www.ibeem.cn/project/single/device             method: POST           //获取项目设备列表**_

```js
request body parameter:
                {
                    "projectID"       :  111   //项目ID
                }

response:
         success: 
                {
                    "code" :  200
                    "list" :  [{
                        "id"          : 216    //项目ID
                        "decribe"     : ""     //项目描述
                        "image"       : ""     //项目图片地址
                        "name"        : ""     //项目名称                        
                    }...]
                }
            fail: 
                {
                    "code" :  1005
                    "messg": "系统错误"
                }
```



