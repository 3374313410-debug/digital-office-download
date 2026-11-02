# 解决方案/产数小微ICT工具箱 v1.2.0

推荐只下载 [Setup.exe](https://github.com/3374313410-debug/digital-office-download/releases/download/v1.2.0/Setup.exe)，大小为 72,704 字节（71.0 KiB）。

运行 Setup 可输入或浏览选择安装目录，支持 Windows 10/11 64 位及 .NET Framework 4.8。首次安装本版本需要联网下载约 866 MiB 完整资源，安装后程序资源约 1.81 GiB。需要离线包时下载完整 ZIP。

安装后的程序每天启动后在后台检查更新，距上次成功检查不足 24 小时时跳过；随时可用“帮助 → 检查更新”。有新版时显示说明，由用户确认后才安装。v1.1.0 用户需先手动安装一次 v1.2.0，才能收到后续版本提示。

更新保留当前安装目录，安装器中仍可修改。用户配置和已导入清单保存在 Windows 用户目录。业务任务进行中会暂缓安装；下载取消或失败可继续使用当前版本。

完整包缓存位于安装目录父目录的“解决方案-产数小微ICT工具箱-downloads/版本号”中，大小和 SHA-256 验证通过后可复用；支持断点续传和重试。新版本首次仍需下载完整资源，目前没有差分更新。

公开版本不含预置业务清单、API Key 或用户配置。API 服务在本机设置中配置，能力清单可自行导入。离线版本解压后运行主 EXE，并保留同目录的 _internal 和 LensSelectTool 文件夹。

- [GitHub 完整 ZIP](https://github.com/3374313410-debug/digital-office-download/releases/download/v1.2.0/digital-office-v1.2.0-windows-x64.zip)
- [发布说明与校验](https://github.com/3374313410-debug/digital-office-download/releases/tag/v1.2.0)
- [GitHub 历史版本](https://github.com/3374313410-debug/digital-office-download/releases)

文件校验值见对应发行版附件 SHA256SUMS.txt。
国内下载可使用 [Gitee Setup.exe](https://gitee.com/zhong-shuhao/digital-office-download/releases/download/v1.2.0/Setup.exe)（64 KiB），由安装器自动处理分卷。



安装器修订 2（2026-10-31）：

- 直接安装到选定文件夹，不再自动追加应用子目录。
- 修复部分 Windows 环境中目录移动被拒绝导致安装失败的问题；安装失败可恢复旧版。
- 修复中文按钮文字截断，适配放大字体。
- 显示整体百分比，涵盖下载、校验、解压和安装，完成后到 100%。
- 去掉预留空间的提示；保留空间不足时的检查。


安装器修订 3（2026-11-02）：

- 修复默认安装目录解压到 85% 时路径过长的问题；自动缩短临时解压和回滚备份目录。
- 下载时显示实时速度和预计剩余下载时间；复用缓存时明确提示无需重复下载。
- 新装、覆盖安装均已用完整发布资源验证，缓存位置与旧安装器兼容。
