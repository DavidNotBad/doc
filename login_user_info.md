## 登录成功后用户信息的获取

```php
# 获取方式
require_once ROOT_FW_PATH . '/application/source/tc/common/Common.php';
class Test
{
    use Common;
    
    /**
     * 获取当前登录的用户的id
     * @return int
     */
    public function test_get_user_id()
    {
        $userId = $this->userId();
    }
    
    /**
     * 获取当前登录的用户的关联表id
     * @return int
     */
    public function test_get_relation_user_id()
    {
        $relationUserId = $this->relationUserId();
    }
    
    /**
     * 登录后的用户信息
     */
    public function test_get_user_info()
    {
        $userInfo = $this->authUser();
    }
}

```

### 获取用户信息返回结果示例

| 字段名      | 值示例            | 备注                                                         |
| ----------- | ----------------- | ------------------------------------------------------------ |
| id          | 30                | 当前用户的id                                                 |
| status      | 1                 | 状态：0禁用，1正常                                           |
| login_time  | 1532312870        | 最近一次登录时间                                             |
| login_ip    | 127.0.0.1         | 最近一次登录ip                                               |
| type        | 1                 | 用户类型(0:超级管理员,1:资方,2:服务商,3:商家,4:业务员,5:平台操作员,6:资方操作员,7:服务商操作员,8:商家操作员) |
| phone       | 18820777741       | 电话号码                                                     |
| name        | 张三              | 用户名                                                       |
| email       | 1304475451@qq.com | 邮箱                                                         |
| relation_id | 50                | 关联表id                                                     |



## relation_id和type关联对照表

| type | 数据表           | 备注         |
| ---- | ---------------- | ------------ |
| 1    | management       | 资方         |
| 2    | service_provider | 服务商       |
| 3    | business         | 商家         |
| 4    | salesman         | 业务员       |
| 5    | user             | 平台操作员   |
| 6    | user             | 资方操作员   |
| 7    | user             | 服务商操作员 |
| 8    | user             | 商家操作员   |

## 用户信息模拟

```mysql
INSERT INTO `tc`.`tc_user` (
	`id`,
	`password`,
	`status`,
	`login_time`,
	`login_ip`,
	`type`,
	`phone`,
	`name`,
	`email`,
	`relation_id`,
	`token`
)
VALUES
	(
		'30',
		'e10adc3949ba59abbe56e057f20f883e',
		'1',
		'0',
		'0',
		'2',
		'18854121111',
		NULL,
		'1542142111@qq.com',
		'40',
		NULL
	);
```

