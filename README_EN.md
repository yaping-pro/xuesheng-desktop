# 📱 XueSheng Desktop

<p align="center">
  <img src="https://webapp.songy.info/icons/Icon-192.png" width="108" alt="XueSheng Logo" />
</p>

<p align="center">
  <strong>Ultra-lightweight, native multi-platform desktop client for XueSheng (macOS / Windows / Linux)</strong>
</p>

<p align="center">
  <a href="./README.md">简体中文</a> | <strong>English</strong>
</p>

<p align="center">
  <a href="https://github.com/yaping-pro/xuesheng-desktop/releases/latest"><img src="https://img.shields.io/github/v/release/yaping-pro/xuesheng-desktop?color=blue&label=Latest%20Release" alt="Release" /></a>
  <a href="https://github.com/yaping-pro/xuesheng-desktop/blob/main/LICENSE"><img src="https://img.shields.io/github/license/yaping-pro/xuesheng-desktop" alt="License" /></a>
  <img src="https://img.shields.io/badge/Platforms-macOS%20%7C%20Windows%20%7C%20Linux-brightgreen" alt="Platforms" />
  <img src="https://img.shields.io/badge/Size-~8MB-success" alt="Size" />
</p>

---

## ✨ Features

- 🎐 **Extremely Lightweight**: Packaged binary size is only **~8 MB** (nearly 20x smaller than Electron).
- 📱 **Mobile Aspect Ratio**: Locked to a $420 \times 840$ mobile golden viewport ratio—no wasted whitespace on desktop sidebars.
- 🌐 **Cross-Platform Native**:
  - **macOS**: Universal binary supporting both Apple Silicon (M1/M2/M3/M4) and Intel chips.
  - **Windows**: Built with Edge WebView2 native engine, standard `.msi` installer provided.
  - **Linux**: Standalone `.AppImage` (double-click to run on any distro) and `.deb` (Debian/Ubuntu).
- 🪟 **Native Window Experience**: Full native title bar controls, drag-and-drop support, zero click-through issues on video controls or back buttons.

---

## 📥 Download & Installation

Visit the [Releases Page](https://github.com/yaping-pro/xuesheng-desktop/releases/latest) to download the latest installer for your system:

| Platform | Format | How to Install |
| :--- | :--- | :--- |
| **macOS** | [XueSheng.dmg](https://github.com/yaping-pro/xuesheng-desktop/releases/latest/download/XueSheng.dmg) | Drag `XueSheng.app` into your `Applications` folder |
| **Windows** | [XueSheng.msi](https://github.com/yaping-pro/xuesheng-desktop/releases/latest/download/XueSheng.msi) | Double-click to run the setup wizard |
| **Linux (Universal)** | [xuesheng.AppImage](https://github.com/yaping-pro/xuesheng-desktop/releases/latest/download/xuesheng.AppImage) | Make executable and run: `chmod +x xuesheng.AppImage && ./xuesheng.AppImage` |
| **Linux (Debian/Ubuntu)** | [xuesheng.deb](https://github.com/yaping-pro/xuesheng-desktop/releases/latest/download/xuesheng.deb) | Run `sudo dpkg -i xuesheng.deb` |

---

## ⚠️ First-Time Security Bypass Guide

### 🍎 macOS (Gatekeeper)
If macOS shows *"App is damaged and cannot be opened"* or *"Cannot verify developer"*:
- **Terminal (Fastest)**: Run `xattr -cr /Applications/XueSheng.app`
- **Finder**: Hold <kbd>Control</kbd>, right-click `XueSheng.app` $\to$ Click **Open** $\to$ Click **Open Anyway**.

### 🪟 Windows (SmartScreen)
If Windows shows *"Windows protected your PC"*:
- Click **"More info"** $\to$ Click **"Run anyway"**.

---

## 💡 Keyboard Shortcuts

| Shortcut | Description |
| :--- | :--- |
| <kbd>⌘/Ctrl</kbd> + <kbd>[</kbd> | Back to previous page |
| <kbd>⌘/Ctrl</kbd> + <kbd>]</kbd> | Forward to next page |
| <kbd>⌘/Ctrl</kbd> + <kbd>R</kbd> | Reload current page |
| <kbd>⌘/Ctrl</kbd> + <kbd>⇧ Shift</kbd> + <kbd>H</kbd> | Return to Home |
| <kbd>⌘/Ctrl</kbd> + <kbd>-</kbd> / <kbd>+</kbd> | Zoom out / Zoom in |
| <kbd>⌘/Ctrl</kbd> + <kbd>0</kbd> | Reset zoom to 100% |

---

## 🤝 Community & Contributing

- **Report Bugs / Propose Ideas**: Open an issue at [GitHub Issues](https://github.com/yaping-pro/xuesheng-desktop/issues/new/choose).
- **Contribute PRs**: This repository is declaratively driven by `app.json`. Edit the JSON config directly on GitHub to submit PRs without any local Rust/C++ toolchain setup. See [CONTRIBUTING.md](./CONTRIBUTING.md).

---

## 📄 License

Open-source under [MIT License](./LICENSE). Powered by [tw93/Pake](https://github.com/tw93/Pake).
