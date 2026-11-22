<div align="center">

<img src="app_icon.png" alt="SANDYPLAY logo" width="112">

# SANDYPLAY

### THE NEXT-GENERATION AI MULTIMEDIA STUDIO

**One player. Six studios. A whole new media experience.**

[![Release](https://img.shields.io/badge/Release-v1.18%20Ultimate-22D3EE?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sandytalks/SANDYPLAY/releases/latest)
[![Windows](https://img.shields.io/badge/Platform-Windows%2010%20%7C%2011-2563EB?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/sandytalks/SANDYPLAY/releases)
[![Python](https://img.shields.io/badge/Python-3.12%2B-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![LibVLC](https://img.shields.io/badge/Engine-LibVLC-FF8800?style=for-the-badge&logo=vlc&logoColor=white)](https://www.videolan.org/)
[![License](https://img.shields.io/badge/License-GPL--3.0-16A34A?style=for-the-badge)](https://github.com/sandytalks/SANDYPLAY/blob/main/LICENSE)

[**Download**](#-download) · [**What's New**](#-whats-new-in-v118) · [**Features**](#-features) · [**OliX Audio**](#-olix-audio-technology) · [**Installation**](#-installation) · [**Roadmap**](#-development-roadmap)

---

*Engineered for entertainment. Designed for discovery. Powered by OliX Audio Technology™.*

</div>

## ✦ Overview

SANDYPLAY is a Windows multimedia application that brings local playback, online entertainment, AI-assisted tools and audio processing together in one desktop experience.

Built with Python, PyQt6 and LibVLC, SANDYPLAY combines a media player with six dedicated online studios, an integrated browser, hardware radio support and the OliX Audio Technology™ sound architecture.

> [!IMPORTANT]
> **Audio architecture:** SANDYPLAY's audio streams, 10-band equalizer, 48-band spectrum visualizer, SoX HiFi resampler and speaker profiles are powered by **OliX Audio Technology™**. **Dolby Studio** is a separate cloud audio dynamic-mastering module using Dolby.io.
>
> 
<h2 id="the-definitive-comparison">🏆 The Definitive Comparison</h2>

<p><em>How SANDYPLAY v1.18 stacks up against leading media players worldwide.</em></p>

<table width="100%">
<thead>
<tr>
  <th align="left">Feature</th>
  <th align="center">🏅 SANDYPLAY v1.18</th>
  <th align="center">VLC 3.x</th>
  <th align="center">PotPlayer</th>
  <th align="center">MPC-HC</th>
  <th align="center">foobar2000</th>
  <th align="center">Kodi</th>
  <th align="center">MPV</th>
</tr>
</thead>
<tbody>
<tr><td><b>Full App Audio Architecture</b></td><td align="center">✅ <b>OliX Audio Technology™</b></td><td align="center">Basic Audio</td><td align="center">Standard</td><td align="center">DirectShow</td><td align="center">Modular</td><td align="center">Standard</td><td align="center">FFmpeg Core</td></tr>
<tr><td><b>OliX DTS Spatializer</b></td><td align="center">✅ 3 Spatial Modes</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td></tr>
<tr><td><b>OliX 10-Band Graphic Parametric EQ</b></td><td align="center">✅ 32 Hz &ndash; 16 kHz</td><td align="center">⚠️ basic</td><td align="center">✅</td><td align="center">❌</td><td align="center">✅</td><td align="center">⚠️ addon</td><td align="center">❌</td></tr>
<tr><td><b>OliX 48-Band Real-Time Visualizer</b></td><td align="center">✅ Dynamic Spectrum</td><td align="center">⚠️ basic</td><td align="center">⚠️ basic</td><td align="center">❌</td><td align="center">✅</td><td align="center">⚠️ addon</td><td align="center">❌</td></tr>
<tr><td><b>OliX SoX HiFi Resampler &amp; Energy Sync</b></td><td align="center">✅ Studio-Grade Resampling</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td><td align="center">⚠️ plugin</td><td align="center">❌</td><td align="center">❌</td></tr>
<tr><td><b>Dolby Studio (Cloud Dynamic Mastering)</b></td><td align="center">✅ Dolby.io Cloud Module</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td></tr>
<tr><td><b>Offline AI Subtitles (Faster-Whisper + VAD)</b></td><td align="center">✅ 99 langs (100% offline)</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td></tr>
<tr><td><b>Instant AI Video Caption &amp; Summarizer</b></td><td align="center">✅ Gemini by Google</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td></tr>
<tr><td><b>Bilingual Synced Lyrics + AI Translation</b></td><td align="center">✅ Side-by-side</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td></tr>
<tr><td><b>Live TV Studio (26,775+ Global Channels)</b></td><td align="center">✅ </td><td align="center">⚠️ manual M3U</td><td align="center">⚠️ manual M3U</td><td align="center">❌</td><td align="center">❌</td><td align="center">⚠️ addon</td><td align="center">❌</td></tr>
<tr><td><b>Adaptive 6,000ms Slow-Net Streaming Buffer</b></td><td align="center">✅ Auto-Reconnect</td><td align="center">⚠️ 300ms default</td><td align="center">⚠️ basic</td><td align="center">❌</td><td align="center">❌</td><td align="center">⚠️ addon</td><td align="center">⚠️ config</td></tr>
<tr><td><b>AI Natural Language Command Palette</b></td><td align="center">✅ Ctrl+K</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td></tr>
<tr><td><b>HDR Master Tuner &amp; Video Suite</b></td><td align="center">✅ OliX Vision</td><td align="center">⚠️ basic</td><td align="center">✅</td><td align="center">⚠️ basic</td><td align="center">❌</td><td align="center">⚠️ addon</td><td align="center">⚠️ scripts</td></tr>
<tr><td><b>15-Source Synced Lyrics Engine</b></td><td align="center">✅ Instant </td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td><td align="center">⚠️ plugin</td><td align="center">⚠️ addon</td><td align="center">❌</td></tr>
<tr><td><b>Music Discovery &amp; 320kbps Streaming</b></td><td align="center">✅ Online Music </td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td></tr>
<tr><td><b>Anime Studio (Multi-Audio &amp; Dubs)</b></td><td align="center">✅ Dual-source sync</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td><td align="center">⚠️ addon</td><td align="center">❌</td></tr>
<tr><td><b>Podcast Studio </b></td><td align="center">✅ </td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td><td align="center">⚠️ addon</td><td align="center">❌</td></tr>
<tr><td><b>Online Video Studio &amp; Parallel Proxy (8125)</b></td><td align="center">✅ </td><td align="center">⚠️ manual URL</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td><td align="center">⚠️ addon</td><td align="center">❌</td></tr>
<tr><td><b>RTL-SDR Hardware FM Radio Tuner</b></td><td align="center">✅ 76&ndash;108 MHz offline</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td></tr>
<tr><td><b>300+ Curated Online Radio Stations</b></td><td align="center">✅ Online FM &amp; ICY meta</td><td align="center">⚠️ manual</td><td align="center">❌</td><td align="center">❌</td><td align="center">⚠️ plugin</td><td align="center">⚠️ addon</td><td align="center">❌</td></tr>
<tr><td><b>GoodbyeDPI + Sophos SSL CA Bypass</b></td><td align="center">✅ Auto network bypass</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td></tr>
<tr><td><b>Integrated Multi-Tab Web Browser</b></td><td align="center">✅ AdBlock + Downloads</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td></tr>
<tr><td><b>High-Speed Multi-Threaded Downloader</b></td><td align="center">✅ </td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td></tr>
<tr><td><b>13 Cyber Themes + Ambient Color Sync</b></td><td align="center">✅ Dynamic palette</td><td align="center">❌</td><td align="center">⚠️ skins</td><td align="center">⚠️ skins</td><td align="center">⚠️ themes</td><td align="center">⚠️ skins</td><td align="center">❌</td></tr>
<tr><td><b>NVDEC 4K/8K Hardware Decoding</b></td><td align="center">✅ GPU accelerated</td><td align="center">✅</td><td align="center">✅</td><td align="center">✅</td><td align="center">❌</td><td align="center">✅</td><td align="center">✅</td></tr>
<tr><td><b>Setup Complexity / Extra Addons Needed</b></td><td align="center">🟢 Zero (Self-Contained)</td><td align="center">🟢 Zero</td><td align="center">🟢 Zero</td><td align="center">🟡 Codec packs</td><td align="center">🔴 Many plugins</td><td align="center">🔴 Many addons</td><td align="center">🟡 Scripts</td></tr>
</tbody>
</table>

<p><em>✅ = Native built-in &nbsp;&bull;&nbsp; ⚠️ = Partial / Manual URL / Plugin required &nbsp;&bull;&nbsp; ❌ = Not supported</em></p>

<br/>


## ✦ At a glance

| Experience | Highlights |
|---|---|
| 🎧 **OliX Audio** | 10-band EQ · 48-band visualizer · spatial audio |
| 🤖 **AI tools** | Offline subtitles · Gemini integrations · bilingual lyrics |
| 🌐 **Six studios** | TV · Music · Podcast · Anime · Video · Browser |
| 📺 **Live TV** | Project-reported catalogue of 26,775+ channels |
| ⚡ **Video engine** | LibVLC playback with supported hardware decoding |
| 📻 **FM radio** | Online radio and RTL-SDR hardware tuner |

## ✦ What's new in v1.18

**SANDYPLAY v1.18 Ultimate Edition** brings together audio, streaming, AI tools and desktop improvements.

| Upgrade | Details |
|---|---|
| **OliX Audio Technology™** | Unified audio architecture, equalizer, spatializer, speaker profiles and spectrum visualizer |
| **Dolby Studio** | Dedicated Dolby.io cloud dynamic-mastering module |
| **Live TV catalogue** | Project-reported 26,775+ channels organized by genre, language and region |
| **Catalogue virtualization** | Background loading and deferred rendering to reduce interface blocking |
| **Adaptive streaming buffer** | LibVLC network, live and file caching configured at 6,000 ms |
| **HDR Master Tuner** | Cinema, Anime, Vivid HDR and Dark Room presets |
| **Anime multi-audio** | Multi-server resolver, episode sequencing and dual-source audio synchronization |
| **Windows installer** | Setup wizard, process management, uninstallation lifecycle and file associations |

## ✦ Features

### 🤖 AI, subtitles & smart playback

- **Offline Faster-Whisper subtitles** — local transcription using Faster-Whisper, CTranslate2 and Silero VAD after the required model is downloaded.
- **Sandytalks AI Assistant** — conversational assistant integrations using Google Dialogflow and Gemini.
- **Media summaries** — ask questions about currently playing media and generate summaries where supported.
- **Bilingual synced lyrics** — display original and translated lyrics side by side.
- **Natural-language command palette** — use `Ctrl + K` to access supported commands.

### 🌐 The six studios

| Studio | Capabilities |
|---|---|
| 📺 **Online TV** | Global live-channel catalogue, genre/language/region categories, stream mirrors and M3U import/export |
| 🎵 **Online Music** | Music discovery, regional categories, streaming, synced LRC lyrics and album art |
| 🎙️ **Podcast** | Podcast discovery, search and background episode downloads |
| ⛩️ **Anime** | Seasonal anime discovery, subtitles, dub options and dual-source audio synchronization |
| 🎬 **Online Video** | Video search, supported high-resolution streams and parallel stream proxy |
| 🌐 **Sandy Browser** | QtWebEngine browser, multi-tab browsing, AdBlock and download manager |

### 🎧 OliX Audio Technology™

A dedicated audio experience designed as a core part of SANDYPLAY.

| Component | Description |
|---|---|
| **OliX Signature Sound** | Dynamic bass, spatial depth and soundstage processing |
| **10-Band Graphic EQ** | 32 Hz–16 kHz control with Signature Dynamic, Bass Boost, Vocal Clarity, Rock, Electronic, Classical, Flat and Custom presets |
| **DTS Studio Surround Spatializer** | Spatial modes and listening presets for Movies, Music and Gaming |
| **48-Band Spectrum Visualizer** | Real-time frequency visualization synchronized with playback |
| **Speaker Profiles** | Profiles designed for headphones, laptop speakers, desktop monitors and external HiFi systems |
| **SoX HiFi Resampler** | Audio resampling integrated into the OliX audio architecture |

#### Dolby Studio · Cloud Dynamic Mastering

A separate cloud module powered by Dolby.io APIs. It is designed to enhance uploaded recordings through cloud-based mastering, including frequency balance and vocal presentation.

> Dolby Studio is a dedicated cloud feature. It is not the audio engine for the entire application.

### ⚡ Hardware & playback engine

- **LibVLC playback** — hardware video decoding support through available GPU paths such as NVDEC, QuickSync and DXVA2.
- **RTL-SDR FM tuner** — with a compatible RTL2832U dongle and antenna, tune supported 76–108 MHz FM broadcasts.
- **Parallel Stream Proxy** — internal multi-threaded HTTP proxy on port `8125`.
- **HDR controls** — adjust contrast, brightness, saturation, gamma and hue.
- **Media downloader** — multi-threaded chunk downloading with FFmpeg remuxing support.

## ✦ Interface preview

```text
┌────────────────────────────────────────────────────────────────────────┐
│  SANDYPLAY AI MULTIMEDIA STUDIO v1.18               [ - ] [ # ] [ X ]  │
├────────────────────────────────────────────────────────────────────────┤
│  [ TV (26k+) ] [ Music ] [ Podcast ] [ Anime ] [ Video ] [ Browser ]   │
├────────────────────────────────────────┬───────────────────────────────┤
│                                        │  SYNCED BILINGUAL LYRICS      │
│                                        │                               │
│             4K HDR LIBVLC              │  Original:   Stay with me     │
│          VIDEO / AUDIO CANVAS          │  Translated: Ennodu Iru       │
│                                        │                               │
│       [ Offline Whisper AI CC ]        │  ┌─────────────────────────┐  │
│       [ OliX Audio Technology ]        │  │ 48-Band Audio Spectrum  │  │
│       [ 6000ms Adaptive Buffer ]       │  └─────────────────────────┘  │
├────────────────────────────────────────┴───────────────────────────────┤
│  |>  |<<  >>|   02:14 / 04:30  ======O==============  85%  [OliX 10-EQ]│
└────────────────────────────────────────────────────────────────────────┘
```

</details>

## ✦ Download

<div align="center">

### SANDYPLAY v1.18 · Windows 10 / 11 · 64-bit

[![Download SANDYPLAY](https://img.shields.io/badge/DOWNLOAD-SANDYPLAY%20v1.18-0EA5E9?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/sandytalks/SANDYPLAY/releases/download/sandyplay1.18/SandyPlay_Setup_v1.18.exe)

[All releases](https://github.com/sandytalks/SANDYPLAY/releases) · [Source code](https://github.com/sandytalks/SANDYPLAY) · [Report an issue](https://github.com/sandytalks/SANDYPLAY/issues)

</div>

## ✦ Installation

1. Download `SandyPlay_Setup_v1.18.exe` from the release link above.
2. Run the installer on a supported 64-bit Windows system.
3. Follow the setup wizard.
4. Launch SANDYPLAY from the desktop or Start menu.

The project describes the installer as bundling the LibVLC engine, OliX Audio core, Faster-Whisper runtimes, codecs and Visual C++ dependencies.

## ✦ Keyboard shortcuts

| Shortcut | Action | Shortcut | Action |
|:---:|---|:---:|---|
| `Space` | Play / Pause | `[` / `]` | Playback speed |
| `F` / `Enter` | Fullscreen | `C` | Aspect ratio / crop |
| `N` / `B` | Next / Previous track | `Ctrl + L` | Floating lyrics |
| `←` / `→` | Seek 10 seconds | `Ctrl + T` | AI subtitles |
| `↑` / `↓` | Volume ±5% | `F5` | Equalizer / OliX DSP |
| `M` | Mute / Unmute | `Ctrl + O` | Open media |
| `Ctrl + U` | Open network stream | `Ctrl + K` | AI command palette |
| `E` / `W` | OliX gapless crossfade | `?` | Keyboard help |

## ✦ System requirements

| Component | Minimum | Recommended |
|---|---|---|
| Operating system | Windows 10 64-bit (Build 17763+) | Windows 11 64-bit |
| CPU | Dual-Core 2.0 GHz x64 | Quad-Core 3.0 GHz+ |
| RAM | 4 GB | 8–16 GB |
| GPU | DirectX 11 compatible integrated graphics | NVIDIA GTX 1060+ / RTX |
| Storage | 600 MB | 3 GB+ |
| Network | Offline for local media and FM | Broadband for online studios |

## ✦ Development roadmap

| Status | Milestone | Version |
|---|---|---|
| ✅ Completed | Lyrics Engine, Dolby Studio Cloud, Faster-Whisper AI, Hardware FM | v1.14–v1.16 |
| ✅ Completed | Offline Whisper AI CC, RTL-SDR FM tuner, Glassmorphism UI | v1.17 |
| 🚀 Current | OliX Audio core, Live TV catalogue, virtualization, adaptive buffer, Anime multi-audio, HDR and installer | v1.18 |
| 📋 In progress | Audio Relay for synchronized multi-device streaming | v1.19 |
| 📋 Planned | Online OTT Studio | v1.20 |
| 💡 Future | Discord Rich Presence, Watch Party Sync, DJ Performance Mode, macOS support | Future |

## ✦ Technology stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,qt,windows,git,github&theme=dark" alt="Technology stack icons">
</p>

| Area | Technology |
|---|---|
| Core | Python 3.12+, PyInstaller |
| Desktop UI | PyQt6, QtWebEngine |
| Media | LibVLC, FFmpeg |
| Audio | OliX Audio Technology™, SoX |
| AI transcription | Faster-Whisper, CTranslate2, ONNX Runtime, Silero VAD |
| AI integrations | Google Dialogflow, Gemini |
| Hardware radio | RTL-SDR |
| Networking | WinDivert / GoodbyeDPI, DNS-over-HTTPS |
| Installer | Inno Setup 6 |

## ✦ Frequently asked questions

<details>
<summary><strong>What powers SANDYPLAY audio?</strong></summary>

OliX Audio Technology™ powers the application's audio architecture, including its 10-band equalizer, speaker profiles, 48-band visualizer, spatializer and SoX resampling. Dolby.io is used specifically by the separate Dolby Studio cloud mastering module.
</details>

<details>
<summary><strong>Do AI subtitles need an internet connection?</strong></summary>

The project describes Faster-Whisper transcription as local/offline after the required model has been downloaded and installed.
</details>

<details>
<summary><strong>Can I use FM radio without internet?</strong></summary>

Yes. With a compatible RTL2832U SDR USB tuner and antenna, the RTL-SDR FM tuner can receive supported over-the-air FM broadcasts.
</details>

<details>
<summary><strong>Do I need API keys?</strong></summary>

The project states that core local playback and audio features do not require API keys. Some connected AI and cloud services may have their own service requirements.
</details>

<details>
<summary><strong>How does SANDYPLAY support slow connections?</strong></summary>

The v1.18 configuration describes 6,000 ms LibVLC network, live and file caching, along with automatic reconnect behavior.
</details>

## ✦ Contributing

SANDYPLAY is presented as free and open-source software. Feedback and contributions are welcome.

<div align="center">

[![Report a bug](https://img.shields.io/badge/REPORT_A_BUG-EF4444?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sandytalks/SANDYPLAY/issues)
[![Pull requests](https://img.shields.io/badge/SUBMIT_A_PR-16A34A?style=for-the-badge&logo=git&logoColor=white)](https://github.com/sandytalks/SANDYPLAY/pulls)
[![Discussions](https://img.shields.io/badge/JOIN_DISCUSSIONS-7C3AED?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sandytalks/SANDYPLAY/discussions)

</div>

## ✦ License

**GPL-3.0** — Copyright © 2026 Sandytalks Devops.

Third-party components have their own licenses and terms, including LibVLC, FFmpeg, Faster-Whisper, PyQt6, yt-dlp, Dolby.io, Google Gemini API, GoodbyeDPI and Silero VAD.

---

<div align="center">

### BUILT WITH ❤️ BY SANDYTALKS

[GitHub](https://github.com/sandytalks) · [Instagram](https://www.instagram.com/sandyplay/) · [Get SANDYPLAY](https://github.com/sandytalks/SANDYPLAY/releases)

[![Star SANDYPLAY](https://img.shields.io/badge/⭐_STAR_SANDYPLAY-SUPPORT_THE_PROJECT-22D3EE?style=for-the-badge&logo=github&logoColor=0B1020)](https://github.com/sandytalks/SANDYPLAY)

*Designed for the ones who experience more than just media.*

</div>
