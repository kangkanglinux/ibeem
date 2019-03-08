### 忘记密码

> _**www.ibeem.cn/user/register        method: POST        通过邮箱找回密码**_

```js
 request body parameter:
                {
                     "username"   :  "test"          //用户名
                     "email"      :  "test@163.com"  //邮箱
                }
response:
     success:   {
                     "code" : 200    //系统将自动修改密码并将密码发送至邮箱
                }
        fail:   {
                     "code" : 1003,
                     "messg": "用户名不存在"
                }
                或者返回
                {
                     "code" : 1003,
                     "messg": "邮箱不匹配"
                }
                或者返回

                {
                     "code" : 1005,
                     "messg": "系统错误"
                }
```



