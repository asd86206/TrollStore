[English](README.md) | [繁體中文](README.zh-TW.md) | [简体中文](README.zh-CN.md) | [日本語](README.ja.md) | [한국어](README.ko.md) | [ไทย](README.th.md) | [Tiếng Việt](README.vi.md) | [Bahasa Indonesia](README.id.md) | [Bahasa Melayu](README.ms.md) | **[Filipino](README.fil.md)** | [ខ្មែរ](README.km.md) | [ລາວ](README.lo.md) | [မြန်မာ](README.my.md)

> **🎯 Libreng IPA resources**
> 　　Libreng IPA resources at mga tutorial sa TrollStore. I-install nang direkta sa telepono, libre.
> 　　🔗 [https://skynexa.xyz/](https://skynexa.xyz/)

---

# 🎭 Gabay sa pag-install ng TrollStore

**Paano i-install ang TrollStore, aling bersyon ng iOS ang suportado, at aling paraan ang tumutugma sa chip ng telepono.**

---

## 📖 Ano ang TrollStore?

Ginagamit ng TrollStore ang CoreTrust bug para permanenteng i-sign at i-install ang anumang IPA. Hindi ito jailbreak. Nanatiling naka-sign ang mga naka-install na app, kaya hindi sila nag-e-expire gaya ng karaniwang sideload.

### ✨ Mga pangunahing bentahe

- ✅ **Libre**: walang babayaran
- ✍️ **Permanenteng pag-sign**: hindi nag-e-expire ang mga naka-install na app
- 📱 **I-install sa telepono**: direktang i-install ang IPA sa iPhone
- 🔓 **Walang jailbreak**: hindi naja-jailbreak ang sistema

### 📱 Mga suportadong bersyon

| Katayuan | Bersyon ng iOS | Tala |
| :--- | :--- | :--- |
| 🟢 | iOS `14.0 beta 2` – `16.6.1`, `16.7 RC`, `17.0` | Suportado |
| 🔴 | iOS `14.0 beta 1` at mas luma | Hindi suportado |
| 🔴 | iOS `16.7` – `16.7.11` | Hindi suportado |
| 🔴 | iOS `17.0.1` at mas bago | Hindi suportado |

> **💡 Tip**: Huwag i-update ang iOS. Maaaring mailabas ng mas bagong bersyon ang telepono sa listahang ito, at hindi mo na mai-install ang TrollStore pagkatapos noon.

Suportado ang `16.7 RC` (build 20H18). Hindi suportado ang pinal na `16.7`. Sumusunod ang talahanayan ng paraan sa [Installing TrollStore](https://ios.cfw.guide/installing-trollstore). Hindi rin suportado roon ang `16.7.12` – `16.7.16`.

### 🔧 Paraan ng pag-install ayon sa bersyon at chip

Hanapin ang bersyon ng iOS sa kaliwang hanay at ang chip sa itaas, tapos buksan ang gabay ng paraang iyon. Ang “Hindi naaangkop” ay nangangahulugang hindi kayang patakbuhin ng chip na iyon ang bersyon ng iOS na iyon. Ang “Hindi suportado” ay nangangahulugang hindi gagana roon ang TrollStore.

| Mula | Hanggang | arm64 (A8) | arm64 (A9–A11) | arm64e (A12–A17 / M1–M2) |
| :--- | :--- | :--- | :--- | :--- |
| 14.0 beta 1 and earlier | — | Hindi suportado | Hindi suportado | Hindi suportado |
| 14.0 beta 2 | 14.8.1 | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) |
| 15.0 | 15.5 beta 4 | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) |
| 15.5 | 15.5 | [TrollInstallerMDC](https://ios.cfw.guide/installing-trollstore-trollinstallermdc) | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) |
| 15.6 beta 1 | 15.6 beta 3 | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) |
| 15.6 beta 4 | 15.6.1 | [TrollInstallerMDC](https://ios.cfw.guide/installing-trollstore-trollinstallermdc) | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) |
| 15.7 | 15.7.1 | [TrollInstallerMDC](https://ios.cfw.guide/installing-trollstore-trollinstallermdc) | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) |
| 15.7.2 | 15.8.6 | [TrollMisaka](https://ios.cfw.guide/installing-trollstore-trollmisaka) | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) |
| 15.8.7 | 15.8.8 | [TrollRestore](https://ios.cfw.guide/installing-trollstore-trollrestore) | [TrollRestore](https://ios.cfw.guide/installing-trollstore-trollrestore) | Hindi naaangkop |
| 16.0 beta 1 | 16.0 beta 5 | Hindi naaangkop | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) |
| 16.0 beta 6 | 16.6.1 | Hindi naaangkop | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) |
| 16.7 RC | 16.7 RC | Hindi naaangkop | [TrollRestore](https://ios.cfw.guide/installing-trollstore-trollrestore) | [TrollRestore](https://ios.cfw.guide/installing-trollstore-trollrestore) |
| 16.7 | 16.7.16 | Hindi naaangkop | Hindi suportado | Hindi suportado |
| 17.0 beta 1 | 17.0 beta 4 | Hindi naaangkop | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | [TrollRestore](https://ios.cfw.guide/installing-trollstore-trollrestore) |
| 17.0 beta 5 | 17.0 | Hindi naaangkop | [TrollRestore](https://ios.cfw.guide/installing-trollstore-trollrestore) | [TrollRestore](https://ios.cfw.guide/installing-trollstore-trollrestore) |
| 17.0.1 and later | — | Hindi naaangkop | Hindi suportado | Hindi suportado |

Pinagmulan: [ios.cfw.guide/installing-trollstore](https://ios.cfw.guide/installing-trollstore).

### 📱 Model ng iPhone at chip

Gamitin ang talahanayang ito para makita kung aling hanay ng chip sa itaas ang tumutugma sa iPhone mo.

| Model | Chip |
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

Nasa hanay na **A12–A17 / M1–M2** ang A17 Pro. Wala rito ang iPhone 16 pataas dahil lumabas ang mga iyon sa iOS na hindi suportado ng TrollStore.

**Mga model ng iPad**

| Model | Chip |
| :--- | :---: |
| iPad Pro (M2) | M2 |
| iPad Pro (M1) / iPad Air (5th generation) | M1 |
| iPad Air (4th generation) / iPad (10th generation) | A14 |
| iPad (9th generation) | A13 |
| iPad (8th generation) / iPad mini (5th generation) | A12 |
| iPad mini (6th generation) | A15 |

---

## 🛠️ Mga inirerekomendang tool

### 🎙️ **TrollRecorder**

Ang TrollRecorder ay call recorder para sa TrollStore. Walang jailbreak. Libre ang mga pangunahing feature.

**I-download**: [GitHub](https://github.com/Lessica/TrollRecorder)

### 📊 **TrollSpeed**

Ipinapakita ng TrollSpeed ang kasalukuyang bilis ng upload at download sa status bar.

**I-download**: [GitHub](https://github.com/Lessica/TrollSpeed)

---

## 🔗 Mga link

- 🌐 Site ng mga resource: [https://skynexa.xyz/](https://skynexa.xyz/)
- 📦 Ang repository na ito: [https://github.com/asd86206/TrollStore](https://github.com/asd86206/TrollStore)

---

## ⚠️ Paunawa

Para sa edukasyon lamang ang gabay na ito. Mag-install lang ng IPA na pinagkakatiwalaan mo. Ikaw ang may pananagutan sa mga app na ini-install mo at sa pagsunod sa batas sa lugar mo.
