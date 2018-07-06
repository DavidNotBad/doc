# 商家模块

## 新增商家页面


| 模块       | 备注                      |
| ---------- | ------------------------- |
| tc.business.business.create |  |

## 获取省份

| 模块     | 备注                        |
| -------- | --------------------------- |
| tc.business.business.province |  |

| 参数    | 描述   | 备注 |
| ------- | ------ | ---- |
| area_id | 地区id |      |

## 获取城市

| 模块     | 备注                        |
| -------- | --------------------------- |
| tc.business.business.city |  |

| 参数    | 描述   | 备注 |
| ------- | ------ | ---- |
| province_id | 省份id |      |

## 获取乡镇

| 模块     | 备注                        |
| -------- | --------------------------- |
| tc.business.business.country |  |

| 参数    | 描述   | 备注 |
| ------- | ------ | ---- |
| city_id | 城市id |      |

## 新增商家提交

| 模块     | 备注                        |
| -------- | --------------------------- |
| tc.business.business.store |  |

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

## 获取所有的服务商列表
| 模块     | 备注                        |
| -------- | --------------------------- |
| tc.business.business.service | 一般用于新增页面 |


| 参数    | 描述   | 备注 |
| ------- | ------ | ---- |
| name | 服务商名称 |  搜索参数    |

## 关联服务商列表
| 模块     | 备注                        |
| -------- | --------------------------- |
| tc.business.business.relationService | 列表页的ajax请求 |


| 参数    | 描述   | 备注 |
| ------- | ------ | ---- |
| business_id | 商家id |     |
| name | 服务商名称 | 获取服务商子页面的搜索    |

## 商家列表
| 模块     | 备注                        |
| -------- | --------------------------- |
| tc.business.business.index |  |


| 搜索参数    | 描述   | 备注 |
| ------- | ------ | ---- |
| begin_ctime && end_ctime  | 开始时间 && 结束时间 |      |
| begin_utime && end_utime  | 修改时间 && 结束时间 |      |
| level  | 商家等级 |      |
| type  |商家类型 |      |
| search  | 搜素框 |      |

## 导出
| 模块     | 备注                        |
| -------- | --------------------------- |
| tc.business.business.export |  |


| 搜索参数    | 描述   | 备注 |
| ------- | ------ | ---- |
| begin_ctime && end_ctime  | 开始时间 && 结束时间 |      |
| begin_utime && end_utime  | 修改时间 && 结束时间 |      |
| level  | 商家等级 |      |
| type  |商家类型 |      |
| search  | 搜素框 |      |

## 编辑页面
| 模块     | 备注                        |
| -------- | --------------------------- |
| tc.business.business.edit |  |


| 参数    | 描述   | 备注 |
| ------- | ------ | ---- |
| id | 商家id |     |


## 编辑提交
| 模块     | 备注                        |
| -------- | --------------------------- |
| tc.business.business.update |  |


| 参数    | 描述   | 备注 |
| ------- | ------ | ---- |
| id | 商家id |     |
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

