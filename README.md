# MC 启动器 - void

基于 PCL 2.14 开源版本进行修改的个人 Minecraft 启动器项目，包含陶瓦联机相关功能与 Windows 安装程序构建脚本。

## 项目内容

- PCL 启动器源代码及相关项目文件
- 陶瓦联机模块相关代码与构建资源
- Mod 下载前置依赖提示功能的修改
- Windows 安装程序构建脚本（Packaging）

## 构建说明

请使用 Windows、Visual Studio / MSBuild 以及项目所需的 .NET Framework 和 NuGet 依赖。首次构建需要联网还原 NuGet 包。

在仓库根目录运行 `BuildAndInstall.cmd` 可启动构建流程。安装程序生成失败时，可查看 `build.log` 和 Packaging 目录中的日志。

## Microsoft 登录

本项目使用 Microsoft/Xbox/Minecraft 官方登录流程。第三方应用注册需要符合 Minecraft 的 AppID 审核要求；尚未获批的 Client ID 可能会在 Minecraft Services 返回 `Invalid app registration`。请勿在此提交个人账号密码、访问令牌或客户端密钥。

## 许可证与上游声明

本项目包含 PCL 及第三方组件。请阅读仓库中的 `LICENCE`、`THIRD-PARTY-NOTICES.txt` 和各组件许可证，并遵守对应条款。本项目与 Microsoft、Mojang、PCL 原作者或陶瓦联机官方无隶属关系。
