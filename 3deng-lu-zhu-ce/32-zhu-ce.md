### 新用户注册

> _**www.ibeem.cn/user/register               method: POST  用户注册信息校验保存**_

```js
request body parameter:
                {
                     "userName"   :  "test"          //用户名
                     "password"   :  "test"          //密码
                     "email"      :  "test@163.com"  //邮箱
                     "workplace"  :  "test"          //单位
                     "position"   :  "test"          //职称
                     "mobilePhone":  "12345678901"   //手机
                     "portrait"   :  "test.jpg"      //头像
                     "name"       :  "test"          //姓名
                }
response:
     success:   {
                     "code" : 200    
                }
        fail:   {
                     "code" : 1001,
                     "messg": "test"
                }
```



