# 暗黑破坏神2：重制版 · 多开器（D2R-DK）

本仓库是 **[FCPOWERUP](https://github.com/fcpowerup)** 的《**暗黑破坏神 II：重制版**》多开器项目。

支持国服与国际服多开，每个账号独立保存画质、键位、Mod 和启动参数，内置宝宝巴士与窗口布局管理。

## 本次更新（v0.1.9）

- 国服新增「战网登录」添加账号，与 Token 登录二选一；两者可并存，登录和建号都能用
- 新增宝宝巴士：主号建房、小号自动加房，可只跟勾选账号，并可选择开车时最小化窗口（Pro 功能）
- 新增 ESC 退房设置：文件夹形式的 Mod 可选「原样」「按2次」「按1次」，修改后从下一局起生效
- 新增国服「更新游戏客户端」入口，更新完成后可保存当前战网账号
- 窗口管理升级：布局改为 10 个，可设名字，记住最小化状态和窗口叠放顺序，支持数字键直接加载和两个布局来回切换，还能吸附到游戏窗口标题栏
- 大幅提升登录和建房速度
- 新增快速启动模式（Pro 功能，仅国服）
- 新增死亡小退，需使用文件夹形式的 Mod，不支持 `.mpq` 打包格式
- 新增开机自启，登录 Windows 后打开 D2R-DK
- 新增右键「强制关闭此账号游戏」，可单独结束指定账号的游戏
- 支持游戏运行中保存当前画质和自订键位，无需先关闭游戏
- 更多设置按国服和国际服分别保存，包括启动间隔、自动布局、布局快捷键、自定义标题及 Mod 独立 Settings 等
- 配置保护升级：启动、退出和升级迁移前自动备份，损坏时尝试恢复；完整迁移可带上有效的国服战网登录资料，并增加 30 天备份提醒

## 下载

当前正式版：**v0.1.9.015** · build **2611100007**。

- [下载 ZIP（程序与离线使用说明）](https://github.com/fcpowerup/D2R-DK/releases/download/v0.1.9-build2611100007/D2R-DK_v0.1.9_build2611100007_p.zip)
- [下载 EXE](https://github.com/fcpowerup/D2R-DK/releases/download/v0.1.9-build2611100007/D2R-DK_v0.1.9_build2611100007_p.exe)
- [EXE 哈希文件](https://github.com/fcpowerup/D2R-DK/releases/download/v0.1.9-build2611100007/D2R-DK_v0.1.9_build2611100007_p.txt)
- [ZIP 哈希文件](https://github.com/fcpowerup/D2R-DK/releases/download/v0.1.9-build2611100007/D2R-DK_v0.1.9_build2611100007_p.zip.txt)

EXE SHA256：

```text
FF2A49C9C497BE97385C51A446320485CE7C312106E6D2702800A5F770123F2F
```

## 使用说明

[在线图文说明](https://fcpowerup.github.io/D2R-DK/) · [离线单文件说明](https://github.com/fcpowerup/D2R-DK/releases/download/v0.1.9-build2611100007/D2R-DK-user-guide.html)

## 运行环境

- Windows 10 / 11，64 位。
- 已安装并可正常启动《暗黑破坏神 II：重制版》国服或国际服客户端。
- 多数机器已有 VC++ 2015–2022 x64；若提示缺少 `VCRUNTIME140.dll`，安装该运行库即可。
- 双击 EXE 即可运行，无需安装 Python、.NET 或 Node。

把程序放到固定目录。同目录下的 `D2R-DK.json`、`D2R-DK.lock.json`、`D2R-DK.ini` 会在首次运行后生成，请保留这些文件及其备份。

## 注意

第三方辅助软件，使用风险自负。主密码无法找回。Token、完整迁移包及其密码请妥善保管。

从 0.1.8 升级后请使用新版 D2R-DK，不要再运行 0.1.8，以免丢失新版保存的设置。
