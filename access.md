# 权限管理 - 权限管理

## 权限列表
| 模块                 | 备注 |
| -------------------- | ---- |
| tc.auth.access.index |   active=0(没有权限),active=1(拥有权限)   |

| 参数 | 描述   | 备注 |
| ---- | ------ | ---- |
| role_id   | 角色id |      |

## 编辑页面
| 模块                | 备注 |
| ------------------- | ---- |
| tc.auth.access.edit |      |


| 参数 | 描述   | 备注 |
| ---- | ------ | ---- |
| pid   | 二级标题id |      |


## 编辑提交
| 模块                  | 备注 |
| --------------------- | ---- |
| tc.auth.access.update |      |


| 参数   | 描述     | 备注                             |
| ------ | -------- | -------------------------------- |
| node_id     | 节点id   |          使用","分割id. 没有权限的节点不需要作为参数传递.                         |

## 菜单列表
| 模块                 | 备注 |
| -------------------- | ---- |
| tc.auth.access.menu |   active=0(没有权限),active=1(拥有权限)   |
| role_id   | 角色id |      |

## 菜单编辑提交
| 模块                  | 备注 |
| --------------------- | ---- |
| tc.auth.access.update |      |

| 参数 | 描述   | 备注 |
| ---- | ------ | ---- |
| node_id   | 节点id |      |
| role_id   | 角色id |      |