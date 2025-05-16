# GoogleAudio - Magisk 音效修改模块

![支持版本](https://img.shields.io/badge/Android-13%2B-blue.svg)
![Magisk 版本](https://img.shields.io/badge/Magisk-23.0%2B-green.svg)
![License](https://img.shields.io/github/license/yourusername/your-repo-name.svg)

## 介绍

GoogleAudio 是一款专为 Magisk 管理器设计的音效修改模块，可为安卓设备使用AOSP上的系统音效。通过替换系统默认的提示音、通知音和其他音效，为你提供接近原生的体验。

## 功能特性

- 自定义点按提示音
- 替换截图提示音
- 修改通知声音
- 充电提示音

## 安装要求

- 已root的安卓设备
- Magisk 23.0 或更高版本
- KSU请自测
- Android 13 或更高版本

## 安装步骤

1. 下载最新版本的 GoogleAudio 文件
2. 打开 Magisk Manager
3. 点击"模块"选项卡
4. 点击上方的"安装"按钮
5. 选择下载的 GoogleAudio.zip 文件
6. 等待安装完成
7. 重启设备

## 使用方法

1. 安装并重启设备后，模块会自动应用默认音效
2. 若要自定义音效，将你喜欢的音频文件放入以下目录：
   - `/sdcard/GoogleAudio/click_sounds/` - 点按提示音
   - `/sdcard/GoogleAudio/screenshot_sounds/` - 截图提示音
   - `/sdcard/GoogleAudio/notification_sounds/` - 通知声音
   - `/sdcard/GoogleAudio/charging_sounds/` - 充电提示音
3. 将文件命名为相应的音效类型（例如：click_sound.mp3）
4. 在 Magisk Manager 中重启模块或重启设备使更改生效

## 卸载方法

1. 打开 Magisk Manager
2. 点击"模块"选项卡
3. 找到 GoogleAudio 模块并点击右侧的垃圾桶图标
4. 重启设备

## 注意事项

- 本模块修改系统文件，请确保你了解其中的风险
- 如果遇到任何问题，可以卸载模块恢复默认
- 不保证支持所有设备，使用前请做好救砖
- 音频文件格式建议使用 MP3 或 WAV，其他格式可能不兼容

## 贡献

如果你有任何建议或发现了 bug，请在 GitHub 上提交 issue 或 pull request。

## 许可证

本项目采用 [MIT 许可证](LICENSE)。
