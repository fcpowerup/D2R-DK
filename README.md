# 暗黑破坏神2：重制版 · 多开器（D2R-DK）

本仓库是 **[FCPOWERUP](https://github.com/fcpowerup)** 的《**暗黑破坏神 II：重制版**》多开器项目。

支持国服与国际服多开，每个账号独立保存画质、键位、Mod 和启动参数，内置宝宝巴士与窗口布局管理。

## 本次更新（v0.2.0）

- 适配国际服 3.4 版本
- 适配红叶 2.9
- 适配 WILL 3.4.0.1
- TZ/DC 监控新增国际服备用源
- Win10 用户也可以用上 Win11 的 UI 设计
- 若干问题修复

## 下载

当前正式版：**v0.2.0.062** · build **2611232106**。

- [下载 ZIP（程序与离线使用说明）](https://github.com/fcpowerup/D2R-DK/releases/download/v0.2.0-build2611232106/D2R-DK_v0.2.0_build2611232106_p.zip)
- [下载 EXE](https://github.com/fcpowerup/D2R-DK/releases/download/v0.2.0-build2611232106/D2R-DK_v0.2.0_build2611232106_p.exe)
- [EXE 哈希文件](https://github.com/fcpowerup/D2R-DK/releases/download/v0.2.0-build2611232106/D2R-DK_v0.2.0_build2611232106_p.txt)
- [ZIP 哈希文件](https://github.com/fcpowerup/D2R-DK/releases/download/v0.2.0-build2611232106/D2R-DK_v0.2.0_build2611232106_p.zip.txt)

EXE SHA256：

```text
4BC50846415C0D3CEB63413738EDBC207F40D8EA51F79592E72CEE32F8F45789
```

## 使用说明

[在线图文说明](https://fcpowerup.github.io/D2R-DK/) · [离线单文件说明](https://github.com/fcpowerup/D2R-DK/releases/download/v0.2.0-build2611232106/D2R-DK-user-guide.html)

## 运行环境

- Windows 10 / 11，64 位。
- 已安装并可正常启动《暗黑破坏神 II：重制版》国服或国际服客户端。
- 多数机器已有 VC++ 2015–2022 x64；若提示缺少 `VCRUNTIME140.dll`，安装该运行库即可。
- 双击 EXE 即可运行，无需安装 Python、.NET 或 Node。

把程序放到固定目录。同目录下的 `D2R-DK.json`、`D2R-DK.lock.json`、`D2R-DK.ini` 会在首次运行后生成，请保留这些文件及其备份。

## 注意

第三方辅助软件，使用风险自负。主密码无法找回。Token、完整迁移包及其密码请妥善保管。

从 0.1.8 升级后请使用新版 D2R-DK，不要再运行 0.1.8，以免丢失新版保存的设置。
