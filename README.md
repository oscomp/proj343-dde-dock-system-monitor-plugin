# projX-oscomp-dde-dock-system-monitor-plugin

### DDE 任务栏系统状态监视插件

为 DDE 桌面环境的任务栏组件编写系统状态监视插件

### 项目描述

DDE Dock 是深度桌面环境（DDE）的任务栏或 dock 栏性质的组件。为用户提供应用切换，托盘区域，快捷控制，桌面预览等功能。这些功能实质上是通过 DDE Dock 项目本身的插件化来实现的，因而开发者可以为 DDE Dock 编写各种类型的插件，使得用户可以方便的在 Dock 中浏览对应的插件并与之产生交互。

此项目期望你为 DDE Dock 编写一个系统监视插件，在插件界面上展示当前系统的内存使用情况、CPU 负载情况等信息，并在用户点击插件时，能够开启系统监视器。

### 所属赛道

2025全国大学生操作系统比赛的“OS功能挑战”赛道

### 参赛要求

- 以小组为单位参赛，最多三人一个小组，且小组成员是来自同一所高校的本科生或研究生（2023年春季学期或之后毕业的大一~大四的本科生或研究生）
- 如学生参加了多个项目，参赛学生选择一个自己参加的项目参与评奖
- 请遵循“2025全国大学生操作系统比赛”的章程和技术方案要求

### 项目导师

* github https://github.com/tsic404
* email liuheng@deepin.org

* github https://github.com/BLumia
* email wangzichong@deepin.org


### 难度

易

### 赛题分类
界面设计（Shell\GUI等）

### 特征

- 熟悉 C++ 语言。
- 了解 Qt 应用程序框架，了解 QML 的使用方式。
- 能够根据阅读代码与文档，了解相关组件的工作方式与架构。

### 文档

- Qt/QML:
  - https://doc.qt.io/qt-6/qtqml-index.html
  - https://www.qt.io/product/qt6/qml-book
- dock：
  - https://github.com/linuxdeepin/dde-dock/

### License

GPL-2.0-or-later

## 预期目标

### 注意：下面的内容是建议内容，不要求必须全部完成。选择本项目的同学也可与导师联系，提出自己的新想法，如导师认可，可加入预期目标

1. （必须）完成一个基于 v23 版本 dde-dock 的插件
2. （必须）插件以单独的仓库提供，并能够单独构建，不需要合并入 dde-dock 或 dde-shell 项目
3. （必须）在插件中能够展示当前系统的 CPU 负载和内存负载，点击插件应当能够打开控制中心应用
4. （必须）编写博客，记录开发过程的心得与体会，并将博客投递至 planet.deepin.org
5. （可选）扩展插件功能范围，支持显示网络等状态信息
6. （可选）使插件可以在不同宽度或位置的任务栏上均以响应式的形式合理的展示相应信息

## 备注

关于研发相关的讨论，可以在 [Matrix](https://wiki.deepin.org/Matrix) 平台的 deepin 开发者讨论群中公开的展开。
