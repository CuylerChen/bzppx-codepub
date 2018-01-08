# bzppx-codepub
暴走皮皮虾之代码发布系统后台

# 系统开发中,请保持关注哟!

# 一些对比


| - | 语言 | 部署 | 稳定性 | 系统要求 | 平台覆盖 | 发布速度 | 发布配置 | 邮件通知 | 封版 | 权限 | 公告
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- 
| `Jenkins` | java | 复杂 | 中 | 高 | 一般 | 很慢 | 灵活| √ | × | √ | ×
| `CodePub` | golang | 1分钟 | 高 | 低 | 广泛 | 极快 | 十分灵活 | √ | √(更细) | √

# 系统介绍

## 一. 用户功能

| - | 用户管理 | 设置管理员 | 发布代码 | 回滚代码 | 封版 | 公告管理 | 模块管理 | 节点管理
| ------ | ------ | ------ | ------ | ------ | ------ | ------ | ------ | ------ 
| `超级管理员` | √ | √ | √ | √ | √ | √ | √ | √
| `管理员` | √ | × | √ | √ | √ | √ | √ | √ | √
| `普通用户` | × | × | √ | √ | × | × | × | ×

## 二. 系统界面,先睹为快

### 登录
![login](/docs/guide_res/images/login.png)
### 添加代码模块
![login](/docs/guide_res/images/module-add.png)
