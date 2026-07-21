<p align="center">
  <img src="https://github.com/Ryukotsuki/Poke-Manager/assets/50199421/0dce132b-8882-4ca0-9719-43e03903c6e9" alt="Poke Manager logo" width="520" />
</p>

<h1 align="center">Poke Manager</h1>

<p align="center">
  A desktop utility for Windows, macOS, and Linux that makes PokeMMO launching, mod management, ReShade installs, and add-on cleanup easier.
</p>

<p align="center">
  <a href="https://github.com/Ryukotsuki/Poke-Manager/releases"><img src="https://img.shields.io/github/v/release/Ryukotsuki/Poke-Manager?style=for-the-badge&label=Latest%20Release" alt="Latest release"></a>
  <a href="https://github.com/Ryukotsuki/Poke-Manager/releases"><img src="https://img.shields.io/github/downloads/Ryukotsuki/Poke-Manager/total?style=for-the-badge" alt="Downloads"></a>
  <a href="https://github.com/Ryukotsuki/Poke-Manager/stargazers"><img src="https://img.shields.io/github/stars/Ryukotsuki/Poke-Manager.svg?style=for-the-badge" alt="Stars"></a>
  <a href="https://github.com/Ryukotsuki/Poke-Manager/issues"><img src="https://img.shields.io/github/issues/Ryukotsuki/Poke-Manager.svg?style=for-the-badge" alt="Issues"></a>
</p>

---

## ✨ Features

- 🖥️ **One-Click PokeMMO Launcher**  
  Start PokeMMO directly from the manager.

- 🔳 **True Borderless Mode**  
  Launch PokeMMO in a cleaner borderless experience for smoother fullscreen-style play.

- 🌐 **Mod Browser and Download Center**  
  Download themes, strings, mods, ReShade presets, and other gameplay enhancements from inside the app.

- 🎨 **ReShade Support**  
  Install and manage ReShade files for a more vibrant PokeMMO visual experience.

- 🧩 **Archetype Theme Tools**  
  Install Archetype Theme, update theme revisions, customize colors, and manage presets.

- 🗂️ **Manager Utilities**  
  Remove installed mods, clean up ReShade files, and manage common PokeMMO add-on folders.

- 📰 **Community and Forum Links**  
  Access useful PokeMMO links and resources through the built-in community tools.

- 🔄 **Automatic Updates**  
  Checks GitHub for new Poke Manager releases and automatically installs them.

- 🛡️ **Error Logging**  
  Captures errors in local logs to make troubleshooting easier.

---

## 📸 Preview

<p align="center">
  <img width="1200" height="875" alt="Poke Manager main window" src="https://github.com/user-attachments/assets/ab83051d-6622-4509-8f5b-0e3f4b143e1b" />
</p>

<p align="center">
  <img width="1200" height="735" alt="Mod Browser" src="https://github.com/user-attachments/assets/329be47d-68ff-4c03-ae09-a5e6b9aadd2c" />
</p>

<p align="center">
  <img width="1200" height="735" alt="Mod Browser downloads" src="https://github.com/user-attachments/assets/705b326a-f6d2-4046-81dd-7c8e42806a14" />
</p>

<p align="center">
  <img width="1200" height="715" alt="Manager utilities" src="https://github.com/user-attachments/assets/ccf68d5d-ec10-4a4a-817b-c278c8347974" />
</p>

<p align="center">
  <img width="1200" height="875" alt="Archetype Theme Customizer" src="https://github.com/user-attachments/assets/09a5776a-b435-47cc-bbee-dd7f1a0feaf6" />
</p>

<p align="center">
  <img width="1200" height="875" alt="Preset Manager" src="https://github.com/user-attachments/assets/5a09a18e-2a44-423b-b677-b6bcd23241b2" />
</p>

<p align="center">
  <img width="1920" height="2160" alt="ReShade comparison" src="https://github.com/user-attachments/assets/10a36eab-b910-4382-bf18-08ecb6e19a32" />
