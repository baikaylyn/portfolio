# 作品集 · Portfolio

macOS 工具与个人实验。所有项目均为**闭源软件**，这里只放产品展示页，不含源代码。

---

## macOS 工具

### [HolderGent](https://github.com/baikaylyn/holdergent-showcase)

工作空间抽屉：把常用 App、文件夹和文件收进一个随时拉出的面板。

- 每块屏幕物理左下角各一枚 L 形角标，点击或鼠标滑入即可拉出
- 分类可绑定现有文件夹，内容实时跟随磁盘
- 面板内浏览、拖入拖出、角标缩放、开机自启
- 单文件 Objective-C，无第三方依赖

`macOS 13+` · `v1.7.0`

### [MonitorGent](https://github.com/baikaylyn/monitorgent-showcase)

菜单栏硬件监测：功率、温度、内存、电池、I/O，一眼看完。

- 菜单栏常显内存压力环 + 温度
- 整机功率曲线与 SoC 功率分解（CPU / GPU / ANE / DRAM）
- 内存四段构成环、电池健康与适配器输入、传感器温度区间
- 全部本地读取，不联网

`macOS 13+` · `v0.9.3`

### [UcGent](https://github.com/baikaylyn/ucgent-showcase)

用 Mac 的键盘鼠标直接控制 iPad，不需要通用控制。

- iPad 零安装，识别为标准蓝牙键盘 + 鼠标
- 一块 ESP32-C3 做 BLE HID 桥，四步安装向导
- 菜单栏常驻、状态灯、小灰条切换、参数可调
- 不要求同一 Apple ID，不挑系统版本

`macOS 13+` · `iPadOS` · `v1.0.0`

---

## 实验

### [NewGent](https://github.com/baikaylyn/newgent-showcase)

个人新闻聚合阅读实验：把反复报道的时事收进一个安静的阅读器。

- 事件聚类：同一事件的多篇报道合并成一条时间线
- 一句话摘要（≤42 字，抽取式）
- 分区、速览、热搜、直播、电台
- 四套主题，单文件网页版离线可读

`Web` · `Android` · `v0.3.1`

---

## 说明

- 各项目仓库仅用于产品介绍与问题反馈，**不包含源代码**。
- 新闻类项目中的内容版权归原媒体所有，仅作个人阅读聚合。
- © 2026 [baikaylyn](https://github.com/baikaylyn)
