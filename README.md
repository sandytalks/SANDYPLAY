<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0ea5e9,100:8b5cf6&height=200&section=header&text=SANDYPLAY&fontSize=80&fontColor=ffffff&fontAlignY=38&desc=The%20Ultimate%20Media%20Player%20·%20Dolby%20Edition&descAlignY=60&descSize=18&descColor=94a3b8&animation=fadeIn" width="100%"/>

<br/>

<p>
  <img src="https://img.shields.io/badge/Version-1.14-0ea5e9?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0xMiAyQzYuNDggMiAyIDYuNDggMiAxMnM0LjQ4IDEwIDEwIDEwIDEwLTQuNDggMTAtMTBTMTcuNTIgMiAxMiAyek0xMCAyMHYtNmg0djZoLTR6bTMtOEgxMVY0aDJ2OHoiLz48L3N2Zz4=&labelColor=0f172a"/>
  <img src="https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white&labelColor=0f172a"/>
  <img src="https://img.shields.io/badge/PyQt6-Powered-41CD52?style=for-the-badge&logo=qt&logoColor=white&labelColor=0f172a"/>
  <img src="https://img.shields.io/badge/VLC-Media%20Engine-FF7F00?style=for-the-badge&logo=vlc-media-player&logoColor=white&labelColor=0f172a"/>
  <img src="https://img.shields.io/badge/Platform-Windows-0078D4?style=for-the-badge&logo=windows&logoColor=white&labelColor=0f172a"/>
</p>

<p>
  <img src="https://img.shields.io/badge/Dolby-Audio%20Studio-4285F4?style=for-the-badge&logoColor=white&labelColor=0f172a"/>
  <img src="https://img.shields.io/badge/Whisper%20AI-Subtitles-10a37f?style=for-the-badge&logo=openai&logoColor=white&labelColor=0f172a"/>
  <img src="https://img.shields.io/badge/Gemini%20AI-Smart%20Features-8b5cf6?style=for-the-badge&logo=google&logoColor=white&labelColor=0f172a"/>
  <img src="https://img.shields.io/badge/License-MIT-f59e0b?style=for-the-badge&labelColor=0f172a"/>
</p>

<br/>

> **A cinematic media player built for audiophiles and power users.**  
> Stream anything. Hear everything. Control it all.

<br/>

</div>

---

## ✨ What is SANDYPLAY?

**SANDYPLAY** is a feature-rich, AI-powered desktop media player built with Python, PyQt6, and VLC. It goes far beyond simple playback — combining Dolby audio processing, real-time lyrics sync, AI subtitle generation, live radio and TV streaming, and a stunning dark UI with per-track dynamic theming.

Designed and developed by **Santhosh (Sandytalks)** — built for people who take their media seriously.

---

## 🖥️ Screenshots

<div align="center">

| Now Playing — Music View | Radio Studio | Online TV |
|:---:|:---:|:---:|
| 🎵 Music Panel with Artwork | 📻 FM & SDR Tuner | 📺 IPTV Channels |

> *Dark theme • Dynamic accent colors • Visualizer canvas*

</div>

---

## 🚀 Feature Highlights

<table>
<tr>
<td width="50%" valign="top">

### 🎧 Audio & Playback
- **Hardware & Software decoding** (GPU via NVDEC or CPU)
- **10-band Equalizer** with presets (Bass Boost, Rock, Pop, Vocal…)
- **Dolby.io Cloud Enhance** — real-time professional audio enhancement
- **DTS Audio Modes** — Music / Movies / Games via local DSP engine
- **Surround Sound** — Stereo, 2.1, 5.1, 7.1, Dolby, Spatial 3D
- **A-B Repeat** loop, variable speed (0.25× – 4.0×)
- **Audio / Subtitle sync** fine-tuning in milliseconds
- **SoX Resampler** for studio-grade audio quality
- **Volume boost** up to 200%

</td>
<td width="50%" valign="top">

### 🎬 Video & Display
- **HDR Mode** — contrast/saturation/gamma enhancement
- **Video color controls** — Brightness, Contrast, Saturation, Hue
- **Deinterlacing** — Yadif, Bob, Blend, Linear and more
- **Aspect ratio & crop** cycling — 16:9, 4:3, 21:9, 1:1 and more
- **Zoom** (Ctrl+Scroll) and frame scale presets
- **Screenshots** with one keypress
- **Fullscreen** with auto-hiding floating control bar
- **Dynamic video theme extraction** — accent color from video frames

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🎤 Lyrics Engine
- **Auto-fetch synced LRC lyrics** from 12+ sources in parallel:
  - LRClib, Netease, Textyl, Kugou, Megalobiz
  - JioSaavn, Musixmatch, AZLyrics, Happi, Vagalume, Lyrist…
