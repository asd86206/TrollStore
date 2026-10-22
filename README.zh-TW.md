[English](README.md) | **[繁體中文](README.zh-TW.md)** | [简体中文](README.zh-CN.md) | [日本語](README.ja.md) | [한국어](README.ko.md) | [ไทย](README.th.md) | [Tiếng Việt](README.vi.md) | [Bahasa Indonesia](README.id.md) | [Bahasa Melayu](README.ms.md) | [Filipino](README.fil.md) | [ខ្មែរ](README.km.md) | [ລາວ](README.lo.md) | [မြန်မာ](README.my.md)

> **🎯 免費 IPA 資源**
> 　　免費 IPA 資源與 TrollStore 教學，可直接在手機上免費安裝。
> 　　🔗 [https://skynexa.xyz/](https://skynexa.xyz/)

---

# 🎭 TrollStore 安裝指南

**說明如何安裝 TrollStore、哪些 iOS 版本支援，以及哪一種方式對應你的晶片。**

---

## 📖 什麼是 TrollStore？

TrollStore 利用 CoreTrust 漏洞，永久簽名並安裝任何 IPA。它不是越獄。裝好的 App 會維持簽名，不會像一般側載那樣到期失效。

### ✨ 核心優勢

- ✅ **完全免費**：不需要付任何費用
- ✍️ **永久簽名**：安裝後的 App 不會過期
- 📱 **在裝置上安裝**：直接在 iPhone 上安裝 IPA
- 🔓 **無需越獄**：不需要越獄系統

### 📱 支援的系統版本

| 狀態 | 系統版本 | 說明 |
| :--- | :--- | :--- |
| 🟢 | iOS `14.0 beta 2` – `16.6.1`, `16.7 RC`, `17.0` | 支援 |
| 🔴 | iOS `14.0 beta 1` 與更早版本 | 不支援 |
| 🔴 | iOS `16.7` – `16.7.11` | 不支援 |
| 🔴 | iOS `17.0.1` 與之後的版本 | 不支援 |

> **💡 小提醒**：不要更新 iOS。系統一更新，手機就可能離開這份清單，之後便無法安裝 TrollStore。

`16.7 RC`（組建 20H18）可以安裝，正式版 `16.7` 則不行。安裝方式表依照 [Installing TrollStore](https://ios.cfw.guide/installing-trollstore)，該頁也將 `16.7.12` – `16.7.16` 標為不支援。

### 🔧 依版本與晶片選擇安裝方式

在左側欄找到 iOS 版本，在上方找到晶片，再打開該方式的指南。「不適用」表示該晶片無法運行這個 iOS 版本。「不支援」表示 TrollStore 在那裡無法使用。

| 起始版本 | 結束版本 | arm64 (A8) | arm64 (A9–A11) | arm64e (A12–A17 / M1–M2) |
| :--- | :--- | :--- | :--- | :--- |
| 14.0 beta 1 and earlier | — | 不支援 | 不支援 | 不支援 |
| 14.0 beta 2 | 14.8.1 | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) |
| 15.0 | 15.5 beta 4 | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) |
| 15.5 | 15.5 | [TrollInstallerMDC](https://ios.cfw.guide/installing-trollstore-trollinstallermdc) | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) |
| 15.6 beta 1 | 15.6 beta 3 | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) |
| 15.6 beta 4 | 15.6.1 | [TrollInstallerMDC](https://ios.cfw.guide/installing-trollstore-trollinstallermdc) | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) |
| 15.7 | 15.7.1 | [TrollInstallerMDC](https://ios.cfw.guide/installing-trollstore-trollinstallermdc) | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) |
| 15.7.2 | 15.8.6 | [TrollMisaka](https://ios.cfw.guide/installing-trollstore-trollmisaka) | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) |
| 15.8.7 | 15.8.8 | [TrollRestore](https://ios.cfw.guide/installing-trollstore-trollrestore) | [TrollRestore](https://ios.cfw.guide/installing-trollstore-trollrestore) | 不適用 |
| 16.0 beta 1 | 16.0 beta 5 | 不適用 | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) |
| 16.0 beta 6 | 16.6.1 | 不適用 | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) |
| 16.7 RC | 16.7 RC | 不適用 | [TrollRestore](https://ios.cfw.guide/installing-trollstore-trollrestore) | [TrollRestore](https://ios.cfw.guide/installing-trollstore-trollrestore) |
| 16.7 | 16.7.16 | 不適用 | 不支援 | 不支援 |
| 17.0 beta 1 | 17.0 beta 4 | 不適用 | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | [TrollRestore](https://ios.cfw.guide/installing-trollstore-trollrestore) |
| 17.0 beta 5 | 17.0 | 不適用 | [TrollRestore](https://ios.cfw.guide/installing-trollstore-trollrestore) | [TrollRestore](https://ios.cfw.guide/installing-trollstore-trollrestore) |
| 17.0.1 and later | — | 不適用 | 不支援 | 不支援 |

資料來源：[ios.cfw.guide/installing-trollstore](https://ios.cfw.guide/installing-trollstore)。

### 📱 iPhone 型號與晶片

用這張表確認你的 iPhone 對應上方哪一個晶片欄。

| 型號 | 晶片 |
| :--- | :---: |
| iPhone 15 Pro / Pro Max | A17 Pro |
| iPhone 15 / 15 Plus | A16 |
| iPhone 14 Pro / Pro Max | A16 |
| iPhone 14 / 14 Plus | A15 |
| iPhone SE (3rd generation) | A15 |
| iPhone 13 / 13 mini / 13 Pro / 13 Pro Max | A15 |
| iPhone 12 / 12 mini / 12 Pro / 12 Pro Max | A14 |
| iPhone SE (2nd generation) | A13 |
| iPhone 11 / 11 Pro / 11 Pro Max | A13 |
| iPhone XS / XS Max / XR | A12 |
| iPhone X / 8 / 8 Plus | A11 |
| iPhone 7 / 7 Plus | A10 |
| iPhone SE (1st generation) / 6s / 6s Plus | A9 |
| iPhone 6 / 6 Plus | A8 |

A17 Pro 屬於 **A12–A17 / M1–M2** 這一欄。iPhone 16 與後續機型未列入，因為出廠時的 iOS 版本不受 TrollStore 支援。

**iPad 型號**

| 型號 | 晶片 |
| :--- | :---: |
| iPad Pro (M2) | M2 |
| iPad Pro (M1) / iPad Air (5th generation) | M1 |
| iPad Air (4th generation) / iPad (10th generation) | A14 |
| iPad (9th generation) | A13 |
| iPad (8th generation) / iPad mini (5th generation) | A12 |
| iPad mini (6th generation) | A15 |

---

## 🛠️ 推薦工具

### 🎙️ **TrollRecorder**

TrollRecorder 是專為 TrollStore 設計的通話錄音工具。不需要越獄，核心功能免費。

**下載**：[GitHub](https://github.com/Lessica/TrollRecorder)

### 📊 **TrollSpeed**

TrollSpeed 在狀態列顯示目前的上傳與下載速度。

**下載**：[GitHub](https://github.com/Lessica/TrollSpeed)

---

## 🔗 連結

- 🌐 資源站：[https://skynexa.xyz/](https://skynexa.xyz/)
- 📦 這個儲存庫：[https://github.com/asd86206/TrollStore](https://github.com/asd86206/TrollStore)

---

## ⚠️ 免責聲明

本指南僅供教育用途。請只安裝你信任的 IPA。你必須自行負責所安裝的 App，並遵守所在地的法律。
