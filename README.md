# 🎵 YTDOWN ULTIMATE `v3.3`

> A powerful YouTube downloader for **Termux** — with Pro Metadata, Synced Lyrics, and a beautiful TUI.

---

## ✨ Features

- 🎵 **Audio Download** — Opus, M4A (AAC), MP3
- 🎬 **Video Download** — 4K, 1080p, 720p, or manual format selection
- 🏷️ **Smart Metadata** — Auto-tags Title, Artist, Album (Single fallback)
- 📝 **Synced Lyrics** — Downloads `.lrc` lyrics file automatically
- 🖼️ **Thumbnail Embed** — Cover art embedded in audio files
- 📦 **Built-in Dependency Manager** — Check & install tools from within the app
- ⚡ **Direct URL Launch** — Pass a URL as argument to skip the menu

---

## 📋 Requirements

### Python Packages
```
yt-dlp
mutagen
syncedlyrics
rich
```

### System Tool
```bash
pkg install ffmpeg
```

---

## 🚀 Installation

**1. Clone the repository:**
```bash
git clone https://github.com/SIFAT-AL-MUKIT/ytdown.git
cd ytdown
```

**2. Install Python dependencies:**
```bash
pip install -r requirements.txt
```

**3. Install ffmpeg:**
```bash
pkg install ffmpeg
```

**4. (Optional) Install as a global command:**
```bash
cp ytdown /data/data/com.termux/files/usr/bin/ytdown
chmod +x /data/data/com.termux/files/usr/bin/ytdown
```

After step 4, you can run `ytdown` from anywhere in Termux.

---

## 🎮 Usage

**Interactive Menu:**
```bash
ytdown
```

**Direct URL (skips menu):**
```bash
ytdown https://www.youtube.com/watch?v=xxxxx
```

---

## 📂 Output Location

All downloaded files are saved to:
```
/storage/emulated/0/Download/Termux_ytdown/
```

---

## 🗂️ File Formats

| Type  | Format | Details |
|-------|--------|---------|
| Audio | `.opus` | Best quality (Recommended) |
| Audio | `.m4a`  | AAC, YouTube native |
| Audio | `.mp3`  | 192kbps, converted |
| Video | `.mp4`  | Up to 4K, with subtitles |
| Lyrics | `.lrc` | Synced lyrics (LRC format) |

---

## 👤 Author

**SIFAT-AL-MUKIT**

---

## 📄 License

This project is open source. Feel free to use and modify as needed.
