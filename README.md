<div align="center">

# Cornch

### Embedded Systems & Firmware · Async Rust on bare metal

[![GitHub](https://img.shields.io/badge/GitHub-cornch--k-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/cornch-k)
[![Email](https://img.shields.io/badge/ditto__eevee%40icloud.com-D14836?style=for-the-badge&logo=maildotru&logoColor=white)](mailto:ditto_eevee@icloud.com)
[![Profile Views](https://komarev.com/ghpvc/?username=cornch-k&style=for-the-badge&color=7F5AF0&label=PROFILE+VIEWS)](https://github.com/cornch-k)

> Also known as **NAV** in online communities

</div>

---

## 🧑‍💻 About Me

I'm a **3rd-year Software Engineering** student at **[Korea Aerospace University](http://sw.kau.ac.kr/)**, drawn to the boundary where **silicon meets code** — embedded systems, firmware engineering, and computer architecture. I enjoy bringing modern async runtimes onto resource-constrained MCUs, and feel most at home inside `memory.x`, datasheets, and protocol stacks.

`💻 Embedded Firmware` &nbsp;·&nbsp; `🔧 Low-level Systems` &nbsp;·&nbsp; `🇯🇵 JLPT N1 in preparation`

---

## 🚀 What I'm Working On

### 🔧 Embedded Systems Internship &nbsp;·&nbsp; *Jan 2026, Mar 2026 – Jun 2026*

> **Re-engineering a legacy C cycling-sensor firmware into idiomatic async Rust on a custom nRF52840 board.**

| Area | Stack |
| :--- | :--- |
| **Async runtime** | `Embassy` — `embassy-nrf`, `embassy-executor`, `embassy-time` |
| **Wireless** | Dual **BLE + ANT** stack via [`nrf-softdevice`](https://github.com/embassy-rs/nrf-softdevice) on top of Nordic SoftDevice |
| **HMI** | ST7789 LCD + capacitive touch, rendered through `embedded-graphics` |
| **On-board sensors** | 3-axis accelerometer · barometer · gyroscope, sharing a single SPI bus |
| **Systems work** | Memory layout (SoftDevice + bootloader + app), OTA DFU, persistent storage for bonding & settings |

---

## 🛠️ Tech Stack

**Languages**

<p align="left">
<img src="https://skillicons.dev/icons?i=c,cpp,rust,cs,python,kotlin" alt="Languages"/>
</p>

**Tools**

<p align="left">
<img src="https://skillicons.dev/icons?i=git,github,vscode" alt="Tools"/>
</p>

**Embedded Stack**

![Nordic nRF52840](https://img.shields.io/badge/Nordic_nRF52840-00A9CE?style=flat-square&logoColor=white)
![STM32F411RE](https://img.shields.io/badge/STM32F411RE-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white)
![Embassy](https://img.shields.io/badge/Embassy-async_Rust-DEA584?style=flat-square&logo=rust&logoColor=white)
![nrf-softdevice](https://img.shields.io/badge/nrf--softdevice-DEA584?style=flat-square&logo=rust&logoColor=white)
![BLE GATT](https://img.shields.io/badge/BLE_GATT-0082FC?style=flat-square&logo=bluetooth&logoColor=white)
![ANT+](https://img.shields.io/badge/ANT%2B-D71920?style=flat-square)
![embedded-graphics](https://img.shields.io/badge/embedded--graphics-DEA584?style=flat-square&logo=rust&logoColor=white)
![probe-rs](https://img.shields.io/badge/probe--rs-000000?style=flat-square)
![SEGGER J-Link](https://img.shields.io/badge/SEGGER_J--Link-A8252C?style=flat-square)
![RTT](https://img.shields.io/badge/RTT_logging-555555?style=flat-square)
![no_std](https://img.shields.io/badge/no__std-DEA584?style=flat-square&logo=rust&logoColor=white)

---

## 📚 Currently Learning

- **Embedded Rust** — Embassy, `nrf-softdevice`, `memory.x` layout, async ISR patterns, `no_std` ergonomics
- **STM32F4 family** — peripherals, RTOS concepts, HAL-level drivers
- **Japanese** — 目標: **JLPT N1**

---

## 💡 Interests

`Embedded Systems & Firmware` &nbsp;·&nbsp; `Computer Architecture` &nbsp;·&nbsp; `Hardware-Software Integration & IoT` &nbsp;·&nbsp; `Software Design Patterns` &nbsp;·&nbsp; `Japanese Language & Culture`

---

## 📊 GitHub Stats

<p align="center">
<img height="170" src="https://github-readme-stats.vercel.app/api?username=cornch-k&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true&hide_rank=true" alt="GitHub Stats"/>
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=cornch-k&layout=compact&theme=tokyonight&hide_border=true&langs_count=4" alt="Top Languages"/>
</p>

---

<details>
<summary><b>🇯🇵 日本語版 / Japanese Version &nbsp;(click to expand)</b></summary>

<br>

# はじめまして、**Cornch（コンチ）** です

> オンラインでは **NAV（ナブ）** として活動しています

## 自己紹介

[韓国航空大学](http://sw.kau.ac.kr/) ソフトウェア工学科 3 年生。**シリコンとコードの境界** — 組み込みシステム、ファームウェア工学、コンピュータアーキテクチャに惹かれています。リソース制約のある MCU に最新の非同期ランタイムを持ち込み、`memory.x`、データシート、プロトコルスタックの中で時間を過ごすのが好きです。

`💻 組み込みファームウェア` &nbsp;·&nbsp; `🔧 低レベルシステム` &nbsp;·&nbsp; `🇯🇵 JLPT N1 学習中`

## 🚀 現在取り組んでいるプロジェクト

### 🔧 組み込みシステムインターンシップ &nbsp;·&nbsp; *2026 年 1 月、2026 年 3 月 - 6 月*

> **サイクリングセンサーのレガシー C ファームウェアを、nRF52840 カスタムボード上の慣用的な非同期 Rust に再構築中。**

| 領域 | スタック |
| :--- | :--- |
| **非同期ランタイム** | `Embassy` — `embassy-nrf`, `embassy-executor`, `embassy-time` |
| **無線** | [`nrf-softdevice`](https://github.com/embassy-rs/nrf-softdevice) と Nordic SoftDevice による **BLE + ANT** デュアルスタック |
| **HMI** | ST7789 LCD と静電容量タッチを `embedded-graphics` で描画 |
| **オンボードセンサー** | 3 軸加速度センサー · 気圧センサー · ジャイロセンサーを単一 SPI バスで接続 |
| **システムワーク** | SoftDevice + ブートローダー + アプリのメモリ配置、OTA DFU、ペアリング情報・設定の永続化 |

## 🛠️ 技術スタック

上記の英語版に同じです (Languages / Tools / Embedded Stack)。

## 📚 現在学習中

- **組み込み Rust** — Embassy、`nrf-softdevice`、`memory.x` レイアウト、非同期 ISR パターン、`no_std` の作法
- **STM32F4 ファミリー** — ペリフェラル、RTOS の概念、HAL レベルのドライバ
- **日本語** — 目標: **JLPT N1**

## 💡 興味分野

`組み込みシステム＆ファームウェア` &nbsp;·&nbsp; `コンピュータアーキテクチャ` &nbsp;·&nbsp; `ハードウェア・ソフトウェア統合＆IoT` &nbsp;·&nbsp; `ソフトウェアデザインパターン` &nbsp;·&nbsp; `日本語＆日本文化`

</details>

---

<div align="center">

📫 **Reach me at** &nbsp;·&nbsp; [ditto_eevee@icloud.com](mailto:ditto_eevee@icloud.com) &nbsp;·&nbsp; [github.com/cornch-k](https://github.com/cornch-k)

</div>
