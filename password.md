通过token获取email

tc.auth.password.byTokenToEmail

参数:

token



设置密码

tc.auth.password.store

参数:

token

password



## 发送重置密码邮件


| 模块                                    | 备注 |
| --------------------------------------- | ---- |
| tc.auth.password.sendResetPasswordEmail |      |

| 参数                                    | 备注 |
| --------------------------------------- | ---- |
| email | 邮箱 |


## 忘记密码重置密码


| 模块                                    | 备注 |
| --------------------------------------- | ---- |
| tc.auth.password.store |      |

| 参数                                    | 备注 |
| --------------------------------------- | ---- |
| token | 唯一的token |
| password | 新密码 |