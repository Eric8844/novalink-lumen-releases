# NovaLink Lumen Releases

NovaLink Lumen 的正式版安装包与更新日志仓库（不含源码）。

## 下载

- 最新正式版：<https://github.com/Eric8844/novalink-lumen-releases/releases/latest>
- 直链（1.5.0）：<https://github.com/Eric8844/novalink-lumen-releases/releases/download/v1.5.0/NovaLinkLumen-WinUI-Setup-1.5.0.exe>

安装包文件名统一为 `NovaLinkLumen-WinUI-Setup-<版本>.exe`。启动器内置更新器只认这个命名，会从本仓库的 latest Release 取包。

## 通道

- 正式版（本仓库）：只接受纯数字标签，如 `v1.5.0`。
- 测试版（[novalink-lumen-preview](https://github.com/Eric8844/novalink-lumen-preview)）：只接受带 `-preview` 的标签。

两个通道互不串台：正式版客户端不会把测试版当成更新，测试版也不会被正式版覆盖。

## 安装

双击安装包即可（每用户安装，不需要管理员权限）。首次启动检测到版本升级时，会把数据备份到 `%LOCALAPPDATA%\NovaLink Lumen\Data_Backup_v<旧版本>`，想回退可在「设置 → 关于 → 数据备份与恢复」一键恢复。

## 源码

启动器是 MIT 开源的：<https://github.com/Eric8844/novalink-lumen>（本版对应 tag `v1.5.0`）。本仓库只放安装包与更新日志，不放源码。
