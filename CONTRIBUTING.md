# 贡献指南 (Contributing Guide)

欢迎参与 **学升桌面端 (XueSheng Desktop)** 的共建！

本项目采用**声明式无代码 / 低门槛**架构设计，你不需要在本地安装庞大的 Rust 工具链或 C++ 编译器，只要会写 JSON 或前端 CSS/JS，就能轻松参与贡献！

---

## 🛠️ 如何提 PR (Pull Request)

### 1. Fork 并在网页上直接编辑
1. 点击右上角 **Fork**，将本仓库复制一份到你的 GitHub 个人账号。
2. 找到仓库根目录下的核心配置文件 `app.json`。
3. 点击右上角铅笔图标进行修改。

### 2. 核心配置文件说明 (`app.json`)
```json
{
  "$schema": "https://raw.githubusercontent.com/tw93/Pake/main/schema/pake.schema.json",
  "name": "XueSheng",
  "url": "https://webapp.songy.info/#/home",
  "icon": "https://webapp.songy.info/icons/Icon-192.png",
  "width": 420,
  "height": 840,
  "minWidth": 380,
  "minHeight": 640,
  "hideTitleBar": false,
  "newWindow": true
}
```

### 3. 可以贡献哪些方向？
- **视口比例优化**：针对特定屏幕分辨率调整 `width` / `height` / `minWidth`；
- **自定义样式注入**：添加 `inject` 字段注入特定 CSS/JS 脚本（如深色模式微调、去干扰元素等）；
- **跨平台支持**：提供 Windows (`.msi`) 或 Linux (`.deb` / `.AppImage`) 的打包配置；
- **文档优化**：完善 README、使用技巧或常见排障指南。

### 4. 云端自动构建检验
当你提交 Pull Request 时，GitHub Actions 会**全自动运行云端编译校验**：
- 只要构建跑通（显示绿色的 `✓ All checks have passed`），维护者便可一键合并。
- 每次合并到 `main` 分支并打 Release 标签后，系统将自动发布全新安装包。

---

## 🐞 发现 Bug 或有新需求？

请直接在 [Issues](https://github.com/yaping-pro/xuesheng-desktop/issues/new/choose) 中选择对应的模板提交，我们会第一时间响应！
