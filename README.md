# HyperLux

兼容 HyperOS 的亮度个性化工具，基于 Root 与 LSPosed。编辑基础曲线、学习手动偏好、暗光稳定与户外高亮，支持按本机真实节点调节。GPL-3.0，官方版本开源免费。

## 4.4.4 正式版

1. 补充 Redmi K60 HyperOS 1 的亮度曲线、自动亮度状态和双光感读取兼容。
2. 修复小米12S Pro部分固件状态和日志不显示、重复弹出曲线读取提示的问题。
3. 改善控制中心节点映射与主屏亮度磁贴的启动兼容，处理部分设备私有文件权限残留导致的启动失败。
4. 完善单项功能检测与错误诊断，保留已有设置及原有兼容路线。

[累计完整更新日志](https://github.com/RongShangs/LumaCurve/blob/v4.4.4/docs/releases/4.4.4.md)

## 安装与使用

最低Android14，需要Root、LSPosed及兼容的HyperOS亮度接口。安装后启用模块，勾选系统框架 / Android系统；控制中心节点控制另需系统界面。安装或覆盖更新后重启手机，再进入APP授予权限。作用域变更可在主屏手动亮度页确认后重启系统界面，日常保存参数无需重启。其他同时控制亮度的模块请先停用。

功能按实际接口分别检测，部分平板和移植系统已有兼容案例。接口或权限暂缺不重置原设置，遇到BUG或不兼容请从日志页导出分析包反馈。

## 下载与源码

- [官网与下载](https://lc.rongshangs.top)
- [完整发布](https://github.com/RongShangs/LumaCurve/releases/tag/v4.4.4)
- [对应源码](https://github.com/RongShangs/LumaCurve/releases/download/v4.4.4/LumaCurve-4.4.4-source.zip)
- [GitHub Issues](https://github.com/RongShangs/LumaCurve/issues)

本项目与小米、红米及HyperOS官方无关联。
