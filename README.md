<div align="center">
  
  <!-- NOTE: Save your app_icon.ico as a .png file and upload it to your repo, then replace this link! -->
  <img src="app_icon.png" alt="SANDYPLAY Logo" width="140" height="140" style="border-radius: 25px;">
  
  <h1 align="center">SANDYPLAY Media Player 🎬</h1>
  
  <p align="center">
    <em>The ultimate AI-powered, Dolby-enhanced media experience. Built for audiophiles and cinephiles.</em>
  </p>

  <p align="center">
    <a href="https://github.com/itsyouhuman/SandyPlay/releases/latest">
      <img src="https://img.shields.io/github/v/release/itsyouhuman/SandyPlay?style=for-the-badge&color=0ea5e9&label=LATEST+RELEASE" alt="Release">
    </a>
    <img src="https://img.shields.io/badge/Platform-Windows_10%2B-0078D6?style=for-the-badge&logo=windows&logoColor=white" alt="Windows">
    <img src="https://img.shields.io/badge/Powered_by-Python_%7C_VLC-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python & VLC">
    <img src="https://img.shields.io/badge/AI_Engine-Gemini_%7C_Whisper-8E75B2?style=for-the-badge&logo=googlebard&logoColor=white" alt="AI">
  </p>

  <p align="center">
    <a href="#-features"><strong>✨ Features</strong></a> ·
    <a href="#-showcase"><strong>📸 Showcase</strong></a> ·
    <a href="#-installation"><strong>🚀 Installation</strong></a> ·
    <a href="#%EF%B8%8F-keyboard-shortcuts"><strong>⌨️ Shortcuts</strong></a> ·
    <a href="#-connect"><strong>🤝 Contact</strong></a>
  </p>
</div>

---

> [!NOTE]
> **SANDYPLAY** goes far beyond a standard media player. By integrating **OpenAI's Whisper** for instant local subtitles, **Google Gemini** for smart metadata and lyrics translation, and **Dolby.io** for cloud-based audio mastering, it delivers a premium, visually stunning experience wrapped in a dynamic glassmorphism UI.

---

## 🌟 What's New in v1.17

* 🚀 **Full Offline Faster-Whisper AI CC**: Local real-time speech-to-text with Silero VAD. Generates perfectly timed English subtitles on-the-fly without sending your data to the cloud.
* 📻 **RTL-SDR Hardware FM Tuner**: Plug in any RTL2832U USB dongle and listen to live over-the-air wideband FM radio (87.5–108 MHz) with automatic frequency scanning, signal meter, and squelch control.
* 🛡️ **Built-in GoodbyeDPI & Network Booster**: Seamless, one-click bypass of ISP throttling and SNI filtering for smooth IPTV and video streaming.
* 📺 **Unified Online Studios**: 6 integrated streaming hubs (Live IPTV, Music Hits, Podcasts, Anime, YouTube Video Search, and the Sandbox Web Browser with ad-blocking).
* 🎤 **Universal Multi-Source Lyrics**: Synced `.lrc` lyrics from 10+ sources with side-by-side Gemini AI bilingual translation (English, Tamil, Hindi, Telugu, and more).
* 🎧 **Dolby.io Cloud Master & DTS Virtual:X**: Instant cloud-based audio dynamic mastering and 6 custom DSP spatializer presets.
* ⚡ **High-DPI Cyberpunk Glassmorphism UI**: 12+ vibrant accent color palettes, automatic ambient frame color extraction, and smooth micro-animations.

---

## ✨ Feature Tour (Explained Simply)

### 🤖 1. Artificial Intelligence & Subtitles
* **Offline AI Transcriber (Faster-Whisper)**: Watching a video without subtitles? Press <kbd>Ctrl</kbd> + <kbd>T</kbd>. SANDYPLAY runs a local Whisper model on your PC to listen to the dialogue and display synchronized subtitles automatically.
* **Google Gemini AI Assistant**: An intelligent sidebar chat that can answer questions about the video or music currently playing, summarize content, explain plotlines, or translate captions.
* **Smart Bilingual Lyrics**: Shows both original song lyrics and synchronized translated lyrics side-by-side, so you always understand songs in any foreign language.
* **Natural Language Command Palette**: Just type what you want (*"Play romantic Tamil songs"*, *"Set volume to 80"*, *"Speed up to 1.25x"*), and the player executes your command instantly.

