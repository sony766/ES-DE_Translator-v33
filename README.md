Polska wersja językowa dostępna [TUTAJ](README_PL.md) / Polish description available [HERE](README_PL.md)

[[Version](#-safety--architecture-github-standard) | [License](#-authors--credits) | [Supported Languages](#-key-features)

# 🎮 ES-DE Translator v33 — NEON EDITION 🌟

![Version](https://shields.io)
![License](https://shields.io)
![Languages Supported](https://shields.io)

**ES-DE Translator** is an independent, feature-rich tool built specifically for the retro-emulation community. It allows for **automated and batch translation of game descriptions (`gamelist.xml`)** as well as **system/console descriptions within themes** for the popular **ES-DE (EmulationStation Desktop Edition)** frontend.

Powered by the Bing translation engine, it offers a stunning, state-of-the-art Neon GUI and dynamically generates localized interface files with full support for 71 languages.

---

## 📸 Interface Preview (Neon GUI v33)

### 🔵 Neon A — Library Management & Game Translation
*Full game library overview, advanced filtering, translation statuses (Ready, In Progress, To Translate), and a robust dual-pane live preview with real-time text editing capabilities.*

<img width="1024" height="537" alt="obraz" src="https://github.com/user-attachments/assets/dc5f2a39-ce28-4a67-8c47-29ea5a032551" />

*Dedicated wide text preview and editing window, showing source and target languages side-by-side:*

<img width="1024" height="537" alt="obraz" src="https://github.com/user-attachments/assets/80f1aa78-3cdd-4c34-a89f-182ff7ed11d0" />

### 🟢 Neon B — Theme Translation (Systems / Consoles)
*A specialized module designed for ES-DE theme creators and customizers. It automatically detects theme folder structures and translates only the `<systemDescription>` tags while playing retro background tracks via the integrated MP3 player.*

<img width="1024" height="537" alt="obraz" src="https://github.com/user-attachments/assets/5902eae1-6e88-42ba-99ee-a653f4e83d8f" />

### 🌍 Fully Multilingual (Interface Auto-Translation Example)
*The software automatically localizes its own entire user interface upon the first launch in any selected language, generating `.ini` configuration files on the fly.*

<img width="1024" height="537" alt="obraz" src="https://github.com/user-attachments/assets/c418bdf3-dddb-42e4-87ce-66600d63dd8e" />

---

## 🔥 Key Features

| Feature | Description |
| :--- | :--- |
| **Game Translation** | Automated translation of `<desc>` tags in `gamelist.xml` files without altering ROM paths or metadata structures. |
| **Theme Customizer** | Automatically scans and translates only `<systemDescription>` fields across custom ES-DE themes. |
| **Smart Cache System** | Saves translation progress after every successful item. Allows seamless pausing and resuming without losing data or API quotas. |
| **Live Editor** | Real-time preview panel allows manual text corrections during active batch translation processes. |
| **Neon GUI (v33)** | Features two layout layouts (Neon A - Library, Neon B - Console) with animated splash screens and glowing UI effects. |
| **Audio & Retro Vibes** | Built-in retro MP3 background music player and 10 customizable event sound effects (WAV/MP3). |
| **Localization Engine** | Instantly translates the app interface to any selected language upon first boot, saving configuration to `language/*.ini`. |

---

## 🛠️ Quick Start Guide

1. **Select Folder:** Target your ES-DE `gamelists` directory or your active `themes` folder.
2. **Set Language:** Choose your desired target language. Leave the source language set to `Auto`.
3. **Scan:** Click the library scan button to let the application index games or themes.
4. **Start:** Click **Start**. Use **Pause / Stop** whenever needed. Thanks to the persistent cache, you can pick up exactly where you left off by clicking **Resume**.

> ⚠️ **IMPORTANT:** This application never alters your ROMs or downloads game files. Before running mass translations on massive libraries, creating your own manual backup of `gamelist.xml` files is highly recommended.

---

## 🚀 Safety & Architecture (GitHub Standard)

The program is distributed as a convenient, automated `.exe` installer. Simply double-click the downloaded file to install the application on your system.

* **Sandboxed Environment:** As of v33, user assets, preferences, and translation cache are stored securely inside `%LOCALAPPDATA%\ES-DE Translator`. Updating the executable will never overwrite your personal data.
* **Portable Mode:** Prefer a self-contained installation (e.g., for a thumb drive or external hard drive)? Simply create an empty text file named `portable.txt` right next to the `.exe` file.

### How to Update via GitHub
1. Click the **Update** button directly inside the app interface.
2. The application will fetch the public `update.json` file hosted on this GitHub repository.
3. If a newer version is detected, select **Yes** to instantly pop open your app installation folder.
4. Head over to the **Releases** tab on this GitHub page and download the latest installer `.exe`.
5. Close the old software version, launch the new installer, and run through the steps (it safely replaces the core app file).

> 🛡️ **Data Integrity:** The installer replaces the core executable file only. Your saved logs, translation cache, language configurations inside `language/`, and customized files within `user_assets/` remain completely safe and untouched!

---

## 🤝 Authors & Credits

* **Lead Developer:** `sony766`
* **AI Collaborators:** 
  * [ChatGPT (OpenAI)](https://chatgpt.com) — Core architecture, translation logic, and app engine.
  * [Claude (Anthropic)](https://claude.ai) — Neon GUI v33 assets, animated splash screens, custom console iconography, and localization systems.

---
*This is an open-source, community-driven project. It is not officially affiliated with the ES-DE development team or Microsoft.*