- **AI lyrics fallback** via Gemini if all sources fail
- **Animated karaoke scroll** with real-time line highlighting
- **Sidecar .lrc / .txt** auto-loading from same folder
- **Batch lyrics fetch** for entire queue in parallel
- **Lyrics search** and in-panel filter
- **Manual paste / LRC editor** built in
- **Lyrics time offset** adjustment (G / H keys)

</td>
<td width="50%" valign="top">

### 🌐 Streaming & Online
- **Online Radio Studio** — 300+ curated stations across genres:
  - Classical, Jazz, Electronic, Hindi, Tamil, K-Pop, Rock, News…
  - Artist-specific stations (Michael Jackson, Coldplay, Taylor Swift…)
- **Hardware SDR FM Tuner** via RTL-SDR dongles
- **Online TV Studio** — IPTV channels loaded live from multiple sources
  - Browse by Genre, Language, Region (India with state-level filters)
- **Online Music Studio** — search YouTube, JioSaavn, SoundCloud, Apple Music
- **Online Video Studio** — trending & search YouTube with thumbnail grid
- **YouTube / SoundCloud / Twitch / Vimeo** URL streaming via yt-dlp

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🤖 AI Tools
- **Whisper AI Subtitles** — offline transcription with word timestamps
  - Auto-extracts audio from video for faster processing
  - Translates to English automatically
  - Caches subtitles per file
- **AI Video Captions** — instant mood/vibe description via Gemini
- **Lyrics Translation** — Tamil ↔ English ↔ any language
- **Bilingual Lyrics View** — original + translation interleaved
- **AI Metadata Cleanup** — strips junk from filenames
- **AI Smart Playlist** — vibe-based queue reordering
- **AI Recommend Next** — similarity-based next track suggestion
- **AI Command Palette** — natural language player control

</td>
<td width="50%" valign="top">

### 💾 Session & Library (Plus)
- **Auto-save session** every 2 minutes
- **Restore last queue** on startup (with prompt)
- **Session snapshots** — named saves you can load anytime
- **Favorites system** — star tracks, browse from menu
- **Recently Played** history (35 tracks)
- **Bookmarks** — per-file timestamp bookmarks
- **Duplicate remover** — smart key-based deduplication
- **Missing file cleaner** — bulk remove dead entries
- **Same-folder mix** — auto-add siblings from track's folder
- **Queue export as HTML** report
- **Queue stats** — total, music, video, missing, top folders

</td>
</tr>
</table>

---

## ⌨️ Keyboard Shortcuts

<div align="center">

| Key | Action | Key | Action |
|:---:|:---|:---:|:---|
| `Space` | Play / Pause | `F` | Toggle Fullscreen |
| `N` | Next Track | `B` | Previous Track |
| `→` / `←` | Seek ±10s | `Alt+→/←` | Seek ±30s |
| `↑` / `↓` | Volume ±5% | `M` | Mute |
| `[` / `]` | Speed Down / Up | `E` | Frame Step |
| `V` | Toggle Visualizer | `C` | Cycle Crop |
| `X` | Next Audio Track | `Z` | Next Subtitle Track |
| `G` / `H` | Lyrics Offset ∓0.3s | `L` | Toggle Loop |
| `Ctrl+L` | Lyrics Panel | `Ctrl+T` | Whisper CC |
| `P` | Toggle Playlist | `F8` | FM Radio |
| `F5` | Effects Panel | `?` | Keyboard Shortcuts |

</div>

---

## 📦 Installation

### Requirements

```
Python 3.10+
VLC Media Player (64-bit)  →  https://www.videolan.org
```

### Install Dependencies

```bash
pip install PyQt6 python-vlc yt-dlp faster-whisper mutagen dolbyio-rest-apis
```

> **Optional but recommended:**
> ```bash
> pip install pyav numpy  # For waveform-synced visualizer
> ```

### Run from Source

```bash
git clone https://github.com/sandytalks/SANDYPLAY.git
cd SANDYPLAY
python sandyplay.py
```

### Windows Installer