</p>

---

## 🚀 Getting Started

### ⬇️ Download

Download the latest release from the [Releases page](https://github.com/Ryukotsuki/Poke-Manager/releases).

### 📂 Recommended Setup

1. Extract the release.
2. Keep the extracted **PokeManager** folder wherever you want the app installed. On macOS, move `PokeManager.app` to your **Applications** folder.
3. Create a desktop shortcut if you want quick access.
4. Run the platform build: `PokeManager.exe` on Windows, `PokeManager.desktop` or `PokeManager` on Linux, or `PokeManager.app` on macOS.
5. Select your main **PokeMMO** folder when prompted.

### ⚡ Quick Start

1. Open Poke Manager.
2. Select your PokeMMO folder if this is the first launch.
3. Click **Start PokeMMO**.
4. Choose normal launch or true borderless mode.
5. Use **Mod Browser** to install themes, strings, mods, or ReShade presets.
6. Use **Manager** to remove or manage installed components.

---

## 🧭 Common Workflows

### Launch PokeMMO

- Use **Start PokeMMO** for a normal launch.
- Use true borderless mode for a borderless fullscreen-style experience.

### Install Mods or Themes

1. Open **Mod Browser**.
2. Pick a category such as themes, strings, mods, or ReShade.
3. Select an item.
4. Click **Download Selected**.
5. Follow any prompts shown by the app.

### Manage Installed Files

1. Open **Manager**.
2. Choose a cleanup or management action.
3. Remove ReShade, delete selected mods, update Archetype Theme revision, or open the Archetype Theme Customizer.

### Customize Archetype Theme

1. Install Archetype Theme from the Mod Browser.
2. Open **Manager**.
3. Launch **Archetype Theme Customizer**.
4. Edit colors manually or apply a saved preset.
5. Press `Ctrl + F5` in PokeMMO if the game is already running.

---

## 📝 Notes

- 🖥️ **Platform support**: Core launching, mod management, downloads, and update checks support Windows, macOS, and Linux. Windows still has the most complete true-borderless window manipulation.
- 📁 **Install location**: Poke Manager no longer needs to be inside your PokeMMO folder. The selected PokeMMO path is saved in `Runtime/settings.json`.
- 🐧 **Linux icon note**: Linux file managers usually cannot show a custom icon on a raw executable file. Poke Manager auto-installs a user app-menu launcher on first packaged launch. You can still use `PokeManager.desktop` or `Install Linux Launcher.sh` manually if needed.
- 🍎 **macOS launch note**: Move `PokeManager.app` to **Applications**, then open it from Finder or run `open /Applications/PokeManager.app`. A `.app` is a bundle directory, not a terminal executable.
- 🔤 **Strings**: Strings are limited to English, and only one strings package should be used at a time.
- 🎮 **Game state**: Some actions may ask you to close PokeMMO before installing or removing files.
- 🛠️ **Troubleshooting**: Check `Runtime/logs` if something fails.

---

## 💖 Support

If Poke Manager helps you, a star on GitHub goes a long way.

- ⭐ Star the repository
- 🐛 Report bugs through [Issues](https://github.com/Ryukotsuki/Poke-Manager/issues)
- 💡 Suggest improvements or new features
- 💸 [Donate via PayPal](https://paypal.me/Ryukotsuki?country.x=US&locale.x=en_US)

### 💬 Community

Have questions, feedback, or want to share your setup? Join the Discord:

<p align="center">
  <a href="https://discord.gg/HdfjKbPNc9">
    <img src="https://github.com/user-attachments/assets/09fb5822-5e82-431b-b9cc-bbd4111ba48b" alt="Join Discord" />
  </a>
</p>

---

## 📜 Disclaimer

Poke Manager is an independent fan-made utility. It is not affiliated with, endorsed by, or officially connected to [PokeMMO](https://pokemmo.com/) or its developers.

---

<p align="center">
  Built to make PokeMMO setup, launching, and customization easier. ✨
</p>
