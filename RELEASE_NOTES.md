# TBOT 0.6.5 · 登录自启修复（Windows x64）

本次将已在作者电脑通过重启测试的登录启动修正落实到安装包：采用系统 Windows PowerShell 完整路径，向 Windows 实际用户登录项登记并回读核对。仍使用现有助手，不添加服务、计划任务或桌面快捷方式；角色、武器、原生桥接 0.4.1 和运行环境保持。

## 下载与升级

- [完整模组与一键安装包](https://github.com/misumisakiko/TBOT/releases/download/v0.6.5/TBOT-0.6.5-Windows-x64.zip)：未安装或使用 GitHub 本地版的玩家，完整解压后运行“一键安装.cmd”。
- [独立首次设置包](https://github.com/misumisakiko/TBOT/releases/download/v0.6.5/TBOT-FirstSetup-0.6.5-Windows-x64.zip)：已订阅工坊的玩家，完整解压后运行“首次设置.cmd”。
- 同名 .sha256 为可选校验文件。Source code 自动归档不是安装包。

**此前遇到开机后后台未运行的玩家，本次请保存并完全关闭以撒，再运行新版首次设置一次；仅等待 Steam 工坊更新无法修正未运行助手的登录登记。GitHub 本地版运行新版完整包即可。** 已有库存、生命、快捷栏和继续局保留，不要使用旧分享版卸载器。首次设置可用于当前完整工坊版本，无需先等待作者上传 0.6.5。

之后直接从 Steam 启动以撒，在 Mods 启用 TBOT 即可；禁用或退出时关闭原生后台。安装时 Steam 保持登录；首次安装前先分别打开一次以撒及 tModLoader 到主菜单再关闭。需要 Windows x64、Repentance+ 1.9.7.17、tModLoader 2026.08.3.0 / Terraria 1.4.4.9 / .NET 8 x64。无需另装 Python，不含完整游戏和私人存档。

## 验证范围

本机真实重启测试由作者确认通过；新安装登记的 9 项定向检查、真实 Windows 注册表重复登记/回读、两个包内 Python 入口及 ZIP/清单/隐私检查通过。新安装命令与本机通过重启的命令逐字相同。稳定玩法和原生载荷复用，未重新遍历武器。

其他电脑和真实工坊订阅更新仍需验收，既有前台性能限制保持。仓库保持私人、发行保留 Pre-release，旧 v0.6.3/v0.6.4 留存；本次 Steam 工坊由作者手动更新同一条目。
