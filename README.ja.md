# OpenClawRun

OpenClawRun は、OpenClaw Gateway を**ターミナルなしで**管理できる macOS メニューバーアプリです。  
エンジニア/非エンジニアを問わず、日常運用をラクにするための便利ツールです。

**言語:** [English](./README.md) | [日本語](./README.ja.md) | [简体中文](./README.zh-Hans.md) | [繁體中文](./README.zh-Hant.md) | [Português (Brasil)](./README.pt-BR.md)

## Download

👉 **最新DMGをダウンロード**  
<https://github.com/yamajinoboru/OpenClawRun/releases/latest>

- 配布形式: DMG
- インストール: DMGを開いて OpenClawRun を Applications に移動
- 起動後: メニューバーから Gateway を操作（Start / Restart / Stop）

## 3ステップで使う

1. 上のリンクから最新DMGをダウンロード
2. OpenClawRunを起動（メニューバーにアイコン表示）
3. `Start Gateway` を押し、`Open Chat` / `Open Dashboard` を開く

## できること

- `openclaw gateway start / restart / stop / status` の実行
- localhost (`127.0.0.1:18789`) 疎通チェック
- 30秒ごとのバックグラウンド診断
- 自動復旧（最大2回）
- Emergency Recovery（強制復旧）
- 診断情報コピー
- Issue報告導線
- 多言語UI（ja / en / zh-Hans / zh-Hant / pt-BR）

## FAQ

- **起動したのにうまく反応しない**  
  メニューバーから `Emergency Recovery` を実行してください。

- **Stop/Restart が押せない**  
  Gateway停止中は無効になります。先に `Start Gateway` を実行してください。

- **不具合報告先は？**  
  <https://github.com/yamajinoboru/OpenClawRun/issues/new/choose>
