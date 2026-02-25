# OpenClawRun

OpenClawRun 是一款 macOS 菜单栏应用，可让你**无需打开终端**就管理 OpenClaw Gateway。  
无论你是否是工程师，它都能让日常运维更轻松。

**语言:** [English](./README.md) | [日本語](./README.ja.md) | [简体中文](./README.zh-Hans.md) | [繁體中文](./README.zh-Hant.md) | [Português (Brasil)](./README.pt-BR.md)

## Download

👉 **下载最新 DMG**  
<https://github.com/yamajinoboru/OpenClawRun/releases/latest>

- 分发格式：DMG
- 安装方式：打开 DMG，将 OpenClawRun 拖到 Applications
- 启动后：通过菜单栏图标操作 Gateway（Start / Restart / Stop）

## 3 步开始使用

1. 从上面的链接下载最新 DMG
2. 启动 OpenClawRun（菜单栏会显示图标）
3. 点击 `Start Gateway`，然后打开 `Open Chat` / `Open Dashboard`

## 功能

- 执行 `openclaw gateway start / restart / stop / status`
- 检查 localhost 连通性（`127.0.0.1:18789`）
- 每 30 秒自动后台诊断
- 自动恢复（最多 2 次）
- Emergency Recovery（强制恢复）
- 复制诊断信息
- 快速进入 Issue 反馈
- 多语言 UI（ja / en / zh-Hans / zh-Hant / pt-BR）

## FAQ

- **已启动，但还是没有反应**  
  请在菜单栏中执行 `Emergency Recovery`。

- **Stop/Restart 按钮不可用**  
  Gateway 停止时会自动禁用。请先执行 `Start Gateway`。

- **在哪里反馈问题？**  
  <https://github.com/yamajinoboru/OpenClawRun/issues/new/choose>
