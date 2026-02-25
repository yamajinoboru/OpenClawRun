# OpenClawRun

OpenClawRun は、OpenClaw Gateway を**ターミナルなしで**管理できる macOS メニューバーアプリです。  
エンジニア/非エンジニアを問わず、日常運用をラクにするための便利ツールです。

**言語:** [English](./README.md) | [日本語](./README.ja.md) | [简体中文](./README.zh-Hans.md) | [繁體中文](./README.zh-Hant.md) | [Português (Brasil)](./README.pt-BR.md)

![OpenClawRun メニュースクリーンショット](./assets/menu-screenshot.png)


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

## 最初の3分チェック

- [ ] メニューバーにアイコンが表示される
- [ ] `Gateway Status` が確認できる
- [ ] `Open Chat` が開ける
- [ ] `Open Dashboard` が開ける

## できること

- `openclaw gateway start / restart / stop / status` の実行
- localhost (`127.0.0.1:18789`) 疎通チェック
- 30秒ごとのバックグラウンド診断
- 自動復旧（最大2回）
- Emergency Recovery（強制復旧）
- 診断情報コピー
- Issue報告導線
- 多言語UI（ja / en / zh-Hans / zh-Hant / pt-BR）

## しないこと

- チャット内容を勝手に外部送信しない
- 日常利用でターミナル操作を必須にしない
- 画面収録 / アクセシビリティ / Automation 権限を要求しない

## 権限について（なぜ必要か）

- 通常のアプリ実行権限（ダウンロードアプリのGatekeeper確認）
- OpenClaw Gateway と通信するための localhost (`127.0.0.1`) アクセス

初回起動がブロックされた場合は、
`システム設定 → プライバシーとセキュリティ → このまま開く` を選んでください。

## トラブル時の60秒手順

1. メニューバーから `Emergency Recovery` を実行
2. `Start Gateway` を再実行
3. `Open Chat` または `Open Dashboard` を再オープン
4. まだ解決しなければ診断情報をコピーして Issue 報告

## FAQ

- **起動したのにうまく反応しない**  
  メニューバーから `Emergency Recovery` を実行してください。

- **Stop/Restart が押せない**  
  Gateway停止中は無効になります。先に `Start Gateway` を実行してください。

- **不具合報告先は？**  
  <https://github.com/yamajinoboru/OpenClawRun/issues/new/choose>
