# HyperLux

兼容 HyperOS 的亮度个性化工具，基于 Root 与 LSPosed。可编辑基础曲线、记住手动偏好、控制暗光与户外表现，也可用控制中心按真实节点调节。官方版本开源免费，GPL-3.0。

## 4.3.1 正式版

1. 新增控制中心节点控制：亮度条可按设备真实节点调节，支持完整控制、分区增强和自定义增强上限。
2. 新增深色模式独立亮度曲线，可分别调整深浅色模式的亮度。
3. 完善部分平板亮度曲线与控制中心映射兼容。
4. 修复部分设备熄屏前亮度反复变亮、变暗的问题。
5. 新增“恢复系统默认”，方便撤销亮度定制。
6. 优化控制中心操作示意、二级页面沉浸及关于页按钮对齐。
7. 深浅色模式新增手动记忆处理选择，可清除、共用或各自独立学习。
8. 手动记忆按当前主题展示，支持分别保存为基础曲线和清除记忆。
9. 基础曲线最右端节点支持向下调整，深色模式同样适用。
10. 改善节点调节时的亮度显示，修复部分设备状态页一直显示 0 的问题。

[累计完整更新日志](https://github.com/RongShangs/LumaCurve/blob/v4.3.1/docs/releases/4.3.1.md)

## 安装与使用

需要Root、LSPosed和兼容的HyperOS亮度接口，最低Android14。安装后启用模块，作用域选择“系统框架 / Android 系统”；控制中心节点控制另需“系统界面”。安装或覆盖更新后重启，再打开APP授予所需权限，日常保存参数无需重启。其他同时控制亮度的模块请先停用。

功能按实际设备接口分别检测，部分平板及移植系统已有兼容案例，不保证每台设备支持全部功能。接口暂缺不重置保存设置。遇到BUG或不兼容请从日志页导出分析包反馈。

## 下载与源码

- [官网与下载](https://lc.rongshangs.top)
- [完整发布](https://github.com/RongShangs/LumaCurve/releases/tag/v4.3.1)
- [对应源码](https://github.com/RongShangs/LumaCurve/releases/download/v4.3.1/LumaCurve-4.3.1-source.zip)
- [GitHub Issues](https://github.com/RongShangs/LumaCurve/issues)

本项目与小米、红米和HyperOS官方无关联，GPL-3.0开源。
