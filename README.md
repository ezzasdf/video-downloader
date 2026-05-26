# 📱 Enhanced Video Downloader — User Guide (v1.0.3)

<div align="center">

![Version](https://img.shields.io/badge/Version-1.0.3-blue.svg?style=for-the-badge)
![Platform](https://img.shields.io/badge/Platform-Windows-blue.svg?style=for-the-badge&logo=windows)
![License](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)

<br>

## 🌙 Eid Mubarak everyone! 🌙

*A modern, high-performance Windows desktop video downloader built for speed, security, and simplicity.*

</div>

---

# 🌟 Supported Platforms & Features

<div align="center">

![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)
![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)
![TikTok](https://img.shields.io/badge/TikTok-000000?style=for-the-badge&logo=tiktok&logoColor=white)
![Facebook](https://img.shields.io/badge/Facebook_Reels-1877F2?style=for-the-badge&logo=facebook&logoColor=white)

</div>

- **Comprehensive Media Control** — Video, audio extraction, and batch downloading.
- **Automation Ready** — Auto-download watcher mode and tray execution.
- **Modern UI** — Themes, drag-and-drop support, compact mode, and analytics.
- **Reliable Engine** — Auto-retry logic and update checking.

---

# 🚀 What's New in v1.0.3

| Feature | Before | v1.0.3 |
|---|---|---|
| Platforms | YouTube only | ✨ YouTube, Instagram, TikTok, Facebook Reels |
| TikTok Engine | Not supported | ✨ Watermark-free downloads |
| Retry System | Basic checks | ✨ Smart auto-retry |
| Themes | Basic UI | ✨ Multiple built-in themes |
| Security | None | ✨ Local encrypted profiles |
| Batch Downloads | Manual only | ✨ Automated scheduler |
| Tray Mode | None | ✨ Minimize-to-tray |
| UI Features | Limited | ✨ Drag & drop + profiles |

---

# 📥 1. Installation

## Option A — Installer (Recommended)

1. Open the **Releases** tab on GitHub.
2. Download `YouTubeDownloaderSetup.exe`
3. Run the installer.
4. Launch the app from the desktop shortcut.

---

## Option B — Run From Source

```bash
# Clone repository
git clone https://github.com/yourusername/enhanced-video-downloader.git

# Enter project folder
cd enhanced-video-downloader

# Install dependencies
pip install -r requirements.txt

# Launch application
python ytdlp_gui.py
```

---

# 🔒 2. First Launch & Security Setup

On first launch, the application creates a secure local admin profile.

```text
┌────────────────────────────────────────┐
│        LOCAL SECURITY GENERATOR        │
├────────────────────────────────────────┤
│ Username: [ admin                    ] │
│ Password: [ ********** ]              │
│                                        │
│ [ GENERATE SECURE RECOVERY CODE ]     │
└────────────────────────────────────────┘
```

> ⚠️ IMPORTANT
>
> - All data stays locally on your computer.
> - No credentials are uploaded online.
> - Keep your recovery code safe.

---

# ⚡ 3. Quick Download

1. Copy a supported video URL.
2. Paste it into the app.
3. Select format and quality.
4. Press **Download**.

---

# 📑 4. Batch Processing

Create a file called `links.txt`

Example:

```txt
https://www.youtube.com/watch?v=xxxxxxxxx
https://www.instagram.com/p/xxxxxxxxx
https://www.tiktok.com/@user/video/xxxxxxxxx
```

Then load the file inside the Batch Downloader.

---

# 🤖 5. Automated Watcher Mode

```text
[Settings Panel]
 └── Auto-Download Mode: ENABLED
 └── Scan Interval: 5 Minutes
 └── Tray Processing: TRUE
```

The app can monitor a folder or link file automatically in the background.

---

# 📊 6. Formats & Quality

| Preset | Description |
|---|---|
| Best Quality | Highest available resolution |
| 1080p | Full HD |
| 720p | HD balanced mode |
| 480p / 360p | Smaller file sizes |
| Audio Only | Extract MP3/audio |

---

# 🗂️ 7. Profiles & Subtitles

## Preset Profiles

- **High Quality** — Max quality MP4 downloads
- **Audio Archive** — MP3 + metadata
- **Low Storage** — Compressed WEBM mode

## Subtitle Features

Supports:
- Multi-language subtitles
- Embedded subtitles
- `.srt` export files

---

# 🛠️ 8. Advanced Features

## Drag & Drop

Drag URLs or `.txt` files directly into the app window.

---

## CLI Automation

```bash
python cli.py --source "./links.txt" --format "mp4" --analytics-log
```

---

# 🗄️ 9. Application Directories

```text
%APPDATA%/YouTubeDownloader/

├── settings.json
├── users.json
├── downloaded.txt
├── profiles/
└── logs/
    └── app.log
```

---

# 🔍 10. Troubleshooting

## Downloads Failing

- Reduce concurrent downloads to 2–3.
- Restart app to update yt-dlp.
- Ensure links are public.

---

## FFmpeg Errors

Reinstall using the installer version or manually configure FFmpeg paths.

---

# ❤️ Thank You

Thank you for using **Enhanced Video Downloader v1.0.3**

Enjoy responsibly and have a blessed **Eid Mubarak 🌙**

<div align="center">

## 📦 Download Latest Release

[![Download](https://img.shields.io/badge/Download-v1.0.3-success?style=for-the-badge&logo=github)](https://github.com/ezzasdf/video-downloader/releases/tag/v1.0.3)

</div>
