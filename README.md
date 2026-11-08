<h1 align="center">Hi, I'm Vlad 👋</h1>

<p align="center">
  <b>Android & Systems Developer from Ukraine 🇺🇦</b><br>
  Crafting fast, low-footprint, privacy-first tools for Android, embedded systems, and the web.<br>
  Zero telemetry · Minimal dependencies · Direct hardware & OS framework integration.
</p>

<p align="center">
  <a href="https://t.me/vladgba"><img src="https://img.shields.io/badge/Telegram-@vladgba-26A5E4?style=flat&logo=telegram&logoColor=white" alt="Telegram"></a>
  <a href="mailto:vladgba@gmail.com"><img src="https://img.shields.io/badge/Email-vladgba@gmail.com-EA4335?style=flat&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://matrix.to/#/@vladgba:matrix.org"><img src="https://img.shields.io/badge/Matrix-000000?style=flat&logo=matrix&logoColor=white" alt="Matrix"></a>
  <a href="https://discord.com/users/vladgba"><img src="https://img.shields.io/badge/Discord-5865F2?style=flat&logo=discord&logoColor=white" alt="Discord"></a>
  <a href="https://www.linkedin.com/in/vladyslav-tishyn-aa55932b2"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://github.com/vladgba"><img src="https://img.shields.io/badge/GitHub-vladgba-181717?style=flat&logo=github&logoColor=white" alt="GitHub"></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=flat&logo=kotlin&logoColor=white" alt="Kotlin">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white" alt="Java">
  <img src="https://img.shields.io/badge/Android%20NDK%20%2F%20C++-00599C?style=flat&logo=cplusplus&logoColor=white" alt="C++">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/PHP%208-777BB4?style=flat&logo=php&logoColor=white" alt="PHP">
  <img src="https://img.shields.io/badge/JavaScript%20%2F%20TS-F7DF1E?style=flat&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnu-bash&logoColor=white" alt="Bash">
</p>

---

## 🧭 Principles & Engineering Philosophy

- **Zero Unnecessary Dependencies:** Standard libraries and direct OS frameworks over heavy third-party bloat.
- **Privacy by Architecture:** Strict permission isolation (e.g. apps without internet permissions stay offline).
- **Extreme Efficiency:** Instant startup times, lean APK binaries, low battery impact, and zero trackers.
- **System Control & Transparency:** Clean, inspectable architectures built for power users.

---

## 📱 The p* Android Ecosystem

A cohesive suite of native Android applications engineered around shared `pUI` styling, modular Gradle setups, and direct OS framework interaction.

