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

## First 3-minute checklist

- [ ] Menu bar icon is visible
- [ ] `Gateway Status` is reachable
- [ ] `Open Chat` opens correctly
- [ ] `Open Dashboard` opens correctly

## What OpenClawRun does

- Runs `openclaw gateway start / restart / stop / status`
- Checks localhost connectivity (`127.0.0.1:18789`)
- Runs automatic background diagnostics every 30 seconds
- Performs auto-recovery (up to 2 attempts)
- Provides Emergency Recovery (forced recovery)
- Copies diagnostics info quickly
- Opens issue report flow quickly
- Supports multi-language UI (ja / en / zh-Hans / zh-Hant / pt-BR)

## What OpenClawRun does not do

- It does **not** send your chat content to external services by itself
- It does **not** require Terminal in normal daily use
- It does **not** require Screen Recording, Accessibility, or Automation permissions

## Permissions (why they are needed)

- Standard app execution permission (Gatekeeper check for downloaded apps)
- Localhost access (`127.0.0.1`) to talk to OpenClaw Gateway

If macOS blocks first launch, use: `System Settings → Privacy & Security → Open Anyway`.

## Troubleshooting (60 seconds)

1. Run `Emergency Recovery` from the menu bar
2. Retry `Start Gateway`
3. Open `Open Chat` or `Open Dashboard` again
4. If still failing, copy diagnostics info and report an issue

## FAQ

- **It launched, but things still don’t respond.**  
  Run `Emergency Recovery` from the menu bar.

- **Stop/Restart is disabled.**  
  That’s expected when Gateway is stopped. Run `Start Gateway` first.

- **Where do I report bugs?**  
  <https://github.com/yamajinoboru/OpenClawRun/issues/new/choose>
