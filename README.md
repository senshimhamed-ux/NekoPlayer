<p align="center">
  <img src="nekoplayer-banner.jpg" alt="NekoPlayer — Gothic Metal Music Player" width="100%">
</p>

<p align="center">
  <a href="../../releases/tag/v1.0.0"><img src="https://img.shields.io/badge/version-1.0.0-8f2049?style=for-the-badge&logo=github"></a>
  <img src="https://img.shields.io/badge/platform-Windows-1f6feb?style=for-the-badge&logo=windows&logoColor=white">
  <img src="https://img.shields.io/badge/architecture-x64-7c3aed?style=for-the-badge">
  <img src="https://img.shields.io/badge/UI-HTML%20%2F%20CSS%20%2F%20JS-ec4899?style=for-the-badge&logo=javascript&logoColor=white">
</p>

<p align="center">
  <b>A Gothic / Metal inspired desktop music player for Windows.</b><br>
  Local playback • Library • Artwork • Queue • YouTube / yt-dlp • FFmpeg
</p>

<p align="center">
  <a href="../../releases/tag/v1.0.0">🚀 Download v1.0.0</a> •
  <a href="#installation">📦 Installation</a> •
  <a href="#features">✨ Features</a>
</p>

---

## ✨ Features

| | Capability | | Capability |
|---|---|---|---|
| 🎵 | Local MP3 playback | 📚 | Music library management |
| 🖼️ | Album artwork & covers | 📋 | Queue / playlist support |
| ▶️ | YouTube integration via yt-dlp | 🔄 | FFmpeg-powered MP3 conversion |
| ⚙️ | Embedded Python backend | 🖥️ | Native Windows desktop app |
| 🖤 | Gothic / Metal visual design | 📦 | Portable ZIP distribution |
| 🛠️ | Windows installer | | |

## 📸 Interface Preview

<p align="center">
  <img src="disk.png" alt="NekoPlayer main player interface" width="92%">
</p>

<p align="center"><sub>Main player interface</sub></p>

<p align="center">
  <img src="queue.png" alt="NekoPlayer queue interface" width="92%">
</p>

<p align="center"><sub>Queue / playlist interface</sub></p>

## 💿 Installation

### Recommended — Windows Installer

1. Open the [v1.0.0 Release](../../releases/tag/v1.0.0).
2. Download **NekoPlayer-Setup.exe**.
3. Run the installer and follow the setup wizard.
4. Choose whether to create a desktop shortcut.
5. Launch **NekoPlayer**.

> No Python installation is required for the packaged release.

### Portable Edition

1. Open the [v1.0.0 Release](../../releases/tag/v1.0.0).
2. Download **NekoPlayer-Release.zip**.
3. Extract the archive to any folder.
4. Launch `NekoPlayer.exe`.

> The portable edition does not require an installer.

### 🖥️ Command-Line Installation

The Windows installer can also be launched from **PowerShell** or **Command Prompt** for automated or silent installation.

**Silent install:**

```powershell
.\NekoPlayer-Setup.exe /VERYSILENT /SUPPRESSMSGBOXES /NORESTART
```

**Launch the portable edition from PowerShell:**

```powershell
cd .\NekoPlayer-Release
.\NekoPlayer.exe
```

> GUI installation is recommended for most users. Command-line options are optional and intended for users who prefer terminal-based workflows or automated setup.

### 🛠️ Portable ZIP — Windows Security Note

Windows may mark files downloaded from the internet as originating from an untrusted source. In some cases, this can prevent bundled .NET components from loading correctly after the ZIP is extracted.

If the portable version shows an error mentioning `Python.Runtime.Loader.Initialize`, try unblocking the ZIP **before extracting it again**.

**File Explorer:**

1. Right-click **NekoPlayer-Release.zip**.
2. Select **Properties**.
3. Check **Unblock** (if the option is available).
4. Click **Apply** → **OK**.
5. Extract the ZIP again and launch `NekoPlayer.exe`.

**PowerShell:**

```powershell
Unblock-File ".\NekoPlayer-Release.zip"
```

Then extract it again:

```powershell
Expand-Archive ".\NekoPlayer-Release.zip" ".\NekoPlayer-Release" -Force
```

> This is only a Windows security/unblocking step. It does **not** mean Python, pythonnet, or other development dependencies need to be installed separately.

## 🖥️ System Requirements

| Requirement | Details |
|---|---|
| Operating system | Windows 10 / Windows 11 |
| Architecture | 64-bit (x64) |
| Internet | Only required for online features such as YouTube / yt-dlp |
| Python | Not required for packaged releases |

## 🚀 Usage

Launch NekoPlayer and manage your music directly from the desktop interface. Use the library for local tracks, build a queue, browse artwork, and use supported online media features when connected to the internet.

## 📦 v1.0.0 — First Stable Release

The first public stable release of NekoPlayer.

### Included downloads

- **NekoPlayer-Setup.exe** — Windows installer
- **NekoPlayer-Release.zip** — Portable version

<a href="../../releases/tag/v1.0.0">
  <img src="https://img.shields.io/badge/Download-NekoPlayer%20v1.0.0-8f2049?style=for-the-badge&logo=github" alt="Download NekoPlayer v1.0.0">
</a>

## ⚠️ Windows SmartScreen

The release binaries may not be code-signed. Windows SmartScreen can therefore display a warning when the installer or application is launched.

If you downloaded NekoPlayer from the official GitHub release page, verify the filename and source before proceeding.

## 🐛 Troubleshooting

**NekoPlayer does not start**

- Confirm that Windows is 64-bit and supported.
- For the portable edition, re-extract the complete ZIP archive.
- If you see `Python.Runtime.Loader.Initialize`, follow the [Portable ZIP — Windows Security Note](#-portable-zip--windows-security-note).
- For the installer edition, reinstall from the latest release.
- For YouTube / yt-dlp features, verify that your internet connection is working.

## 📄 License

No open-source license has been declared yet. All rights are reserved unless otherwise stated by the project owner.

## 👤 Author

**senshimhamed-ux**

<p align="center">
  <img src="nekoplayer.icon.png" alt="NekoPlayer" width="96">
</p>

<p align="center"><sub>Made with 🖤 for music lovers.</sub></p>
