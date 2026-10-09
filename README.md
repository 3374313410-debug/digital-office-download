# 解决方案/产数小微ICT工具箱

Windows 桌面办公工具，包含报价转换、Word 服务清单、收支表、询价函、方案解构、网络拓扑、设备图库及抠图等功能。

本仓库仅公开下载说明及程序包，项目源码保持私有。公开包不内置自有能力清单或集采设备表，使用者可通过软件自行上传自己的清单；导入和查询功能均保留。

## 下载 v1.0.0（公开版）

- [下载完整 Windows 64 位 ZIP](https://github.com/3374313410-debug/digital-office-download/releases/download/v1.0.0/digital-office-v1.0.0-windows-x64.zip)
- [发行版页面与文件校验](https://github.com/3374313410-debug/digital-office-download/releases/tag/v1.0.0)
- [Gitee 下载说明页面](https://gitee.com/zhong-shuhao/digital-office-download)

只需下载一个 ZIP，无需分卷。文件大小为 829,358,167 字节（约 791 MiB），解压后约占用 1.8 GB。适用于 Windows 10/11 64 位。

## 运行方法

1. 下载 `digital-office-v1.0.0-windows-x64.zip`。
2. 将整个 ZIP 解压到本机文件夹。
3. 打开解压后的 `解决方案-产数小微ICT工具箱` 文件夹，双击 `解决方案-产数小微ICT工具箱.exe`。

请保留 EXE 同目录中的 `_internal` 文件夹。本次发布包可直接解压运行；旧版 `Setup.exe` 不适用于本次发布包。

新电脑首次运行时没有预置业务清单。已有电脑上的本地清单会继续保留，替换程序不会清除用户数据。

程序来自 2026-09-28 构建的现有 dist，本次移除预置能力清单及其导入元数据，保留其余 5,311 个程序与资源文件，版本继续使用 v1.0.0。

## AI 服务配置

AI 服务需要联网，并由使用者在本机配置自己的 DeepSeek 或 MiniMax API Key。发布包不提供作者的密钥，也不包含用户配置或网页 AI 登录资料。

## 文件校验

SHA-256：

```text
2702a486b075dfbeefa44adae14a005268a88c49016ac3dc96ac9bf962a2419d
```

可在发行版页面下载 `SHA256SUMS.txt` 进行核对。