### 🎧 2. Audiophile Sound Engine
* **Dolby.io Cloud Mastering**: Fix muddy or low-volume recordings. Upload to Dolby's mastering API with one click for clear vocals and balanced bass.
* **DTS Studio Surround Spatializer**: Transforms standard stereo headphones into a wide 3D soundstage with modes tailored for **Movies**, **Music**, **Voice**, **Gaming**, and **Night Mode**.
* **10-Band Graphic Equalizer**: Fine-tune frequencies from 32 Hz to 16 kHz with built-in presets (Bass Boost, Vocal Clarity, Rock, Electronic, Classical, etc.).
* **Real-Time 48-Band Spectrum Visualizer**: Dynamic visual representation of your music's audio frequencies, perfectly synced to the rhythm.
* **Smart Device Adaptation**: Automatically detects whether you are using laptop speakers, headphones, or external monitors, and adjusts audio loudness curves accordingly.

---

## 🌐 The 6 Online Studios

SANDYPLAY includes 6 dedicated streaming and discovery dialogs accessible right from the top navigation bar:

| Studio | Description & Highlights |
| :--- | :--- |
| **📺 Online TV Studio** | Stream 1000+ live television channels across News, Sports, Movies, and Entertainment from India, USA, UK, and worldwide. Includes stream health checks and YuppTV live integration. |
| **🎵 Online Music Studio** | Explore trending hits, top charts (Apple Music, Spotify, JioSaavn), and regional playlists (Tamil, Hindi, Telugu, Punjabi, Malayalam, International Pop). Play instantly with real-time lyrics. |
| **🎙️ Online Podcast Studio** | Search and stream millions of podcast episodes from Apple Podcasts and Podcast Index. Supports background episode downloading. |
| **⛩️ Online Anime Studio** | Browse popular and trending anime, select seasons and episodes, choose streaming servers, and download episodes for offline viewing. |
| **🎬 Online Video Studio** | Built-in YouTube and web video search powered by `yt-dlp`. Stream in 1080p, 2K, or 4K with parallel chunk downloading for instant zero-buffering playback. |
| **🌐 Sandy Web Browser** | Built-in Chromium browser with multi-tab support, ad-blocker (`🛡️ AdBlock`), download manager, and dark theme synchronization. |

---

## ⚡ Hardware & Engine

* **LibVLC 4K NVDEC Hardware Decoding**: Uses native VLC core engine with NVIDIA CUDA, Intel QuickSync, and AMD DXVA2 GPU acceleration to playback 4K and 8K HDR videos without taxing your CPU.
* **RTL-SDR USB Hardware Tuner**: Connect an inexpensive RTL-SDR dongle to your USB port, open **FM Radio**, and listen to over-the-air radio stations completely offline without an internet connection.
* **Parallel Stream Proxy (Port 8125)**: A built-in local multi-threaded HTTP caching proxy that fetches online video chunks in parallel, eliminating playback stuttering on slow internet connections.
* **High-Speed Stream Capture**: Download any streaming video or audio file with automatic format conversion via `ffmpeg`.

---

## 📸 Interface Preview

```
┌────────────────────────────────────────────────────────────────────────┐
│  SANDYPLAY AI MEDIA STUDIO v1.17                    [ — ] [ 口 ] [ X ] │
├────────────────────────────────────────────────────────────────────────┤
│  [📺 TV] [🎵 Music] [🎙️ Podcast] [⛩️ Anime] [🎬 Video]  [🌐 Browser] │
├──────────────────────────────────────┬─────────────────────────────────┤
│                                      │  📜 SYNCED BILINGUAL LYRICS     │
│                                      │                                 │
│          4K HDR LIBVLC               │  Original:   Stay with me       │
│        VIDEO / AUDIO CANVAS          │  Translated: என்னோடு இரு    │
│                                      │                                 │
│     [💬 Offline Whisper AI CC]       │  ┌───────────────────────────┐  │
│                                      │  │ ⚡ 48-Band Audio Spectrum │  │
│                                      │  └───────────────────────────┘  │
├──────────────────────────────────────┴─────────────────────────────────┤
│  ▶  ⏮  ⏭   02:14 / 04:30  ══════●═════════════ 🔊 85% [ 10-Band EQ ] │
└────────────────────────────────────────────────────────────────────────┘
```

---

## 🚀 Quick Installation

### Windows 10 / 11 (64-bit)
<div align="center">
  <h3>Get the Latest Sandyplay setup v1.13:</h3>
  
  <a href="https://github.com/sandytalks/SANDYPLAY/releases/download/Sandyplay/SandyPlay_Setup_v1.13.exe">
    <img src="https://img.shields.io/badge/⬇️_DOWNLOAD_SANDYPLAY-0ea5e9?style=for-the-badge&logo=windows&logoColor=white&scale=2" alt="Download">
  </a>
  <p><em>Version 1.13 | Windows 10/11 (64-bit)</em></p>
