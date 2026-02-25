# OpenClawRun

OpenClawRun is a macOS menu bar app for managing OpenClaw Gateway **without opening Terminal**.
It’s a convenience tool for everyday operations, whether you’re technical or not.

**Languages:** [English](./README.md) | [日本語](./README.ja.md) | [简体中文](./README.zh-Hans.md) | [繁體中文](./README.zh-Hant.md) | [Português (Brasil)](./README.pt-BR.md)

## Download

👉 **Get the latest DMG**  
<https://github.com/yamajinoboru/OpenClawRun/releases/latest>

- Distribution format: DMG
- Install: Open the DMG and move OpenClawRun to Applications
- After launch: Use the menu bar icon to control Gateway (Start / Restart / Stop)

## Quick Start (3 steps)

1. Download the latest DMG from the link above
2. Launch OpenClawRun (menu bar icon appears)
3. Click `Start Gateway`, then open `Open Chat` / `Open Dashboard`

## What you can do

- Run `openclaw gateway start / restart / stop / status`
- Check localhost connectivity (`127.0.0.1:18789`)
- Automatic background diagnostics every 30 seconds
- Auto-recovery (up to 2 attempts)
- Emergency Recovery (forced recovery)
- Copy diagnostics info
- Open issue report flow quickly
- Multi-language UI (ja / en / zh-Hans / zh-Hant / pt-BR)

## FAQ

- **It launched, but things still don’t respond.**  
  Run `Emergency Recovery` from the menu bar.

- **Stop/Restart is disabled.**  
  That’s expected when Gateway is stopped. Run `Start Gateway` first.

- **Where do I report bugs?**  
  <https://github.com/yamajinoboru/OpenClawRun/issues/new/choose>