Download the latest `.exe` from [**Releases →**](https://github.com/sandytalks/SANDYPLAY/releases/latest)

> No Python required. VLC must still be installed separately.

---

## 🗂️ Project Structure

```
SANDYPLAY/
├── sandyplay.py              # Main application (single file)
├── rtl-sdr/
│   └── x64/
│       └── rtl_fm.exe        # RTL-SDR binary (optional, for FM hardware)
└── ~/.sandyplay/             # Auto-created user data directory
    ├── config.json           # Saved settings
    ├── plus/
    │   ├── last_session.json # Auto-saved session
    │   ├── library.json      # Favorites & recent history
    │   └── snapshots/        # Named session snapshots
    ├── lyrics/               # Cached lyrics (per track hash)
    ├── artwork/              # Cached album art
    ├── subtitles/            # Cached Whisper .srt files
    └── dolby/                # Dolby.io processed audio output
```

---

## 🔧 Configuration & First Run

SANDYPLAY auto-saves all settings on exit to `~/.sandyplay/config.json`. No manual setup needed.

**On first run:**
- Volume, theme, EQ, speaker mode, and loop/shuffle preferences are all persisted.
- The last queue is offered for restore on the next launch.
- Lyrics are fetched automatically and cached per track.

**To use AI features, set your Gemini API key:**

```bash
# Option 1: Environment variable
set GEMINI_API_KEY=your_key_here   # Windows
export GEMINI_API_KEY=your_key_here  # Linux/macOS

# Option 2: Edit sandyplay.py line ~30
MY_GEMINI_API_KEY = "your_key_here"
```

Get a free key at [Google AI Studio](https://aistudio.google.com/app/apikey).

**To use Dolby.io Cloud Enhance:**  
Go to `Misc → Dolby & DTS Studio`, enter your App Key and App Secret from [Dolby.io](https://dolby.io).

**To use Hardware FM Radio (RTL-SDR):**  
Place `rtl_fm.exe` and related DLLs inside `rtl-sdr/x64/` in the app directory.

---

## 🎨 Theming

SANDYPLAY ships with **12 built-in color themes** and supports any custom hex color:

| Theme | Color | | Theme | Color |
|---|---|---|---|---|
| 🔵 Sky Blue | `#0ea5e9` | | 🟣 Purple Haze | `#8b5cf6` |
| 🟠 Sunset Orange | `#f97316` | | 🟢 Emerald | `#22c55e` |
| 🔴 Crimson | `#ef4444` | | 🟡 Golden Glow | `#eab308` |
| 🩷 Hot Pink | `#ec4899` | | 🔷 Deep Indigo | `#4f46e5` |
| 🩵 Teal Surge | `#14b8a6` | | 🌊 Ocean Cyan | `#06b6d4` |
| 🟤 Copper | `#b45309` | | ⚪ Moonlight | `#e2e8f0` |

Themes also auto-extract from video content — the accent color shifts to match what's playing.

---

## 📻 Built-in Radio Stations (Sample)

<details>
<summary><b>300+ stations across 9 genres — click to expand</b></summary>

**🎶 Hindi / Indian**  
AIR Vividh Bharati · Radio Aashiqanaa · Hits of Lata Mangeshkar · Hits of Mohammad Rafi · MY CLUB REMIX

**🎵 Tamil**  
Ilayaraja Radio · AR Rahman Radio · AIR Madurai FM · Sooriyan FM · Thalapathy Vijay FM · Chillax FM · 80s/90s Tamil Hits

**🌟 K-Pop**  
Listen.moe · Big B Radio KPOP · BTS Radio · Exclusively BTS · DFM K-POP · SBS PopAsia

**🎼 Classical & Jazz**  
BBC Radio 3 · Jazz Radio Classic Jazz · Radio Swiss Classic · WQXR Classical · SomaFM Lush

**🎸 Rock & Pop**  
KEXP Seattle · Radio Caroline · Radio Paradise Rock · ROCK FM · SomaFM Groove Salad

**🌍 English / UK**  
BBC Radio 1–6 · BBC World Service · BBC News HD · SomaFM Underground 80s

**🎤 International Artists (100+ dedicated streams)**  
Michael Jackson · Queen · The Beatles · Taylor Swift · Coldplay · Eminem · BTS · and many more

</details>

---

## 📺 Online TV (IPTV)

SANDYPLAY loads thousands of IPTV channels from multiple public sources, organized by:

- **Genre** — News, Movies, Music, Kids, Sports, Entertainment
- **Language** — Tamil, Hindi, Malayalam, Telugu, Kannada, Marathi, Bengali, English, and more
- **Region** — India (state-level), USA, UK, France, Germany, Japan, Korea, etc.

Channels auto-refresh every 24 hours. Favorites are saved locally.

---

## 🤖 Whisper AI — How It Works

1. Press `Misc → AI Tools → Generate Subtitles (Whisper)` or click the **CC** button
2. SANDYPLAY extracts the audio track via ffmpeg (if available) for faster processing
3. `faster-whisper` transcribes the audio using the selected model (default: `medium`)
4. Output is word-timestamp-aligned for precise subtitle sync
5. Automatically **translates to English** regardless of source language
6. Subtitles are cached as `.srt` per file — loaded instantly on next play

**Supported Whisper models:** `tiny` · `base` · `small` · `medium` · `large-v3` · `large-v3-turbo`

---

## 🏗️ Built With

| Component | Role |
|---|---|
| [Python 3.10+](https://python.org) | Core runtime |
| [PyQt6](https://pypi.org/project/PyQt6/) | UI framework |
| [python-vlc](https://pypi.org/project/python-vlc/) | Media playback engine |
| [yt-dlp](https://github.com/yt-dlp/yt-dlp) | Stream resolution (YouTube, SoundCloud, etc.) |
| [faster-whisper](https://github.com/SYSTRAN/faster-whisper) | AI speech-to-text subtitles |
| [mutagen](https://mutagen.readthedocs.io/) | Audio metadata reading |
| [dolbyio-rest-apis](https://pypi.org/project/dolbyio-rest-apis/) | Dolby.io cloud audio enhancement |
| [Google Gemini API](https://aistudio.google.com/) | AI lyrics, captions, translation |
| [SoX Resampler](https://sourceforge.net/projects/sox/) | Studio-grade audio resampling (via VLC) |
| [RTL-SDR](https://www.rtl-sdr.com/) | Hardware FM radio (optional) |

---

## 🙋 FAQ

**Q: Does it work on macOS / Linux?**  
A: The codebase is cross-platform but primarily tested on Windows. VLC and PyQt6 work on all platforms — some platform-specific paths (e.g. RTL-SDR binary, registry keys) are Windows-only.

**Q: Why does it need VLC installed separately?**  
A: SANDYPLAY uses VLC as its decoding and rendering engine via `python-vlc`. The installer does not bundle VLC to keep the download small and avoid license complexity.

**Q: Whisper is slow on first run — is that normal?**  
A: Yes. The first run downloads the model (~1.5GB for `medium`). After that, it loads from disk in seconds.

**Q: Can I use it without a Gemini API key?**  
A: Absolutely. All core features — playback, EQ, lyrics from 12 sources, radio, TV, Whisper subtitles — work without any API key. Gemini only powers AI captions, translation, and smart playlist.

**Q: How do I disable auto-fetch lyrics for large libraries?**  
A: Batches over 200 files skip auto-fetch automatically. You can manually trigger it per-track or via `Misc → Auto-Fetch Lyrics (Entire Queue)`.

---

## 🗺️ Roadmap

- [ ] macOS / Linux native packaging
- [ ] Discord Rich Presence integration  
- [ ] Podcast & RSS feed support
- [ ] Cloud sync for bookmarks and favorites
- [ ] Plugin system for custom DSPs
- [ ] Mini player / compact mode
- [ ] Android companion remote control app

---

## 👤 Author

<div align="center">

**Santhosh** · [@sandytalks](https://github.com/sandytalks)

[![Instagram](https://img.shields.io/badge/Instagram-@itsyouhuman-E4405F?style=for-the-badge&logo=instagram&logoColor=white&labelColor=0f172a)](https://www.instagram.com/itsyouhuman/)
[![GitHub](https://img.shields.io/badge/GitHub-sandytalks-181717?style=for-the-badge&logo=github&logoColor=white&labelColor=0f172a)](https://github.com/sandytalks)

*Crafted with obsession and late nights. For people who hear the difference.*

</div>

---

## 📄 License

```
MIT License — free to use, modify, and distribute.
See LICENSE for full terms.
```

**Third-party acknowledgements:** VLC (LGPL), FFmpeg (LGPL/GPL), OpenAI Whisper (MIT),  
Dolby.io REST APIs (commercial), Google Gemini API (commercial).

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:8b5cf6,100:0ea5e9&height=120&section=footer&text=Made%20with%20%E2%99%A5%20by%20Sandytalks&fontSize=18&fontColor=ffffff&fontAlignY=65&animation=fadeIn" width="100%"/>

**⭐ Star this repo if SANDYPLAY made your music sound better.**

</div>
