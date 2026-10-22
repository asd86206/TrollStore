[English](README.md) | [繁體中文](README.zh-TW.md) | [简体中文](README.zh-CN.md) | **[日本語](README.ja.md)** | [한국어](README.ko.md) | [ไทย](README.th.md) | [Tiếng Việt](README.vi.md) | [Bahasa Indonesia](README.id.md) | [Bahasa Melayu](README.ms.md) | [Filipino](README.fil.md) | [ខ្មែរ](README.km.md) | [ລາວ](README.lo.md) | [မြန်မာ](README.my.md)

> **🎯 無料の IPA リソース**
> 　　無料の IPA リソースと TrollStore の解説です。スマホ上で、無料のまま直接インストールできます。
> 　　🔗 [https://skynexa.xyz/](https://skynexa.xyz/)

---

# 🎭 TrollStore インストールガイド

**TrollStore の入れ方、対応する iOS、チップに合ったインストール方法をまとめています。**

---

## 📖 TrollStore とは

TrollStore は CoreTrust の不具合を使い、任意の IPA を恒久的に署名してインストールします。脱獄ではありません。入れたアプリは署名が維持されるため、通常のサイドロードのように期限切れになりません。

### ✨ 主な利点

- ✅ **無料**：費用はかかりません
- ✍️ **恒久署名**：インストールしたアプリは期限切れになりません
- 📱 **本体でインストール**：IPA を iPhone 上で直接インストールできます
- 🔓 **脱獄不要**：システムを脱獄する必要はありません

### 📱 対応バージョン

| 状態 | iOS バージョン | 説明 |
| :--- | :--- | :--- |
| 🟢 | iOS `14.0 beta 2` – `16.6.1`, `16.7 RC`, `17.0` | 対応 |
| 🔴 | iOS `14.0 beta 1` およびそれ以前 | 非対応 |
| 🔴 | iOS `16.7` – `16.7.11` | 非対応 |
| 🔴 | iOS `17.0.1` およびそれ以降 | 非対応 |

> **💡 ヒント**：iOS をアップデートしないでください。新しいバージョンだとこの一覧から外れ、その後は TrollStore を入れられません。

`16.7 RC`（ビルド 20H18）は対応しています。正式版の `16.7` は非対応です。インストール方法の表は [Installing TrollStore](https://ios.cfw.guide/installing-trollstore) に合わせています。同ページでは `16.7.12` – `16.7.16` も非対応です。

### 🔧 バージョンとチップ別のインストール方法

左の列で iOS のバージョンを、上の行でチップを確認し、その方法のガイドを開いてください。「対象外」はそのチップがその iOS を実行できないという意味です。「非対応」は、そこで TrollStore が使えないという意味です。

| 開始 | 終了 | arm64 (A8) | arm64 (A9–A11) | arm64e (A12–A17 / M1–M2) |
| :--- | :--- | :--- | :--- | :--- |
| 14.0 beta 1 and earlier | — | 非対応 | 非対応 | 非対応 |
| 14.0 beta 2 | 14.8.1 | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) |
| 15.0 | 15.5 beta 4 | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) |
| 15.5 | 15.5 | [TrollInstallerMDC](https://ios.cfw.guide/installing-trollstore-trollinstallermdc) | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) |
| 15.6 beta 1 | 15.6 beta 3 | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) |
| 15.6 beta 4 | 15.6.1 | [TrollInstallerMDC](https://ios.cfw.guide/installing-trollstore-trollinstallermdc) | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) |
| 15.7 | 15.7.1 | [TrollInstallerMDC](https://ios.cfw.guide/installing-trollstore-trollinstallermdc) | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) |
| 15.7.2 | 15.8.6 | [TrollMisaka](https://ios.cfw.guide/installing-trollstore-trollmisaka) | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) |
| 15.8.7 | 15.8.8 | [TrollRestore](https://ios.cfw.guide/installing-trollstore-trollrestore) | [TrollRestore](https://ios.cfw.guide/installing-trollstore-trollrestore) | 対象外 |
| 16.0 beta 1 | 16.0 beta 5 | 対象外 | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) |
| 16.0 beta 6 | 16.6.1 | 対象外 | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) |
| 16.7 RC | 16.7 RC | 対象外 | [TrollRestore](https://ios.cfw.guide/installing-trollstore-trollrestore) | [TrollRestore](https://ios.cfw.guide/installing-trollstore-trollrestore) |
| 16.7 | 16.7.16 | 対象外 | 非対応 | 非対応 |
| 17.0 beta 1 | 17.0 beta 4 | 対象外 | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | [TrollRestore](https://ios.cfw.guide/installing-trollstore-trollrestore) |
| 17.0 beta 5 | 17.0 | 対象外 | [TrollRestore](https://ios.cfw.guide/installing-trollstore-trollrestore) | [TrollRestore](https://ios.cfw.guide/installing-trollstore-trollrestore) |
| 17.0.1 and later | — | 対象外 | 非対応 | 非対応 |

出典: [ios.cfw.guide/installing-trollstore](https://ios.cfw.guide/installing-trollstore)。

### 📱 iPhone のモデルとチップ

この表で、自分の iPhone が上のどのチップ列に入るか確認できます。

| モデル | チップ |
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

A17 Pro は **A12–A17 / M1–M2** の列です。iPhone 16 以降は載せていません。TrollStore が対応しない iOS を搭載して出荷されているためです。

**iPad のモデル**

| モデル | チップ |
| :--- | :---: |
| iPad Pro (M2) | M2 |
| iPad Pro (M1) / iPad Air (5th generation) | M1 |
| iPad Air (4th generation) / iPad (10th generation) | A14 |
| iPad (9th generation) | A13 |
| iPad (8th generation) / iPad mini (5th generation) | A12 |
| iPad mini (6th generation) | A15 |

---

## 🛠️ おすすめのツール

### 🎙️ **TrollRecorder**

TrollRecorder は TrollStore 向けの通話録音アプリです。脱獄は不要で、中心的な機能は無料です。

**ダウンロード**：[GitHub](https://github.com/Lessica/TrollRecorder)

### 📊 **TrollSpeed**

TrollSpeed は、ステータスバーに現在の上りと下りの速度を表示します。

**ダウンロード**：[GitHub](https://github.com/Lessica/TrollSpeed)

---

## 🔗 リンク

- 🌐 リソースサイト：[https://skynexa.xyz/](https://skynexa.xyz/)
- 📦 このリポジトリ：[https://github.com/asd86206/TrollStore](https://github.com/asd86206/TrollStore)

---

## ⚠️ 免責事項

このガイドは教育のみを目的としています。信頼できる IPA だけをインストールしてください。インストールするアプリと、お住まいの地域の法令を守る責任はあなたにあります。
