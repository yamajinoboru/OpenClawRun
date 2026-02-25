# OpenClawRun

OpenClawRun 是一款 macOS 菜单栏应用，可让你**无需打开终端**就管理 OpenClaw Gateway。  
无论你是否是工程师，它都能让日常运维更轻松。

**语言:** [English](./README.md) | [日本語](./README.ja.md) | [简体中文](./README.zh-Hans.md) | [繁體中文](./README.zh-Hant.md) | [Português (Brasil)](./README.pt-BR.md)

![OpenClawRun 菜单截图](./assets/menu-screenshot.png)


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

## 前 3 分钟检查清单

- [ ] 菜单栏图标已显示
- [ ] 可以查看 `Gateway Status`
- [ ] `Open Chat` 可正常打开
- [ ] `Open Dashboard` 可正常打开

## 能做什么

- 执行 `openclaw gateway start / restart / stop / status`
- 检查 localhost 连通性（`127.0.0.1:18789`）
- 每 30 秒自动后台诊断
- 自动恢复（最多 2 次）
- Emergency Recovery（强制恢复）
- 复制诊断信息
- 快速进入 Issue 反馈
- 多语言 UI（ja / en / zh-Hans / zh-Hant / pt-BR）

## 不会做什么

- 不会自行把聊天内容发送到外部服务
- 日常使用不要求你打开终端
- 不要求屏幕录制、辅助功能或 Automation 权限

## 权限说明（为什么需要）

- 标准应用启动权限（下载应用的 Gatekeeper 校验）
- 访问 localhost（`127.0.0.1`）以连接 OpenClaw Gateway

如果首次启动被系统拦截，请在：
`系统设置 → 隐私与安全性 → 仍要打开`。

## 故障排查（60 秒）

1. 在菜单栏执行 `Emergency Recovery`
2. 重新执行 `Start Gateway`
3. 再次打开 `Open Chat` 或 `Open Dashboard`
4. 若仍失败，复制诊断信息并提交 Issue

## FAQ

- **已启动，但还是没有反应**  
  请在菜单栏中执行 `Emergency Recovery`。

- **Stop/Restart 按钮不可用**  
  Gateway 停止时会自动禁用。请先执行 `Start Gateway`。

- **在哪里反馈问题？**  
  <https://github.com/yamajinoboru/OpenClawRun/issues/new/choose>
