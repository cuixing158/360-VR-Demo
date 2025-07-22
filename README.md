# 全景VR Demo

欢迎体验全景360度VR Demo！本应用支持多平台（Windows、Linux、macOS、Android、iOS），为dual-Fisheye图像、视频拼接、预览、交互等场景提供高效解决方案。当前提供的 `360Stitcher.exe` 仅为 Windows 演示版，欢迎在其他平台联系我们获取更多信息。

## 主要功能亮点

- 支持dual-Fisheye 类型全景照片和视频实时拼接、预览与交互
- 实时连接 WiFi/RTSP 全景相机，360°预览与交互
- 鼠标旋转、滚轮缩放、键盘快捷键切换多种视角模式
- 照片动画师：自动生成不同视角的视频动画并导出
- 陀螺仪实时防抖算法处理，提升观看体验
- 基础依赖库已内置，无需额外安装

## 快速开始

> **Windows 用户**：直接拖动相关文件到 `360Stitcher.exe` 即可体验全部功能。  
> **命令行帮助**：`360Stitcher.exe -h` 查看详细参数说明。

## 操作指南

**鼠标操作：**

- 左键拖动：平移视角
- 滚轮：缩放视角

**键盘操作：**

- A/D：左右移动视角
- W/S：上下移动视角
- F1/F2/F3：切换照片动画师模式
- P：导出动画师视频

*照片动画师*可自动生成不同视角的视频动画，形成流畅的全景播放效果。

### WiFi/RTSP 全景相机实时预览

1. 连接相机至 WiFi，默认流地址：`rtsp://192.168.1.254:554/xxx.mov`
2. 双击 `360Stitcher.exe` 实时预览拼接效果

### 双鱼眼照片预览

拖动 `dualFisheye.jpg` 到 `360Stitcher.exe`，或命令行：

```bash
./360Stitcher.exe dualFisheye.jpg
```

### 双鱼眼全景视频拼接预览

拖动双鱼眼视频到 `360Stitcher.exe`，或命令行：

```bash
./360Stitcher.exe VID_20241019_143754_00_037.mp4
```

如视频包含陀螺仪数据：

```bash
./360Stitcher.exe VID_20241019_143754_00_037.mp4 ./gyroData/6DOF_VID_20241019_143754_00_037.csv
```

---

## 多平台支持与商业合作

本应用已支持 Windows、Linux、macOS、Android、iOS 等主流平台。  
如对全景拼接算法、定制开发或商业合作感兴趣，欢迎随时联系：

**邮箱：<cuixingxing150@gmail.com>**

让我们一起探索全景视觉的无限可能！
