# Palworld Banlist

[English](README.md)
这是一个简单的 banlist，旨在提供官方 banlist 的替代选项。

**您可以通过提交您封禁的玩家名单及其封禁原因来为这个仓库做出贡献。**

## 使用指南

### 方法一：直接放入游戏目录（不推荐）

下载 `banlist.txt` 文件并将其放入 `/Pal/Saved/SaveGames` 目录下。

### 方法二：通过配置文件加载

打开 `PalWorldSettings.ini` 配置文件，并找到以下条目：

```ini
BanListURL="https://api.palworldgame.com/api/banlist.txt"
```

将其修改为：

```ini
BanListURL="https://raw.githubusercontent.com/qinastar/palworld-banList/main/banlist.txt"
```

## JSON

提供了一个简单的 JSON 文件，可能适用于未来的某些功能。

同时，我们还添加了一个 HTML 页面，您可以在任何地方引用和集成它。