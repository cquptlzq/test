`post`  `api.baptest.cn/user/login`

| **参数**  | **必选**  | **类型**      |**描述**|
| ---|---|---|---|
|user_name    | true   |    string  |用户名(手机号或者邮箱)|
| user_pwd     | true  |    string     |用户密码（已经加密)|
| time         | true       |     int   |时间戳（用于确定接口的访问时间）|
| token         | true     |    string  |确定访问者身份|
```  
{"code":200,  
"msg":"登录成功",  
"data":{"user_id":"100",  
"user_name":"小王",  
"user_role":"游客",  
"password":"123456",    
"email":"1773852344@qq.com",  
 "phone_num":"13423442442",  
"create_time":"2020\/10\/511:54:06",  
"update_time":"2020\/10\/5 11:54:06"}  
}  
```  


