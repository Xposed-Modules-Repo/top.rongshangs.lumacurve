# HyperLux

兼容 HyperOS 的亮度个性化工具，基于 Root 与 LSPosed。编辑基础曲线、学习手动偏好、暗光稳定与户外高亮，支持按本机真实节点调节。GPL-3.0，官方版本开源免费。

## 4.6.0 正式版

1. 重做高亮增强设置，支持四点拖动目标曲线、恢复默认及最高亮度限制。
2. 新增短时激发测试，显示剩余时间、当前亮度和测试最高亮度。
3. 完善应用临时亮度隔离：正常小窗保留临时亮度，最小浮窗或贴边挂起后交回系统。
4. 修复应用从小窗最大化后未恢复独立亮度的问题。
5. 精简多个设置页面的冗余说明，优化布局、状态展示及深色模式。

[4.6.0更新日志](https://github.com/RongShangs/LumaCurve/blob/v4.6.0/docs/releases/4.6.0.md)

## 安装与使用

最低Android14，需要Root、LSPosed及兼容的HyperOS亮度接口。安装后启用模块，勾选系统框架 / Android系统；控制中心节点控制另需系统界面。安装或覆盖更新后重启手机，再进入APP授予权限。作用域变更可在主屏手动亮度页确认后重启系统界面，日常保存参数无需重启。其他同时控制亮度的模块请先停用。

功能按实际接口分别检测，部分平板和移植系统已有兼容案例。接口或权限暂缺不重置原设置，遇到BUG或不兼容请从日志页导出分析包反馈。

## 下载与源码

- [官网与下载](https://lc.rongshangs.top)
- [完整发布](https://github.com/RongShangs/LumaCurve/releases/tag/v4.6.0)
- [对应源码](https://github.com/RongShangs/LumaCurve/releases/download/v4.6.0/LumaCurve-4.6.0-source.zip)
- [GitHub Issues](https://github.com/RongShangs/LumaCurve/issues)

本项目与小米、红米及HyperOS官方无关联。
