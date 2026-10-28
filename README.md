# HyperLux

兼容 HyperOS 的亮度个性化工具，基于 Root 与 LSPosed。可编辑基础曲线、记住手动偏好、控制暗光与户外表现，并可用控制中心按真实节点调节。官方版本开源免费，GPL-3.0。

## 4.3.0 正式版

1. 新增控制中心节点控制：亮度条可按设备真实节点调节，支持完整控制、分区增强和自定义增强上限。
2. 新增深色模式独立亮度曲线，可分别调整深浅色模式的亮度。
3. 完善部分平板亮度曲线与控制中心映射兼容。
4. 修复部分设备熄屏前亮度反复变亮、变暗的问题。
5. 新增“恢复系统默认”，方便撤销亮度定制。
6. 优化控制中心操作示意、二级页面沉浸及关于页按钮对齐。

[完整更新日志](https://github.com/RongShangs/LumaCurve/blob/v4.3.0/docs/releases/4.3.0.md)

## 安装与使用

需要Root、LSPosed和兼容的HyperOS亮度接口，最低Android 14。安装APK后启用模块，作用域选择“系统框架 / Android 系统”；使用控制中心节点控制还需勾选“系统界面”。安装或覆盖更新后重启，再打开APP授予所需权限，日常修改保存应用即可。请先停用其他同时控制亮度的模块。

功能按实际设备接口逐项判断，已存在部分平板和移植系统兼容案例，不保证所有设备支持全部功能。节点写入和系统注入分别自检；权限或接口暂缺不重置既有设置。遇到BUG或不兼容，请从日志页导出分析包反馈。

## 下载与源码

- [官网与下载](https://lc.rongshangs.top)
- [源码与完整发布](https://github.com/RongShangs/LumaCurve/releases/tag/v4.3.0)
- [对应源码ZIP](https://github.com/RongShangs/LumaCurve/releases/download/v4.3.0/LumaCurve-4.3.0-source.zip)
- [GitHub Issues](https://github.com/RongShangs/LumaCurve/issues)

本项目与小米、红米及HyperOS官方无关联。GPL-3.0开源协议。