| App | Description | GitHub | Site / Docs |
|:---|:---|:---:|:---:|
| **pKeyboard** | Gestures, custom layouts, macro scripting, clipboard history, theme engine. Voice recognition is completely isolated in an optional add-on. | [GitHub](https://github.com/vladgba/pKeyboard) | [View](https://zcxv.cc/apps/pKeyboard/) |
| **pFiles** | Dual-pane file manager, built-in code editor, Markdown viewer, hex editor, large-file analyzer, and zip engine. | [GitHub](https://github.com/vladgba/pFiles) | [View](https://zcxv.cc/apps/pFiles/) |
| **pLauncher** | Clean 2D page matrix home screen with free-form widget placement, folder hierarchies, and edge gestures. | [GitHub](https://github.com/vladgba/pLauncher) | [View](https://zcxv.cc/apps/pLauncher/) |
| **pShare** | Offline and cross-network transfers over Wi-Fi, Wi-Fi Direct, Bluetooth, local hotspot, and visual QR code slideshows. | [GitHub](https://github.com/vladgba/pShare) | [View](https://zcxv.cc/apps/pShare/) |
| **pGPS** | GNSS constellation diagnostics, 3D/AR sky projection, signal integrity auditing, track recording, and waypoint navigation. | [GitHub](https://github.com/vladgba/pGPS) | [View](https://zcxv.cc/apps/pGPS/) |
| **pSMS** | Secure, offline SMS manager with regex spam rules, conversation tags, OTP extraction, and zero internet permission. | [GitHub](https://github.com/vladgba/pSMS) | [View](https://zcxv.cc/apps/pSMS/) |
| **pCalendar** | Fast calendar, task planner, and agenda engine with customizable home-screen widgets. | [GitHub](https://github.com/vladgba/pCalendar) | [View](https://zcxv.cc/apps/pCalendar/) |
| **pCalc** | Calculator supporting programmable formula keys, trigonometric solvers, history tape, and function graphing. | [GitHub](https://github.com/vladgba/pCalc) | [View](https://zcxv.cc/apps/pCalc/) |
| **pScanner** | High-speed offline QR and 1D/2D barcode reader/generator with native Honeywell hardware scanner support. | [GitHub](https://github.com/vladgba/pScanner) | [View](https://zcxv.cc/apps/pScanner/) |
| **pDimmer** | Hardware screen backlight override allowing dimming below system minimums via Quick Settings tiles and overlay shaders. | [GitHub](https://github.com/vladgba/pDimmer) | [View](https://zcxv.cc/apps/pDimmer/) |
| **pUtils** | Integrated sensor toolkit: compass, digital spirit level, precision ruler, GPS speedometer, and hardware telemetry. | [GitHub](https://github.com/vladgba/pUtils) | [View](https://zcxv.cc/apps/pUtils/) |

---

## 🛠 Recent Engineering Milestones

- **`pKeyboard` Voice Isolation:** Refactored voice input into an optional, isolated `pKeyboard Voice` add-on, keeping the core IME binary completely free of microphone and network permissions. Added dedicated icons for prebuilt layouts and themes.
- **Universal Android 5 Compatibility (API 21-22):** Hardened theme color pipelines, `pColor` calculations, and translucent status bars across all `p*` apps, eliminating crashes on legacy Android releases.
- **Unified `pUI` & Shared Gradle Engine:** Extracted `pUI` common styling, standardized About dialogs, and automated GitHub Actions release APK generators across repositories via [`configs`](https://github.com/vladgba/configs).
- **`pShare` Protocol Expansion:** Upgraded QR visual transfer speed, memory buffering, folder hierarchy replication, and bidirectional sync tests.
- **`pFiles` Enhancements:** Deployed mobile roadmap modules, full code viewer activities, and Markdown preview directly within file trees.

---

## 🌐 Web & Open Tooling

- [**Markdown Project Hub (SimpleMd4PHP)**](https://github.com/vladgba/simplemd4php) — Ultra-fast, single-file Markdown website engine written in modern PHP. Features GitHub Flavored Markdown (GFM), heading anchors, conditional HTTP cache validation (ETag/304), breadcrumb navigation, and in-memory ZIP / Git bundle file browsing without server-side archive extraction.
- [**configs**](https://github.com/vladgba/configs) — Reusable configuration templates, `pUI` shared styling, and automated GitHub Actions build workflows for Android and PHP.
- [**php-cache-proxy**](https://github.com/vladgba/php-cache-proxy) — Modular caching reverse proxy split into `PageCache`, `ProxyTarget`, and `UrlRewriter` with POST isolation and automated PHP syntax linting.
- Earlier open work includes [Back2source](https://github.com/vladgba/Back2source), [ShortURL](https://github.com/vladgba/ShortURL), and [termux-py-utils](https://github.com/vladgba/termux-py-utils).

---

## 🔬 Core Interests & Technical Domains

- **Android System Internals:** WindowManager overlays, InputMethodService pipelines, accessibility services, IPC via Binder, and custom ROM integration.
- **Embedded Runtimes:** Embedding lightweight JS engines ([QuickJS](https://bellard.org/quickjs/)) and micro-scripting into native Android and C++ apps.
- **Hardware & Microcontrollers:** Firmware hacking on ESP32, STM32, Arduino, and Raspberry Pi Zero nodes.
- **Decentralized & Local-First:** Offline-first architectures, encrypted peer communication, and distributed device sync.

---

## 📊 Activity & Statistics

<p align="center">
  <img src="https://github-stats-extended.vercel.app/api?username=vladgba&hide_rank=true&hide_title=true&show=reviews%2Cdiscussions_started%2Cdiscussions_answered%2Cprs_merged%2Cprs_merged_percentage%2Cprs_commented%2Cprs_reviewed%2Cissues_commented%2Ccontributions%2Call_time_contribs&show_icons=true&include_all_commits=true&disable_animations=true&theme=light_github" alt="GitHub Stats">
</p>
<p align="center">
  <img src="https://github-stats-extended.vercel.app/api/top-langs?username=vladgba&hide_title=true&langs_count=10&hide_values=true&disable_animations=true&theme=light_github" alt="Top Languages">
</p>
