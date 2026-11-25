# EFCCA 音视频编辑与播放器

[网站与下载中心](https://media-9ad.pages.dev/) · [完整使用教程](https://media-9ad.pages.dev/guide) · [发布版本](https://github.com/110711071107victor-cpu/efcca-media-releases/releases)

Windows 用户请下载 **EFCCA-Windows-v1.1.15.zip**。完整包约 1.8 GB，包含免费本地 AI 模型、运行环境、背景素材及播放器。

1. 等待 ZIP 下载完成。
2. 右键 ZIP → **全部解压缩**，建议放到 `D:\EFCCA` 等容易找到的位置。
3. 进入解压后的文件夹，双击 **晚堂舞台.exe**，程序会打开浏览器。
4. 点击导入歌曲或视频，开始识别、编辑、编排背景和导出。

## 版本中的文件

| 文件 | 用途 |
| --- | --- |
| EFCCA-Windows-v1.1.15.zip | Windows 完整本地程序，含 AI 模型 |
| EFCCA-Android-v1.1.15.zip | 安卓网页入口和使用指南 |
| EFCCA-Mac-v1.1.15.zip | Mac 网页入口和使用指南 |
| EFCCA-Cloudflare-Pages-v1.1.15.zip | 管理员上传到 Cloudflare Pages 的网站包 |
| EFCCA-Maintenance-v1.1.15.zip | Windows 管理员发布版本和公告的维护工具 |
| EFCCA-update-构建号.zip | 程序自动下载的签名更新包 |
| latest.json / downloads.json / SHA256SUMS.txt | 签名清单、下载文件信息及 SHA-256 校验值 |

安卓和 Mac 当前使用网页入口，在线识别与导出需要管理员另行连接处理服务。网站可以预览背景并阅读教程。

## 自动保存和更新

本机上传素材和编辑记录保存在程序文件夹的 `data` 内。请保留该文件夹，备份时复制整个程序文件夹。

联网启动后自动检查版本，运行期间每小时检查。更新通过签名和 SHA-256 校验后下载；在程序内保存并重启完成安装。发布公告也会在联网检查时读取。关闭程序或断网时不能立即收到通知。

## 管理员

网站部署在 Cloudflare Pages，安装包与更新存放在本仓库的 Releases。无需启用 Cloudflare R2。

请参阅[管理员部署指南](https://media-9ad.pages.dev/deploy)。普通用户不需要运行管理员维护工具。

此公开仓库提供程序发布文件，不包含任何用户账户、项目、原视频或更新签名私钥。

© EFCCA · v1.1.15
