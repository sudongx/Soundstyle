# AudioMod - Magisk 音效修改模块

![支持版本](https://img.shields.io/badge/Android-13%2B-blue.svg)
![Magisk 版本](https://img.shields.io/badge/Magisk-23.0%2B-green.svg)
![License](https://img.shields.io/github/license/yourusername/your-repo-name.svg)

## 介绍

AudioMod 是一款专为 Magisk 设计的音效修改模块，可让你轻松自定义安卓设备的系统音效。通过替换系统默认的提示音、通知音和其他音效，为你的设备带来全新的听觉体验。

## 功能特性

- 自定义点按提示音
- 替换截图提示音
- 修改通知声音
- 自定义充电提示音
- 支持多种音效格式
- 一键恢复默认设置

## 安装要求

- 已root的安卓设备
- Magisk 23.0 或更高版本
- Android 13 或更高版本

## 安装步骤

1. 下载最新版本的 AudioMod.zip 文件
2. 打开 Magisk Manager
3. 点击"模块"选项卡
4. 点击右上角的"+"按钮
5. 选择下载的 AudioMod.zip 文件
6. 等待安装完成
7. 重启设备

## 使用方法

1. 安装并重启设备后，模块会自动应用默认音效
2. 若要自定义音效，将你喜欢的音频文件放入以下目录：
   - `/sdcard/AudioMod/click_sounds/` - 点按提示音
   - `/sdcard/AudioMod/screenshot_sounds/` - 截图提示音
   - `/sdcard/AudioMod/notification_sounds/` - 通知声音
   - `/sdcard/AudioMod/charging_sounds/` - 充电提示音
3. 将文件命名为相应的音效类型（例如：click_sound.mp3）
4. 在 Magisk Manager 中重启模块或重启设备使更改生效

## 卸载方法

1. 打开 Magisk Manager
2. 点击"模块"选项卡
3. 找到 AudioMod 模块并点击右侧的垃圾桶图标
4. 重启设备

## 注意事项

- 本模块修改系统文件，请确保你了解其中的风险
- 如果遇到任何问题，可以在模块设置中选择恢复默认设置
- 不保证支持所有设备，使用前请备份重要数据
- 音频文件格式建议使用 MP3 或 WAV，其他格式可能不兼容

## 贡献

如果你有任何建议或发现了 bug，请在 GitHub 上提交 issue 或 pull request。

## 许可证

本项目采用 [MIT 许可证](LICENSE)。
