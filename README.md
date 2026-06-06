# selfcmd-releases
<div align="center">

# 🖥️ SelfCmd v2.0.1

### Your SSH command center for Windows — connect, automate, and monitor servers without leaving the app.

[![Platform](https://img.shields.io/badge/platform-Windows%2010%20%2F%2011-0078D6?logo=windows)](#-install-windows)
[![Version](https://img.shields.io/badge/version-2.0.1-8b5cf6)](https://github.com/Rocky-Works/selfcmd/releases)
[![Price](https://img.shields.io/badge/Starter-Free-22c55e)](#-editions)
[![License](https://img.shields.io/badge/Pro-offline%20%26%20device--bound-f59e0b)](#-editions)

</div>

---

SelfCmd is a desktop app for developers and small ops teams who juggle many Linux
servers from a Windows machine. Save your connections, turn frequent commands into
**one-click buttons**, **schedule** recurring tasks, chain them into **workflows**,
and keep an eye on **CPU / memory / disk** — all from one clean window, fully offline.

No accounts. No phone-home. Your credentials never leave your machine.

---

## 🔧 What's New in 2.0.1

| | |
|---|---|
| 🚀 **Launch on startup** | Optionally start SelfCmd automatically when Windows boots (Settings → UI → Startup). |
| 🧭 **Reworked Help page** | Cleaner layout, split into **Support & Feedback** and **Version & License**. |
| 🔑 **Easier licensing** | "Get a license" opens a pre-filled email (with your machine ID) to support@selfcmd.com. |
| 💬 **Smarter feedback** | If the feedback server is unreachable, SelfCmd offers to send via your own email client. |
| 🌐 **Polished details** | Unified domains and contact info across the app. |

> Upgrading from 2.0.0? Just install over the top — your connections, tasks, and settings are preserved.

---

## ✨ Highlights

- 🎨 **Modern PySide6 (Qt 6) UI** — fast side navigation, lazy-loaded panels, clean and responsive.
- 🌍 **Live language switching** — English ⇄ 简体中文 with no restart.
- 🌗 **Dark & Light themes** — consistent across every panel.
- 🧩 **Collapsible command groups** — tag filtering, single-click fill, double-click run.
- ⬇️ **In-app online updates** — check, download, and install the latest build without leaving the app.

---

## 🚀 Core Features

- **🔐 SSH Connection Manager** — hosts, ports, password or key auth, groups & tags. Passwords encrypted at rest (Fernet AES). Import from Xshell, MobaXterm, FinalShell, SecureCRT, PuTTY, `~/.ssh/config`.
- **⚡ One-Click Command Buttons** — build a reusable command library in collapsible groups.
- **⏰ Scheduled Tasks** — run commands on a schedule with result checks and per-module logging.
- **🔗 Workflow Engine** — chain tasks sequentially or in parallel, including SFTP upload steps; export / import as JSON.
- **📊 Resource Monitoring & Alerts** — track CPU / memory / disk with non-blocking toasts and optional SMTP email alerts.
- **🧰 Network & File Tools** — ping, port/service probing, MAC lookup, SFTP/FTP transfer, and more.
- **🌐 Built-in i18n** — full English / Chinese coverage.

---

## 🔐 Editions

| Capability | 🆓 Starter (Free) | ⭐ Pro |
|---|:---:|:---:|
| SSH connections | up to **5** | **Unlimited** |
| Scheduled tasks | up to **10** | **Unlimited** |
| Command buttons | up to **30** | **Unlimited** |
| Command groups | up to **3** | **Unlimited** |
| Workflow engine | preview | ✅ |
| Resource monitoring | preview | ✅ |
| Activation | — | **Offline, device-bound** |

> Hitting a limit never deletes data — Starter only blocks creating *new* items beyond the limit. Pro is a one-time, fully offline license.

---

## 📥 Install (Windows)

1. Download **`SelfCmd_Setup_2.0.1.exe`** from the **Assets** below.
2. Run the installer and follow the prompts.
3. Launch **SelfCmd** from the Start menu.

> ⚠️ **First run:** this build isn't code-signed yet, so Windows SmartScreen may show
> *"Windows protected your PC."* Click **More info → Run anyway** to continue.
> A signed build is on the roadmap.

---

## 💬 Support

- 📧 **support@selfcmd.com** — or use **Help → Send feedback** in the app
- 🐛 **Issues:** https://github.com/Rocky-Works/selfcmd/issues

---

<div align="center">

### 中文说明

</div>

# 🖥️ SelfCmd v2.0.1（中文）

> 面向 Windows 的 SSH 运维工作台 —— 在一个应用里连接、自动化并监控你的服务器。

SelfCmd 专为「在 Windows 上管理多台 Linux 服务器」的开发者与小型运维团队打造。
保存连接、把常用命令变成**一键按钮**、设置**定时任务**、串联成**工作流**、
实时查看 **CPU / 内存 / 磁盘** —— 全部在一个窗口内完成，且完全离线。
无需账号、不回传数据，凭证永远留在你本机。

## 🔧 2.0.1 更新内容

| | |
|---|---|
| 🚀 **开机自启动** | 可选随 Windows 启动自动运行（设置 → 界面 → 启动）。 |
| 🧭 **帮助页重构** | 布局更清晰，分为「支持与反馈」「版本与授权」。 |
| 🔑 **更便捷的授权** | 「获取 License」改为打开预填好的邮件（含机器码）发往 support@selfcmd.com。 |
| 💬 **更聪明的反馈** | 反馈服务器不可达时，可改用本地邮件客户端发送。 |
| 🌐 **细节统一** | 统一了应用内的域名与联系方式。 |

> 从 2.0.0 升级：直接覆盖安装即可，连接 / 任务 / 设置都会保留。

## ✨ 亮点

- 🎨 **全新 PySide6 (Qt 6) 界面** —— 侧边导航、面板懒加载，更快更清爽。
- 🌍 **中英文实时切换** —— 无需重启。
- 🌗 **明 / 暗主题** —— 所有面板风格统一。
- 🧩 **可折叠命令分组** —— 标签筛选、单击填充、双击执行。
- ⬇️ **应用内在线升级** —— 检查、下载、安装最新版，无需离开应用。

## 🚀 核心功能

- **🔐 SSH 连接管理** —— 主机、端口、密码/密钥认证、分组与标签；密码本地加密（Fernet AES）；支持从 Xshell、MobaXterm、FinalShell、SecureCRT、PuTTY、`~/.ssh/config` 导入。
- **⚡ 一键命令按钮** —— 构建可复用命令库，按可折叠分组组织。
- **⏰ 定时任务** —— 按计划执行命令，支持结果检查与分模块日志。
- **🔗 工作流引擎** —— 串行/并行编排任务，含 SFTP 上传步骤，可导出/导入 JSON。
- **📊 资源监控与告警** —— 监测 CPU / 内存 / 磁盘，非阻塞提示 + 可选 SMTP 邮件告警。
- **🧰 网络与文件工具** —— ping、端口/服务探测、MAC 查找、SFTP/FTP 传输等。
- **🌐 内置国际化** —— 完整中英文覆盖。

## 🔐 版本

| 能力 | 🆓 Starter（免费） | ⭐ Pro |
|---|:---:|:---:|
| SSH 连接 | 最多 **5** | **无限** |
| 定时任务 | 最多 **10** | **无限** |
| 命令按钮 | 最多 **30** | **无限** |
| 命令分组 | 最多 **3** | **无限** |
| 工作流引擎 | 预览 | ✅ |
| 资源监控 | 预览 | ✅ |
| 激活方式 | — | **离线、绑定设备** |

> 达到上限不会删除任何数据，Starter 仅阻止创建超出上限的「新」项目。Pro 为一次性、完全离线的授权。

## 📥 安装（Windows）

1. 从下方 **Assets** 下载 **`SelfCmd_Setup_2.0.1.exe`**。
2. 运行安装程序并按提示完成。
3. 从开始菜单启动 **SelfCmd**。

> ⚠️ **首次运行：** 此版本尚未代码签名，Windows SmartScreen 可能提示
> *「Windows 已保护你的电脑」*，点击 **更多信息 → 仍要运行** 即可。签名版本已在计划中。

## 💬 支持

- 📧 **support@selfcmd.com** —— 或在应用内 **帮助 → 发送反馈**
- 🐛 **Issues：** https://github.com/Rocky-Works/selfcmd/issues
