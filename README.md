<div align="center">
  
  <img src="app_icon.ico" alt="SANDYPLAY Logo" width="130" height="130" style="border-radius: 28px; box-shadow: 0 10px 30px rgba(14, 165, 233, 0.4);">
  
  <h1 align="center">🎬 SANDYPLAY AI Media Studio</h1>
  
  <p align="center">
    <b>The All-in-One AI Multimedia Powerhouse, Hardware Tuner & Universal Stream Studio.</b><br>
    <i>Engineered with Python, PyQt6, LibVLC 4K NVDEC, Faster-Whisper, Google Gemini AI, Dolby.io, and RTL-SDR Radio.</i>
  </p>

  <p align="center">
    <a href="https://github.com/itsyouhuman/SandyPlay/releases/latest">
      <img src="https://img.shields.io/badge/RELEASE-v1.17_STABLE-0ea5e9?style=for-the-badge&logo=github&logoColor=white" alt="Release">
    </a>
    <img src="https://img.shields.io/badge/Platform-Windows_10_%7C_11_(64--bit)-0078D6?style=for-the-badge&logo=windows&logoColor=white" alt="Windows">
    <img src="https://img.shields.io/badge/Architecture-x64_Native-8b5cf6?style=for-the-badge" alt="x64">
    <img src="https://img.shields.io/badge/License-GPL--3.0-10b981?style=for-the-badge" alt="License">
  </p>

  <p align="center">
    <a href="#-whats-new-in-v1.17"><strong>🌟 What's New</strong></a> ·
    <a href="#-feature-showcase"><strong>✨ Feature Tour</strong></a> ·
    <a href="#-the-6-online-studios"><strong>🌐 Online Studios</strong></a> ·
    <a href="#-hardware--acceleration"><strong>⚡ Hardware & Engine</strong></a> ·
    <a href="#-quick-installation"><strong>🚀 Download & Install</strong></a> ·
    <a href="#-keyboard-shortcuts"><strong>⌨️ Shortcuts</strong></a> ·
    <a href="#-connect--support"><strong>🤝 Connect</strong></a>
  </p>
</div>

---

> [!NOTE]
> **SANDYPLAY** is not just another video player — it is a complete **AI-augmented media workstation**. From offline AI subtitle transcription and real-time bilingual lyrics to live hardware RTL-SDR FM radio scanning, ISP bypass network acceleration, and Dolby.io studio mastering, SANDYPLAY redefines what a desktop media player can do.

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
│  SANDYPLAY AI MEDIA STUDIO v1.17                       [ — ] [ 口 ] [ X ] │
├────────────────────────────────────────────────────────────────────────┤
│  [📺 TV]  [🎵 Music]  [🎙️ Podcast]  [⛩️ Anime]  [🎬 Video]  [🌐 Browser] │
├──────────────────────────────────────┬─────────────────────────────────┤
│                                      │  📜 SYNCED BILINGUAL LYRICS     │
│                                      │                                 │
│          4K HDR LIBVLC               │  Original:   Stay with me       │
│        VIDEO / AUDIO CANVAS          │  Translated: என்னோடு இரு         │
│                                      │                                 │
│     [💬 Offline Whisper AI CC]       │  ┌───────────────────────────┐  │
│                                      │  │ ⚡ 48-Band Audio Spectrum │  │
│                                      │  └───────────────────────────┘  │
├──────────────────────────────────────┴─────────────────────────────────┤
│  ▶  ⏮  ⏭   02:14 / 04:30  ══════●═════════════  🔊 85%  [ 10-Band EQ ] │
└────────────────────────────────────────────────────────────────────────┘
```

---

## 🚀 Quick Installation

### Windows 10 / 11 (64-bit)

1. **Download the installer**:
   
   <div align="center">
     <a href="https://github.com/itsyouhuman/SandyPlay/releases/latest">
       <img src="https://img.shields.io/badge/⬇️_DOWNLOAD_SANDYPLAY_SETUP_v1.17-0ea5e9?style=for-the-badge&logo=windows&logoColor=white&scale=1.5" alt="Download SandyPlay">
     </a>
     <br><br>
     <code>SandyPlay_Setup_v1.17.exe (Recommended Installer)</code>
   </div>

2. **Run Setup**:
   - Double-click `SandyPlay_Setup_v1.17.exe`.
   - The installer automatically configures the LibVLC engine, Visual C++ runtimes, and Windows firewall allowances for the RTL-SDR tuner and network booster.
   - Choose your optional shortcuts (Desktop, Taskbar, Explorer right-click integration).
   - Launch and enjoy!

3. **Silent / Administrative Deployment**:
   ```cmd
   SandyPlay_Setup_v1.17.exe /SILENT /NORESTART
   ```

---

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

* 📸 **Instagram:** [@sandyfromindia](https://www.instagram.com/sandyfromindia/)
* 🐙 **GitHub:** [itsyouhuman / SandyPlay](https://github.com/itsyouhuman/SandyPlay)

---

<div align="center">
  <b>If you love using SANDYPLAY, please consider starring ⭐ this repository on GitHub!</b><br>
  <i>Copyright © 2026 Sandytalks Devops. All rights reserved.</i>
</div>
