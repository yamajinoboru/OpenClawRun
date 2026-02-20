# OpenClawRun

OpenClawRun は、OpenClaw Gateway をターミナル操作なしで扱うための macOS メニューバーアプリです。

## 配布方針
- このリポジトリは **配布・サポート専用** です。
- ソースコードは非公開（closed source）で運用しています。
- バイナリは [Releases](../../releases) から配布します。

## ダウンロード
1. [Releases](../../releases) を開く
2. 最新の `OpenClawRun-*.dmg` をダウンロード
3. アプリを Applications にドラッグ

## 不具合報告
不具合は [Issues](../../issues/new/choose) へお願いします。

報告時にあると助かる情報:
- macOSバージョン
- OpenClawRunバージョン
- OpenClawバージョン（`openclaw --version`）
- OpenClawRunの `Copy Diagnostics` で取得した内容

## 既知の前提
- OpenClaw Gateway のデフォルトポート（`127.0.0.1:18789`）を使用
- macOS 14+
