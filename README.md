# 📱 学升桌面端 (XueSheng Desktop)

<p align="center">
  <img src="https://webapp.songy.info/icons/Icon-192.png" width="108" alt="XueSheng Logo" />
</p>

<p align="center">
  <strong>专为 macOS 深度调优的极轻量「学升」桌面原生客户端</strong>
</p>

<p align="center">
  <a href="https://github.com/yaping-pro/xuesheng-desktop/releases/latest"><img src="https://img.shields.io/github/v/release/yaping-pro/xuesheng-desktop?color=blue&label=最新版本" alt="Release" /></a>
  <a href="https://github.com/yaping-pro/xuesheng-desktop/blob/main/LICENSE"><img src="https://img.shields.io/github/license/yaping-pro/xuesheng-desktop" alt="License" /></a>
  <img src="https://img.shields.io/badge/体积-8.6MB-success" alt="Size" />
  <img src="https://img.shields.io/badge/架构-Universal%20(Intel%20%2B%20Apple%20Silicon)-orange" alt="Architecture" />
</p>

---

## ✨ 特性

- 🎐 **极度轻量**：仅约 **8.6 MB**，内存占用远低于传统 Electron 封装。
- 📱 **黄金视口**：锁定 $420 \times 840$ 手机屏幕比例，桌面边栏查看课程与动态绝不留白。
- 🍎 **全系兼容**：原生 Universal 通用架构，全面支持 Apple Silicon (M1/M2/M3/M4) 及老款 Intel 芯片 Mac。
- 🪟 **原生窗口交互**：保留原生标准标题栏，所有返回键、视频播放控件均可被鼠标精准触发，支持任意拖拽与置顶。

---

## 📥 下载与安装

### 方式一：直接下载安装包
前往 [Releases 页面](https://github.com/yaping-pro/xuesheng-desktop/releases/latest) 下载最新发布的 **`XueSheng.dmg`**：
1. 双击打开 `XueSheng.dmg`。
2. 将 `XueSheng.app` 图标拖拽到系统的 `Applications`（应用程序）文件夹即可。

---

## ⚠️ 首次打开必读（绕过 macOS 安全拦截）

由于本客户端为社区共建打包，未购买苹果每年 $99 的商业开发者证书，首次打开时系统可能会提示「无法验证开发者」或「已损坏」。

请任选以下一种方式授权（仅需操作一次，后续即可直接双击正常使用）：

### 🚀 方式 A：终端极速解锁（推荐）
打开系统的「终端 (Terminal)」，粘贴并回车执行以下命令：
```bash
xattr -cr /Applications/XueSheng.app
```

### ☕ 方式 B：访达图形化解锁（无需敲命令）
1. 打开访达 (Finder) -> 进入「应用程序 (Applications)」。
2. 找到 `XueSheng` 应用图标。
3. **按住键盘上的 `Control` 键不放，鼠标右键点击应用图标**，在弹出的菜单中点击 **「打开」**。
4. 在弹出的系统确认框中，点击 **「仍要打开」** 即可。

---

## 💡 常用快捷键

| 快捷键 | 功能 |
| :--- | :--- |
| <kbd>⌘ Command</kbd> + <kbd>[</kbd> | 返回上一页 |
| <kbd>⌘ Command</kbd> + <kbd>]</kbd> | 前进下一页 |
| <kbd>⌘ Command</kbd> + <kbd>R</kbd> | 强制刷新页面 |
| <kbd>⌘ Command</kbd> + <kbd>⇧ Shift</kbd> + <kbd>H</kbd> | 立即返回首页 |
| <kbd>⌘ Command</kbd> + <kbd>-</kbd> / <kbd>+</kbd> | 页面缩放缩小 / 放大 |
| <kbd>⌘ Command</kbd> + <kbd>0</kbd> | 重置页面缩放 |

---

## 🤝 参与共建与贡献

欢迎社群同学参与共建与改进！

- **提交 Bug / 功能建议**：请前往 [Issues 页面](https://github.com/yaping-pro/xuesheng-desktop/issues/new/choose) 提交。
- **参与开发 / 提 PR**：本仓库基于声明式配置管理，**无需本地安装 Rust 或复杂的开发环境**，修改 `app.json` 即可提交 PR，云端 GitHub Actions 会自动完成构建校验。详细步骤请参考 [CONTRIBUTING.md](./CONTRIBUTING.md)。

---

## 📄 开源许可

本项目采用 [MIT 许可证](./LICENSE)。
基于 [tw93/Pake](https://github.com/tw93/Pake) 构建打包。
