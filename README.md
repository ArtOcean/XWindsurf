# XWindsurf VIP Free Tool

## 简介
XWindsurf VIP Free Tool 是一款批量注册与管理 Windsurf 账号的桌面应用。支持自动注册 PRO 账号、自动填写支付表单、读取与刷新 Credits、切换账号、重置机器码等功能，方便批量运维与测试。

## 功能亮点
- 自动注册：
  - 可批量生成随机邮箱、密码，并完成 Windsurf 注册流程
  - 支持 FREE/PRO 两种模式，PRO 模式可触发支付表单自动填写
- 支付自动化：
  - 内置 BIN 配置，可自动生成卡号、地址信息并填写 Stripe 表单
  - 支持手动／自动切换，便于调试
- 账号管理：
  - 图形化界面展示所有账号
  - 支持 Credits 刷新、试用信息查看、切号操作
  - 支持数据库或 JSON 文件两种存储模式
- 机器码与重置：
  - 可读取 Windsurf 的机器码信息
  - 支持重置 storage.serviceMachineId 等关键字段
- 日志与诊断：
  - 集成日志面板
  - 附带多种诊断脚本，便于定位问题
