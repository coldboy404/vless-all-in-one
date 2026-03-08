# vless-all-in-one

这是从上游项目整理后的 **代码仓库版**，仅保留脚本、配置与实现文件，并将说明文档重写为更适合 GitHub 维护的精简结构。

## 一键使用脚本

可直接使用 GitHub 仓库中的脚本：

```bash
curl -O https://raw.githubusercontent.com/coldboy404/vless-all-in-one/main/vless-server.sh && bash vless-server.sh
```

如果你的系统没有 `curl`，也可以使用：

```bash
wget -O vless-server.sh https://raw.githubusercontent.com/coldboy404/vless-all-in-one/main/vless-server.sh && bash vless-server.sh
```

> 如需先审查脚本再执行，可先查看文件内容或参考 `docs/usage-notes.md`。

## 当前内容

- `vless-server.sh`：主部署脚本
- `docs/overview.md`：项目概览
- `docs/features.md`：功能摘要
- `docs/usage-notes.md`：精简使用说明
- `docs/source-note.md`：来源与整理策略说明

## 文档入口

- [项目概览](docs/overview.md)
- [功能摘要](docs/features.md)
- [使用说明（精简版）](docs/usage-notes.md)
- [来源说明](docs/source-note.md)

## 仓库定位

本仓库主要用于：
- 保存核心部署脚本与相关配置代码
- 便于在 GitHub 上继续维护、审查和二次改造
- 降低原始说明文档噪音，让代码结构更聚焦

## 当前已搬运文件

- `vless-server.sh`

## 来源

原始来源：
- GitLab: <https://gitlab.com/chil30-group/vless-all-in-one>

当前仓库是基于上游代码内容做的轻量化整理版，目标是保留实现、减少噪音。

## 免责声明

本仓库内容涉及代理、网络转发和自动化部署脚本。请仅在你有权限、且符合当地法律法规与服务条款的前提下使用。部署前请自行完成代码审计与安全检查。
