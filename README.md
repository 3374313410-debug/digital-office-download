# 解决方案/产数小微ICT工具箱

Windows 桌面办公工具，提供报价转换、Word 服务清单、收支表、询价函、方案解构、网络拓扑、设备图库、抠图以及容量、带宽和镜头选型工具。

本仓库用于公开下载说明及程序包，源码保持私有。

## 下载最新版 v1.1.0

- **[下载安装器 Setup.exe（约 62 KB，推荐）](https://github.com/3374313410-debug/digital-office-download/releases/download/v1.1.0/Setup.exe)**
- [完整 Windows 64 位 ZIP（约 867 MiB，离线备用）](https://github.com/3374313410-debug/digital-office-download/releases/download/v1.1.0/digital-office-v1.1.0-windows-x64.zip)
- [新版发行说明与文件校验](https://github.com/3374313410-debug/digital-office-download/releases/tag/v1.1.0)
- [历史版本](https://github.com/3374313410-debug/digital-office-download/releases)

发布于 **2026-10-30**。客户只需下载一个 `Setup.exe`，大小为 **62,976 字节（约 62 KB）**。运行后自动联网下载约 867 MiB 的完整程序，并校验文件后安装。安装后的程序约占用 1.81 GiB，建议预留约 4 GiB 磁盘空间。适用于 Windows 10/11 64 位，安装器要求 .NET Framework 4.8。

## 安装方法

1. 下载并运行本次发布的 `Setup.exe`。
2. 输入安装目录，或点击“浏览…”选择位置，例如 D 盘。请选择本地可写的空文件夹，或本安装器之前的安装目录。
3. 点击“开始安装”。安装器自动下载、校验和安装，可创建桌面快捷方式。

安装期间需要能访问 GitHub，下载支持续传和失败后重试。默认目录为 `%LOCALAPPDATA%\Programs\解决方案-产数小微ICT工具箱`。同一 Windows 账户下的本地配置和已导入清单继续保留。

需要离线使用时，可选择下载完整 ZIP，解压后运行其中的 `解决方案-产数小微ICT工具箱.exe`。请保留 EXE 同目录中的 `_internal` 和 `LensSelectTool` 文件夹。两种下载方式任选一种即可。

## 最新变化

- 增加视频容量、带宽、摄像机焦距及海康镜头选型等工具。
- 优化网络拓扑工具栏、文本框、自动对齐、区域框和 Visio 导出。
- Word 服务清单增加通用提示词版本，保留原版提示词。

## AI 服务和清单

AI 服务需要联网，请在软件中配置自己的 OpenAI 兼容 API 地址、API Key 和模型。公开包不提供作者密钥，不包含用户配置或浏览器登录资料。

公开版不预置自有能力清单或集采设备业务表，保留查询、导入及检索功能，使用者可自行导入清单。办公模板、设备图标、浏览器及抠图模型保留。

## 文件校验

```text
add02585c7233edea121d8d3ca490bac852ec4bb8fd3906265cf4662a77d4845  Setup.exe
9cd0e6f005e5065b4b81e8b16c4a4ed38a470e3496e7b0961e5df53ccc3809f7  digital-office-v1.1.0-windows-x64.zip
```

可在[发行版页面](https://github.com/3374313410-debug/digital-office-download/releases/tag/v1.1.0)下载 `SHA256SUMS.txt` 进行核对。
