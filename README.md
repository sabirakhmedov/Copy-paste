# 📋 macOS Privacy-Focused Clipboard Manager

A lightweight, fast, and 100% private clipboard manager for macOS built with **SwiftUI** and **AppKit**.

Designed for users who need a clean clipboard history without resource overhead or tracking risks.

---

## ✨ Features

* **🔒 100% Private (RAM-Only Storage):** Clipboard history is stored strictly in volatility memory (RAM). Nothing is saved to disk, and all stored items are completely wiped upon app exit or system reboot.
* **⚡ Extremely Lightweight:** Zero performance impact (~0.1% CPU usage and minimal RAM footprint). Runs quietly in the background without draining your battery.
* **📌 Pin Clipboard Items:** Pin frequently used snippets so they stay at the top of your list for quick access.
* **🌐 Offline & Network-Free:** Operates completely offline with zero network calls, telemetry, or third-party trackers.
* **🎯 Native macOS Experience:** Optimized for both Apple Silicon and Intel Macs.

---

## 🚀 Installation & Setup

### Option 1: Pre-compiled App (Recommended)
1. Go to the **[Releases](../../releases)** section of this repository.
2. Download `Copy paste.zip` and extract it.
3. Move `Copy paste.app` to your **Applications** folder.
4. Launch the application.

> **First Launch Note:** Since this application is distributed outside the Mac App Store, you may need to open **System Settings ➔ Privacy & Security** and click **Open Anyway**. You may also need to grant **Accessibility** access in System Settings for global shortcut detection.

### Option 2: Build from Source
1. Clone this repository:
   ```bash
   git clone https://github.com/sabirakhmedov/Copy-paste.git

   Open the project in Xcode.
Press Cmd + R to build and run.
🛠️ Tech Stack
Language: Swift
Frameworks: SwiftUI, AppKit (NSPasteboard)
Target Platform: macOS 13.0+
📄 License
MIT License — Feel free to modify, distribute, and use for personal or commercial projects.

---

## ☕ Support & Donations

If you find this project helpful and want to support its development, you can send a contribution via USDT:

* **USDT (TRC-20):** `TNFyLq3XeoV4nBXStpV1yaHsuWm1LYjKPa`
