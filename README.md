# HyperLux

兼容 HyperOS 的亮度个性化工具，基于 Root 与 LSPosed。可编辑基础曲线、记住手动偏好、调整暗光稳定与户外高亮，保留系统过渡和必要保护。官方版本开源免费，GPL-3.0。

## 4.2.0 正式版

1. 改善户外节点增强的恢复，减少短暂写入失败后无法继续增强的情况。
2. 修复部分传统曲线设备将绿色记忆曲线保存为基础曲线时提示节点无效的问题。
3. 完善受限 Root 环境适配，独立检查各项权限，避免影响其他仍可使用的功能。
4. 加强异常恢复和系统更新后的状态判断，保留已有兼容路线与用户设置。
5. 设置新增实时搜索；分析包导出后可直接打开系统分享，反馈更方便。
6. 完善更新提醒、兼容详情与深色显示，优化日常操作体验。

[完整更新日志](https://github.com/RongShangs/LumaCurve/blob/v4.2.0/docs/releases/4.2.0.md)

## 安装与使用

需要 Root、LSPosed 和兼容的 HyperOS 亮度接口，最低 Android 14。安装 APK 后启用模块，作用域选择“系统框架 / Android 系统”，重启并在 APP 内授予所需权限。安装或覆盖更新系统钩子仍需重启，日常参数修改保存并应用即可。请先停用其他同时控制亮度的模块。

功能按实际设备接口逐项判断，已有部分移植系统适配案例；不保证所有机型或移植包支持全部功能。权限或接口暂缺时保留已有设置，查看日志中的运行与兼容详情。遇到问题请从日志页导出分析包反馈。

## 下载与源码

- [官网与下载](https://lc.rongshangs.top)
- [源码与完整发布](https://github.com/RongShangs/LumaCurve/releases/tag/v4.2.0)
- [对应源码 ZIP](https://github.com/RongShangs/LumaCurve/releases/download/v4.2.0/LumaCurve-4.2.0-source.zip)
- [问题反馈](https://github.com/RongShangs/LumaCurve/issues)
- [GPL-3.0](https://github.com/RongShangs/LumaCurve/blob/v4.2.0/LICENSE)

## 界面示例

以下为历史版本示意，具体界面以当前安装版本为准。

<img src="https://raw.githubusercontent.com/RongShangs/LumaCurve/v4.2.0/docs/screenshots/3.0.0/status.jpg" width="260" alt="状态页示意">
<img src="https://raw.githubusercontent.com/RongShangs/LumaCurve/v4.2.0/docs/screenshots/3.0.0/scene-controls.jpg" width="260" alt="场景设置示意">

作者：戎Shang（RongShangs）。个人开源项目，与小米、红米及 HyperOS 官方无关联。
