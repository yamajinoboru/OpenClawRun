# OpenClawRun

OpenClawRun 是一款 macOS 選單列應用程式，讓你**不必開啟終端機**就能管理 OpenClaw Gateway。  
不論是否為工程師，都能更輕鬆地進行日常操作。

**語言:** [English](./README.md) | [日本語](./README.ja.md) | [简体中文](./README.zh-Hans.md) | [繁體中文](./README.zh-Hant.md) | [Português (Brasil)](./README.pt-BR.md)

![OpenClawRun 選單截圖](./assets/menu-screenshot.png)


## Download

👉 **下載最新 DMG**  
<https://github.com/yamajinoboru/OpenClawRun/releases/latest>

- 發佈格式：DMG
- 安裝方式：打開 DMG，將 OpenClawRun 移到 Applications
- 啟動後：透過選單列圖示操作 Gateway（Start / Restart / Stop）

## 3 步快速開始

1. 由上方連結下載最新 DMG
2. 啟動 OpenClawRun（選單列會出現圖示）
3. 點擊 `Start Gateway`，再開啟 `Open Chat` / `Open Dashboard`

## 前 3 分鐘檢查清單

- [ ] 選單列圖示已顯示
- [ ] 可查看 `Gateway Status`
- [ ] `Open Chat` 可正常開啟
- [ ] `Open Dashboard` 可正常開啟

## 可以做什麼

- 執行 `openclaw gateway start / restart / stop / status`
- 檢查 localhost 連線（`127.0.0.1:18789`）
- 每 30 秒自動背景診斷
- 自動復原（最多 2 次）
- Emergency Recovery（強制復原）
- 複製診斷資訊
- 快速開啟 Issue 回報流程
- 多語系 UI（ja / en / zh-Hans / zh-Hant / pt-BR）

## 不會做什麼

- 不會自行把聊天內容傳送到外部服務
- 日常使用不要求開啟終端機
- 不要求螢幕錄製、輔助使用或 Automation 權限

## 權限說明（為何需要）

- 標準應用程式啟動權限（下載 App 的 Gatekeeper 驗證）
- 存取 localhost（`127.0.0.1`）以連接 OpenClaw Gateway

若首次啟動被系統阻擋，請到：
`系統設定 → 隱私權與安全性 → 仍要開啟`。

## 疑難排解（60 秒）

1. 在選單列執行 `Emergency Recovery`
2. 重新執行 `Start Gateway`
3. 再次開啟 `Open Chat` 或 `Open Dashboard`
4. 若仍失敗，請複製診斷資訊並提交 Issue

## FAQ

- **啟動後仍然沒有反應**  
  請從選單列執行 `Emergency Recovery`。

- **Stop/Restart 按鈕無法點擊**  
  Gateway 停止時會自動停用。請先執行 `Start Gateway`。

- **要在哪裡回報問題？**  
  <https://github.com/yamajinoboru/OpenClawRun/issues/new/choose>
