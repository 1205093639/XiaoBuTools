# MotoGifRecorder - 选区 GIF 录制工具

Snipaste 式屏幕选区录制：按 `F7` 框选录制区域 → 自动开始录制 → 双击停止 → 自动合成 GIF 并复制路径到剪贴板，方便快速分享动效/操作演示。

> **下载安装包**：前往 [Releases 页面](https://github.com/1205093639/XiaoBuTools/releases) 选择版本下载。

## 版本历史

| 版本 | 文件 | 更新说明 |
|---|---|---|
| v1.1.0 | [下载](https://github.com/1205093639/XiaoBuTools/releases/download/motogifrecorder-v1.1.0/MotoGifRecorder.exe) | 可调帧率/画质设置；托盘菜单加 B站主页 与 打赏支持（微信/支付宝） |
| v1.0.1 | [下载](https://github.com/1205093639/XiaoBuTools/releases/download/motogifrecorder-v1.0.1/MotoGifRecorder.exe) | 生成 GIF 时红框显示实时进度（百分比+动画），不再像卡死 |
| v1.0.0 | [下载](https://github.com/1205093639/XiaoBuTools/releases/download/motogifrecorder-v1.0.0/MotoGifRecorder.exe) | 首个版本：自带 .NET 运行时 + 内嵌 ffmpeg，单文件免安装，双击即用 |

## 使用步骤

1. 从 [Releases](https://github.com/1205093639/XiaoBuTools/releases) 下载 exe，双击启动（无主窗口，托盘常驻）
2. 按 `F7`（或点托盘图标），鼠标框选要录制的区域
3. 框选后自动开始录制，红框左上角显示 REC 状态
4. 双击选区停止录制，自动合成 GIF
5. 合成完成后弹出提示，保存路径已复制到剪贴板，直接粘贴发送即可

## 说明

- 单文件自带运行时与 ffmpeg，**任何 Windows 10/11 电脑直接可用**，无需安装任何东西
- 托盘右键菜单：设置默认保存目录 / 自动保存开关 / 退出
- 源码与问题反馈：[MotoGifRecorder 源码仓库](https://github.com/1205093639/MotoGifRecorder)
