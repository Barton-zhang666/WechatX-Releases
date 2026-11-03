# WechatX Releases

This public repository distributes **Windows x64 installers and signed update manifests only**. It does not contain the application source, signing private keys, API keys, or user chat archives.

本仓库仅用于分发 **Windows x64 安装包及带签名的更新清单**，不包含应用源码、签名私钥、API Key 或用户聊天数据。

Download installers from [Releases](https://github.com/Barton-zhang666/WechatX-Releases/releases). The application checks `updates.json` for updates. Initial installation of an updater-enabled version is required; older installations cannot gain this capability automatically.

请从 [Releases](https://github.com/Barton-zhang666/WechatX-Releases/releases) 下载安装包。支持自动更新的版本读取 `updates.json` 检查新版本；旧版需手动安装一次新版，之后可在软件内更新。

Updates are published only after the installer and its updater signature have been uploaded and verified. The installer retains the existing installation directory and local data. Current packages are development previews; updater signatures do not replace Windows publisher code signing.

安装包和更新签名上传、校验完成后才更新版本清单。升级保留原安装目录和本地数据。目前为开发预览；更新签名不等同于 Windows 发布者代码签名。