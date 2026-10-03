# 📱 学升桌面端 (XueSheng Desktop)

<p align="center">
  <img src="https://webapp.songy.info/icons/Icon-192.png" width="108" alt="XueSheng Logo" />
</p>

<p align="center">
  <strong>跨平台多端原生极轻量「学升」桌面客户端 (macOS / Windows / Linux)</strong>
</p>

<p align="center">
  <strong>简体中文</strong> | <a href="./README_EN.md">English</a>
</p>

<p align="center">
  <a href="https://github.com/yaping-pro/xuesheng-desktop/releases/latest"><img src="https://img.shields.io/github/v/release/yaping-pro/xuesheng-desktop?color=blue&label=最新版本" alt="Release" /></a>
  <a href="https://github.com/yaping-pro/xuesheng-desktop/blob/main/LICENSE"><img src="https://img.shields.io/github/license/yaping-pro/xuesheng-desktop" alt="License" /></a>
  <img src="https://img.shields.io/badge/支持平台-macOS%20%7C%20Windows%20%7C%20Linux-brightgreen" alt="Platforms" />
  <img src="https://img.shields.io/badge/体积-~8MB-success" alt="Size" />
</p>

---

## ✨ 特性

- 🎐 **极度轻量**：仅约 **8 MB** 安装包体积，内存占用极低。
- 📱 **黄金视口**：锁定 $420 \times 840$ 手机屏幕比例，桌面边栏查看课程与动态绝不留白。
- 🌐 **全平台支持**：
  - **macOS**：Universal 通用双架构，原生兼容 Apple Silicon (M1~M4) 与 Intel 芯片。
  - **Windows**：基于 Edge WebView2 原生内核，提供 `.msi` 标准安装包。
  - **Linux**：提供 `.AppImage`（免安装双击运行）与 `.deb`（Debian/Ubuntu 系列）格式。
- 🪟 **原生窗口交互**：保留原生标准标题栏，所有返回键、视频播放控件均可被鼠标精准触发，支持任意拖拽。

---

## 📥 下载安装

前往 [Releases 页面](https://github.com/yaping-pro/xuesheng-desktop/releases/latest) 直接获取对应平台的最新安装包：

| 平台 | 格式 | 说明 |
| :--- | :--- | :--- |
| **macOS** | [XueSheng.dmg](https://github.com/yaping-pro/xuesheng-desktop/releases/latest/download/XueSheng.dmg) | 拖拽至「应用程序」文件夹即可运行 |
| **Windows** | [XueSheng.msi](https://github.com/yaping-pro/xuesheng-desktop/releases/latest/download/XueSheng.msi) | 双击运行安装向导，自动创建桌面图标 |
| **Linux (通用)** | [XueSheng.AppImage](https://github.com/yaping-pro/xuesheng-desktop/releases/latest/download/XueSheng.AppImage) | 赋予执行权限后双击即跑：`chmod +x XueSheng.AppImage` |
| **Linux (Debian/Ubuntu)** | [XueSheng.deb](https://github.com/yaping-pro/xuesheng-desktop/releases/latest/download/XueSheng.deb) | 运行 `sudo dpkg -i XueSheng.deb` |

---

## ⚠️ 首次运行安全提示（绕过系统拦截）

### 🍎 macOS 系统（Gatekeeper）
首次打开若提示「无法验证开发者」或「已损坏」：
- **终端解锁（推荐）**：执行 `xattr -cr /Applications/XueSheng.app`
- **图形解锁**：在「访达」中按住 <kbd>Control</kbd> 键右键点击应用图标 $\to$ 点击「打开」 $	o$ 点击「仍要打开」。

### 🪟 Windows 系统（SmartScreen）
若提示「Windows 已保护你的电脑」：
- 点击弹窗上的 **「更多信息」**（More info）链接 $\to$ 随后点击右下角出现的 **「仍要运行」**（Run anyway）即可。

---

## 💡 常用快捷键

| 快捷键 | 功能 |
| :--- | :--- |
| <kbd>⌘/Ctrl</kbd> + <kbd>[</kbd> | 返回上一页 |
| <kbd>⌘/Ctrl</kbd> + <kbd>]</kbd> | 前进下一页 |
| <kbd>⌘/Ctrl</kbd> + <kbd>R</kbd> | 强制刷新当前页面 |
| <kbd>⌘/Ctrl</kbd> + <kbd>⇧ Shift</kbd> + <kbd>H</kbd> | 立即返回首页 |
| <kbd>⌘/Ctrl</kbd> + <kbd>-</kbd> / <kbd>+</kbd> | 页面缩放缩小 / 放大 |
| <kbd>⌘/Ctrl</kbd> + <kbd>0</kbd> | 重置页面缩放为 100% |

---

## 🤝 参与共建与贡献

- **发现 Bug / 功能建议**：请前往 [Issues 页面](https://github.com/yaping-pro/xuesheng-desktop/issues/new/choose) 提交。
- **参与开发 / 提 PR**：本仓库基于 `app.json` 声明式配置驱动，修改配置即可提 PR，云端 Actions 会自动校验。详见 [CONTRIBUTING.md](./CONTRIBUTING.md)。

---

## 📄 开源许可

本项目采用 [MIT 许可证](./LICENSE)。基于 [tw93/Pake](https://github.com/tw93/Pake) 构建。
