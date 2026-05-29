# 💻 Sulse — Premium System Monitor & Telemetry for macOS

<p align="center">
  <img src="AppIcon.png" width="128" height="128" alt="Sulse App Icon">
</p>

<p align="center">
  <strong>Sulse</strong> is a simple, lightweight, and beautiful system monitor designed exclusively for macOS (Apple Silicon). It shows you in real-time how your Mac is feeling, keeping all vital telemetry at your fingertips with a gorgeous, modern design.
</p>

<p align="center">
  <a href="https://github.com/tepliy/sulse-app/releases/latest">
    <img src="https://img.shields.io/github/v/release/tepliy/sulse-app?color=4fc08d&label=Download%20Latest%20.DMG&style=for-the-badge" alt="Download Latest DMG">
  </a>
</p>

---

## ✨ Features

*   **⚡️ Complete CPU & GPU Insights**: Monitor real-time loads, speeds, cluster activity (Performance & Efficiency cores), and precise temperatures.
*   **🔋 Smart Battery Telemetry**: View charge levels, battery health (capacity), cycle counts, charging speeds, and temperature.
*   **🧠 Memory & Storage Health**: Keep track of RAM usage, memory pressure, active/wired categories, and drive read/write speeds.
*   **🌐 Network & Connections**: Instant access to upload/download speeds, active connection info, internal/external IPs, signal strength, and VPN status.
*   **❄️ Cooling & Sensors**: Check fan speeds, ambient light sensor readings, and system thermal pressure.
*   **🎨 Stunning Design**: Beautiful glassmorphic overlays and sidebar layouts that fit perfectly into macOS, running natively with absolutely **0% UI lag**.

---

## 📦 Installation & Unsigned App Setup

Since Sulse is currently in active development, **it is not signed with an Apple Developer certificate yet**. macOS Gatekeeper will block it by default. 

Please follow these quick steps to install and run the app:

1. Go to the [**Releases**](https://github.com/tepliy/sulse-app/releases) page and download **`Sulse.dmg`**.
2. Open the downloaded `.dmg` and drag **Sulse** to your **Applications** folder.
3. Choose **one of the methods** below to launch the app:

### Method A: Right-Click Open (Easiest)
1. Open your **Applications** folder in Finder.
2. Hold the `Control` key (or right-click) and click on **Sulse**.
3. Select **Open** from the menu.
4. Click **Open** in the confirmation dialog.

### Method B: Terminal Command (If macOS says the file is "damaged")
If macOS shows an error or refuses to launch it, open your **Terminal** app and run the following command:
```bash
xattr -cr /Applications/Sulse.app
```
*This command safely removes the quarantine flag that macOS automatically attaches to unsigned internet downloads.*

---

## 🔒 Source Code & License

*   **Proprietary & Closed Source**: Sulse is a closed-source application. The source code is private.
*   **Terms of Use**: By downloading the application, you agree to the [End User License Agreement (EULA)](file:///Users/tepliy/github/sulse-app/LICENSE.md).

---

<p align="center">
  Made with ❤️ for macOS.
</p>
