# 更新记录

最新社区版代码托管在Github上.

企业版代码托管在私有的GIT服务器上,购买企业版后可获取企业版代码以及后续更新。


> 注意
>
> master为最新开发分支. 线上使用请根据情况切换到对应版本的分支.
>

# 更新日志
> 服务端-V1.x `master`


## V1.0.1（2023/1/31）

增加：
* 增加事件上报及事件告警支持
* 增加设备运行状态属性及设备数据空值过滤处理
* 增加数据模型解绑处理

修复:
* 修复TD取值过程因大小写引起的BUG
* 修复tls转换类型BUG
* 修复默认协议调别有误的BUG

优化:
* 优化TD数据迁移工具
* 优化运行脚本日志输出
* 优化用户登录权限初始化方式

## V1.0.0（2023/1/1）

* SagooIOT 1.0 版本发布，开放 SagooIOT开 源库