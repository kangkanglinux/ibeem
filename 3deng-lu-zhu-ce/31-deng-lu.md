### **用户登录**

> _**www.ibeem.cn/user/login     method: POST      用户登录验证**_

```js
 request body parameter: 
                  {
                      "username": "test" //用户名
                      "password": "test" //密码      
                  }

 response:
       success:   {
                      "status": 200
                      "user"  : user //用户信息       
                  }
       fail:      {
                      "status": -1
                      "messg" :  2   //用户名和密码校验失败   1 //服务器异常
                  }
```



