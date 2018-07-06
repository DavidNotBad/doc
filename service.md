# 服务商

| 模块       | 描述                      |
| ---------- | ------------------------- |
| 新增服务商 | tc.service.service.create |

------



| 模块     | 描述                        |
| -------- | --------------------------- |
| 获取省份 | tc.service.service.province |

| 参数    | 描述   | 备注 |
| ------- | ------ | ---- |
| area_id | 地区id |      |

------

| 模块     | 描述                        |
| -------- | --------------------------- |
| 获取城市 | tc.service.service.city |

| 参数    | 描述   | 备注 |
| ------- | ------ | ---- |
| province_id | 省份id |      |

------

| 模块     | 描述                        |
| -------- | --------------------------- |
| 获取乡镇 | tc.service.service.country |

| 参数    | 描述   | 备注 |
| ------- | ------ | ---- |
| city_id | 城市id |      |

------


| 模块     | 描述                        |
| -------- | --------------------------- |
| 新增服务商提交 | tc.service.service.store |

| 参数    | 描述   | 备注 |
| ------- | ------ | ---- |
| name | 服务商名称 |      |
| level | 等级 |      |
| type | 类型 |      |
| area | 区域 |      |
| city | 城市 |      |
| county | 乡镇 |      |
| company_name | 公司名称 |      |
| uscc | 统一社会信用代码 |      |
| legal_name | 法人名 |      |
| legal_phone | 法人电话 |      |
| legal_email | 法人email |      |
| contact_email | 联系人email |      |
| contact_name | 联系人名 |      |
| contact_phone | 联系人电话 |      |
| office_address | 办公地址 |      |
| note | 备注 |      |

------

| 模块     | 描述                        |
| -------- | --------------------------- |
| 服务商列表页 | tc.service.service.index |

| 搜索参数    | 描述   | 备注 |
| ------- | ------ | ---- |
| begin_ctime && end_ctime  | 开始时间 && 结束时间 |      |
| begin_utime && end_utime  | 修改时间 && 结束时间 |      |
| level  | 服务商等级 |      |
| type  | 服务商类型 |      |
| search  | 搜素框 |      |

------



| 模块     | 描述                        |
| -------- | --------------------------- |
| 导出 | tc.service.service.export |


> 搜索参数和index方法一样

------



| 模块     | 描述                        |
| -------- | --------------------------- |
| 编辑页面 | tc.service.service.edit |

| 参数    | 描述   | 备注 |
| ------- | ------ | ---- |
| id  |  |      |

------


| 模块     | 描述                        |
| -------- | --------------------------- |
| 编辑提交 | tc.service.service.update |

| 参数    | 描述   | 备注 |
| ------- | ------ | ---- |
| name | 服务商名称 |      |
| level | 等级 |      |
| type | 类型 |      |
| area | 区域 |      |
| city | 城市 |      |
| county | 乡镇 |      |
| company_name | 公司名称 |      |
| uscc | 统一社会信用代码 |      |
| legal_name | 法人名 |      |
| legal_phone | 法人电话 |      |
| legal_email | 法人email |      |
| contact_email | 联系人email |      |
| contact_name | 联系人名 |      |
| contact_phone | 联系人电话 |      |
| office_address | 办公地址 |      |
| note | 备注 |      |

------


| 模块     | 描述                        |
| -------- | --------------------------- |
| 服务商列表关联的商家列表 | tc.service.service.relationBusiness |

| 参数    | 描述   | 备注 |
| ------- | ------ | ---- |
| service_id | 服务商id |      |
| name |  搜索参数:商家名称 |      |

------


 



















