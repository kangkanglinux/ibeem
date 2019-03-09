### 问卷成员

> _**www.ibeem.cn/project/single/member                method: POST            //获取项目成员**_

```js
request body parameter:
                {
                    "projectID"       : 111       //项目ID
                }

response:
         success: 
                {
                    "code" :  200
                    "list" :  [{
                        "id"          :  12       //成员ID
                        "name"        :  ""       //成员名称
                        "portrait"    :  ""       //成员肖像
                        "role"        :  ""       //角色
                    }...]
                }
            fail: 
                {
                    "code" :  1005
                    "messg": "系统错误"
                }
```

> _**www.ibeem.cn/project/single/member/search        method: POST        //搜索用户**_

```js
request body parameter:
                {
                    "projectID"       : 111       //项目ID
                    "key"             : ""        //搜索字符串
                }

response:
         success: 
                {
                    "code" :  200
                    "arrayList" :  [{
                        "id"          :  12       //成员ID
                        "name"        :  ""       //成员名称
                        "portrait"    :  ""       //成员肖像
                    }...]
                }
            fail: 
                {
                    "code" :  1005
                    "messg": "系统错误"
                }
```

> _**www.ibeem.cn/project/single/member/add          method: POST        //添加成员**_

```js
request body parameter:
                {
                    "projectID"       : 111       //项目ID
                    "userID"          : ""        //用户ID
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



