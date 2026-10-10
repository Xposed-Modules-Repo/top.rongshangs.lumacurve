# HyperLux

适配 HyperOS 4 的亮度自定义工具。基于 Root 与 LSPosed，在系统亮度链路内调整曲线、手动偏好记忆及现有场景控制，保留系统过渡动画与必要保护。

A brightness customization module for HyperOS 4, powered by Root and LSPosed. Customize the base brightness curve, remember manual preferences, and configure existing system scenes while retaining system transitions and protection.

## 功能 / Features

- 可编辑基础曲线、命名预设与手动偏好记忆。
- 状态页展示主辅光感、当前场景、生效曲线、输出保护及实际屏幕亮度。
- 九类现有场景支持参与方式、附加进入条件及进入/退出确认。
- 可选暗光稳定、暗光锁定、户外增强与显示层温控调整。
- 主屏手动亮度磁贴、平滑过渡与变化确认。
- 更新支持忽略版本、官网与 GitHub 下载；日志页可导出故障分析包。

## 安装 / Installation

需要 **HyperOS 4、Root、LSPosed**，最低 Android 14。安装 APK，在 LSPosed 启用 HyperLux，作用域选择 **系统框架 / Android 系统（android）**，重启后进入 APP 授予 Root。后续修改曲线及参数无需重启；更新模块后重启加载新版钩子。旧亮度模块请先停用或卸载，避免同时控制。

Requires **HyperOS 4, Root and LSPosed**, with Android 14 or newer. Install the APK, enable HyperLux for **System Framework / Android System (android)** in LSPosed, reboot, and grant Root to the app. Reboot after module updates; ordinary curve and parameter edits do not require a reboot. Disable or uninstall other brightness modules first.

## 已知问题 / Known issues

K90PM / K80PM 偶发解锁卡死的根因仍在排查，尚不能保证 3.0.0 已解决。主机回归与固件接口核对不等于完成所有机型实测。发生问题请在恢复使用后尽快导出分析包，并附机型、系统版本、模块版本及故障时间；分析包可能包含设备信息，建议私下提供给作者。

Intermittent wake/unlock freezes reported on K90PM / K80PM remain under investigation. Version 3.0.0 is not a confirmed fix. Host tests and firmware interface checks do not establish compatibility with every device.

## 源码、反馈与许可 / Source, support and license

本仓库用于 LSPosed 模块分发。完整源码继续在原仓库维护；GPL-3.0，官方版本永久免费。

This repository distributes the LSPosed module. Full corresponding source is maintained in the original project under GPL-3.0.

- [官网与下载 / Website](https://lc.rongshangs.top)
- [完整源码 / Source code](https://github.com/RongShangs/LumaCurve)
- [3.0.0 对应源码 ZIP / Corresponding source](https://github.com/RongShangs/LumaCurve/releases/download/v3.0.0/LumaCurve-3.0.0-source.zip)
- [更新日志 / Changelog](https://github.com/RongShangs/LumaCurve/blob/v3.0.0/docs/releases/3.0.0.md)
- [问题反馈 / Issues](https://github.com/RongShangs/LumaCurve/issues)
- [GPL-3.0](https://github.com/RongShangs/LumaCurve/blob/v3.0.0/LICENSE)

作者 / Author：戎Shang（RongShangs）。个人开源项目，与小米、红米及 HyperOS 官方无关联。