</div>

> [!IMPORTANT]  
> 1. Click the blue download button above.
> 2. Run the downloaded `SandyPlay_Setup_v1.13.exe`.
> 3. The installer will automatically configure VLC Engine and Visual C++ runtimes.
> 4. Launch the app and drop in your media!

<br>

## ⌨️ Keyboard Shortcuts

| Shortcut | Description | Shortcut | Description |
| :---: | :--- | :---: | :--- |
| <kbd>Space</kbd> | Play / Pause | <kbd>[</kbd> / <kbd>]</kbd> | Decrease / Increase Playback Speed |
| <kbd>F</kbd> / <kbd>Enter</kbd> | Toggle Fullscreen | <kbd>C</kbd> | Cycle Aspect Ratio / Crop |
| <kbd>N</kbd> / <kbd>B</kbd> | Next / Previous Track | <kbd>Ctrl</kbd> + <kbd>L</kbd> | Toggle Floating Lyrics Panel |
| <kbd>→</kbd> / <kbd>←</kbd> | Seek +10s / -10s | <kbd>Ctrl</kbd> + <kbd>T</kbd> | Toggle Offline Whisper AI Subtitles |
| <kbd>↑</kbd> / <kbd>↓</kbd> | Volume Up / Down (5%) | <kbd>F5</kbd> | Open Equalizer & Audio Effects |
| <kbd>M</kbd> | Mute / Unmute Audio | <kbd>Ctrl</kbd> + <kbd>O</kbd> | Open Media File |
| <kbd>Ctrl</kbd> + <kbd>U</kbd> | Open Network Stream URL | <kbd>?</kbd> | View In-App Interactive Help Guide |

---

## 🛠️ Technology Stack

<p align="center">
  <img src="https://img.shields.io/badge/Python_3.14-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/PyQt6_GUI-41CD52?style=for-the-badge&logo=qt&logoColor=white" alt="PyQt6">
  <img src="https://img.shields.io/badge/LibVLC_Engine-FF8800?style=for-the-badge&logo=vlcmediaplayer&logoColor=white" alt="VLC">
  <img src="https://img.shields.io/badge/Faster--Whisper-412991?style=for-the-badge&logo=openai&logoColor=white" alt="Whisper">
  <img src="https://img.shields.io/badge/Google_Gemini_AI-8E75B2?style=for-the-badge&logo=googlebard&logoColor=white" alt="Gemini">
  <img src="https://img.shields.io/badge/Dolby.io-000000?style=for-the-badge&logo=dolby&logoColor=white" alt="Dolby">
  <img src="https://img.shields.io/badge/RTL--SDR_Radio-E34F26?style=for-the-badge" alt="RTL-SDR">
  <img src="https://img.shields.io/badge/Inno_Setup_6-00599C?style=for-the-badge" alt="Inno Setup">
</p>

* **Core Platform:** Python 3.14 (Optimized with PyInstaller 6 onedir flat architecture)
* **User Interface:** PyQt6 & QtWebEngine (Cyberpunk Dark Glassmorphism, Dynamic Accent Palette)
* **Media Playback:** 64-bit LibVLC with direct hardware acceleration (NVDEC, DXVA2, CUDA)
* **Local Machine Learning:** `faster-whisper` + `ctranslate2` + `onnxruntime` + Silero VAD
* **Generative AI:** Google Gemini API (`google-genai` SDK)
* **Audio Mastering:** Dolby.io Media Processing REST APIs
* **Software-Defined Radio:** `rtl-sdr` (`rtl_fm` streaming pipeline)
* **Network Acceleration:** `goodbyedpi` Windows WinDivert packet filter
* **Installer Architecture:** Inno Setup 6 (LZMA2 Ultra64 Solid Compression, Explorer shell refresh)

---

## 🤝 Connect & Support

Created with passion by **Sandytalks Devops** (Santhosh).

* 📸 **Instagram:** [@sandyplay](https://www.instagram.com/sandyplay/)
* 🐙 **GitHub:** [Sandyplay](https://github.com/sandytalks/SANDYPLAY/)

---

<div align="center">
  <b>If you love using SANDYPLAY, please consider starring ⭐ this repository on GitHub!</b><br>
  <i>Copyright © 2026 Sandytalks Devops. All rights reserved.</i>
</div>
