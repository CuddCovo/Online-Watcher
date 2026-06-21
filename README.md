# Online Watcher

A lightweight Minecraft Fabric client-side mod that monitors specific players' online status on multiplayer servers, with customizable HUD display.

## Features

- **Player Monitoring**: Add player names to a watchlist and get notified when they're online
- **HUD Overlay**: Shows monitored players' online status in the bottom-right corner of the screen
- **Customizable Name Color**: Choose any color for the HUD player name display
- **HUD Overlay Mode**: Three display modes — None (plain text), Background (debug-style dark background), Shadow (text shadow)
- **Cross-Dimension Detection**: Detects players regardless of which dimension they're in
- **Toggle On/Off**: Enable or disable the mod at any time via the config screen
- **Mod Menu Integration**: Easy-to-use configuration through Mod Menu

## Requirements

- Minecraft 1.21.11
- Fabric Loader >= 0.15.11
- Fabric API
- Mod Menu
- Cloth Config API

## Usage

1. Install the mod along with the required dependencies
2. Open Mod Menu from the title screen or pause menu
3. Click the config button for "Online Watcher"
4. In the "General" tab, you can:
   - Toggle the mod on/off
   - Choose the name display color via color picker
   - Select HUD overlay mode (None / Background / Shadow)
5. In the "Watchlist" tab, add player names to monitor
6. When a monitored player joins the server, their name will appear on the HUD

## How It Works

The mod reads player names directly from the network player list (the same data shown when pressing Tab), matching against the original Mojang account names. Server-added prefixes, suffixes, or rank tags will not affect detection.

## License

This project is licensed under the [Creative Commons Attribution-NoDerivatives 4.0 International License](https://creativecommons.org/licenses/by-nd/4.0/). See the [LICENSE](LICENSE) file for details.

---

## 中文说明

**Online Watcher** 是一款轻量级 Minecraft Fabric 客户端模组，用于监控多人服务器中指定玩家的在线状态，支持自定义 HUD 显示效果。

### 功能

- **玩家监控**：将玩家名添加到监控列表，当他们上线时收到通知
- **HUD 显示**：在屏幕右下角显示被监控玩家的在线状态
- **自定义名字颜色**：通过颜色选择器自由选择 HUD 上玩家名字的显示颜色
- **HUD 叠加层模式**：三种显示模式 — 无（纯文字）、背景（调试风格深色背景）、阴影（文字阴影）
- **跨维度检测**：无论目标玩家在哪个维度，都能准确检测
- **开关控制**：随时通过配置界面启用或禁用模组
- **Mod Menu 集成**：通过 Mod Menu 进行简单直观的配置

### 前置依赖

- Minecraft 1.21.11
- Fabric Loader >= 0.15.11
- Fabric API
- Mod Menu
- Cloth Config API

### 使用方法

1. 安装本模组及所有前置依赖
2. 在主菜单或暂停菜单中打开 Mod Menu
3. 点击 "Online Watcher" 的配置按钮
4. 在「通用设置」标签页中，可以：
   - 开关模组
   - 通过颜色选择器选择名字显示颜色
   - 选择 HUD 叠加层模式（无 / 背景 / 阴影）
5. 在「监控名单」标签页中，添加要关注的玩家名
6. 当被监控的玩家加入服务器时，他们的名字将显示在 HUD 上

### 工作原理

模组直接从网络玩家列表（按 Tab 键显示的相同数据）读取玩家名，匹配的是 Mojang 账户原始名称。服务器添加的前缀、后缀或称号标签不会影响检测结果。

### 许可证

本项目基于 [Creative Commons 署名-禁止演绎 4.0 国际许可证](https://creativecommons.org/licenses/by-nd/4.0/deed.zh-hans) 开源，详见 [LICENSE](LICENSE) 文件。
