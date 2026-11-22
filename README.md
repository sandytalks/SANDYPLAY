<div align="center">

  <img src="app_icon.png" alt="SANDYPLAY Logo" width="130" height="130">
  
  <h1>SANDYPLAY Media Player</h1>
  
  <p>
    <em>The ultimate AI-powered multimedia studio with audio powered by <b>OliX Audio Technology™</b>. Built for audiophiles, cinephiles, and power streamers.</em>
  </p>

  <p>
    <a href="https://github.com/sandytalks/SANDYPLAY/releases/latest"><img src="https://img.shields.io/static/v1?label=Release&message=v1.18%20Ultimate&color=0ea5e9&style=for-the-badge&logo=github" alt="Release v1.18"/></a>&nbsp;
    <a href="#audio-engine"><img src="https://img.shields.io/static/v1?label=Audio%20Engine&message=OliX%20Audio%20Technology%E2%84%A2&color=8b5cf6&style=for-the-badge" alt="OliX Audio Technology"/></a>&nbsp;
    <a href="https://github.com/sandytalks/SANDYPLAY/releases"><img src="https://img.shields.io/static/v1?label=Platform&message=Windows%2010%20%7C%2011&color=0078D6&style=for-the-badge&logo=windows" alt="Windows"/></a>&nbsp;
    <a href="https://python.org"><img src="https://img.shields.io/static/v1?label=Python&message=3.12%2B&color=3776AB&style=for-the-badge&logo=python" alt="Python 3.12+"/></a>&nbsp;
    <a href="https://www.videolan.org/"><img src="https://img.shields.io/static/v1?label=Engine&message=LibVLC%204K%20HDR&color=FF8800&style=for-the-badge&logo=vlc" alt="LibVLC"/></a>&nbsp;
    <a href="https://github.com/sandytalks/SANDYPLAY"><img src="https://img.shields.io/static/v1?label=AI%20Engine&message=Faster--Whisper%20%7C%20Gemini&color=8E75B2&style=for-the-badge" alt="AI Engine"/></a>&nbsp;
    <a href="https://github.com/sandytalks/SANDYPLAY/blob/main/LICENSE"><img src="https://img.shields.io/static/v1?label=License&message=GPL%203.0&color=22c55e&style=for-the-badge" alt="License"/></a>
  </p>

  <p>
    <a href="#the-definitive-comparison"><strong>🏆 Comparison</strong></a> &nbsp;•&nbsp;
    <a href="#whats-new"><strong>🌟 What's New in v1.18</strong></a> &nbsp;•&nbsp;
    <a href="#olix-audio"><strong>🎧 OliX Audio</strong></a> &nbsp;•&nbsp;
    <a href="#features"><strong>✨ Features</strong></a> &nbsp;•&nbsp;
    <a href="#studios"><strong>🌐 The 6 Studios</strong></a> &nbsp;•&nbsp;
    <a href="#hardware"><strong>⚡ Hardware Engine</strong></a> &nbsp;•&nbsp;
    <a href="#showcase"><strong>📸 Showcase</strong></a> &nbsp;•&nbsp;
    <a href="#installation"><strong>🚀 Installation</strong></a> &nbsp;•&nbsp;
    <a href="#shortcuts"><strong>⌨️ Shortcuts</strong></a> &nbsp;•&nbsp;
    <a href="#requirements"><strong>⚙️ Specs</strong></a> &nbsp;•&nbsp;
    <a href="#roadmap"><strong>🗺️ Roadmap</strong></a> &nbsp;•&nbsp;
    <a href="#contributing"><strong>🤝 Community</strong></a>
  </p>
</div>

---

> [!IMPORTANT]
> **Audio Powered by OliX Audio Technology™**:  
> Every audio stream, 10-band equalizer, 48-band spectrum visualizer, SoX HiFi resampler, 10 speaker profiles, across the entire application is engineered by **OliX Audio Technology™**.  
> **Dolby Studio**: Dolby technology is featured specifically as a dedicated cloud audio dynamic mastering module (**Dolby Studio** via Dolby.io) for one-click recording enhancement.

---

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

---

<h2 id="whats-new">🌟 What's New in v1.18 Ultimate Edition</h2>

* 🎧 **Audio by OliX Audio Technology™**: Unified audio architecture across the entire player.
* ☁️ **Dolby Studio (Dedicated Cloud Mastering)**: Specific, dedicated cloud audio dynamic mastering module powered by Dolby.io REST APIs for one-click audio enhancement, vocal clarity, and bass balancing.
* 📺 **Massive 26,775+ Channel Live TV Studio**: Expanded global live television database categorized by Genre, Language, Country/Region, and Favorites. Includes verified HD live streams for Star Vijay, Vijay Super, Zee Tamil, Sun TV, Thanthi One, Polimer TV, Asianet HD, NDTV 24x7, Republic TV, and hundreds more with automatic mirror failovers.
* ⚡ **Zero-Lag Asynchronous Catalog Virtualization**: Fully decoupled background network loading from the Qt GUI thread. Implemented tab-aware deferred rendering and uniform 800-channel instant slicing, reducing channel catalog rendering time from ~8.0 seconds down to **0.018 seconds (450x faster)**. Completely eliminates GUI freezing and Windows *"Not Responding"* hangs on slow or fluctuating internet connections.
* 🌐 **Adaptive 6,000ms Slow-Internet Buffer Engine**: Quadrupled LibVLC network caching (`:network-caching=6000`, `:live-caching=6000`, `:file-caching=6000`) with `:ipv4-timeout=5000` and `:http-continuous=1`. Video and live TV streams automatically absorb jitter, packet drops, and bandwidth dips without stuttering or breaking playback loops.
* 🎨 **HDR Modes**: Dynamic real-time post-processing controls for contrast, brightness, saturation, gamma, and hue with hardware acceleration and one-click presets for **Cinema**, **Anime**, **Vivid HDR**, and **Dark Room** viewing.
* ⛩️ **Anime Multi-Audio Synchronization**: Multi-server resolver with dual-source sync for Japanese, English, Tamil, and Hindi dubs. Features episode auto-sequencing, AnimeSalt audio slave injection, and background episode downloading.
* 🛡️ **Hardened GoodbyeDPI & Sophos Bypass**: Automated packet filtering via WinDivert and automatic injection of `SecurityAppliance_SSL_CA.pem` preventing HTTPS blocking and ISP SNI throttling on campus and enterprise networks.
* 📦 **Production Setup v1.18 Installer**: Professional dark cyber-themed setup wizard, automated process management, clean uninstallation lifecycle, firewall rule creation, and full Windows 10/11 Explorer file associations.

---

<h2 id="olix-audio"> OliX Audio Technology™ </h2>

The entire audio architecture in SANDYPLAY is engineered from the ground up by **OliX Audio Technology™**:


* **OliX Signature Sound**: Flagship dynamic bass and 3D spatial acoustic engine delivering holographic depth, binaural soundstage widening, and pristine high-frequency clarity.
* **OliX Hardware Speaker Profiles**: Auto-adaptive hardware loudness matching. Automatically optimizes audio characteristics whether you are using studio headphones, laptop speakers (preventing driver distortion), desktop monitors, or high-end external HiFi amplifiers.
* **OliX DTS Studio Surround Spatializer**: Converts conventional 2-channel stereo into an expansive 3D audio space with presets tailored for **Movies**, **Music**, and **Gaming**.
* **OliX 10-Band Graphic Equalizer**: Precision parametric graphic equalizer spanning 32 Hz to 16 kHz with built-in presets (OliX Signature Dynamic, Bass Boost, Vocal Clarity, Rock, Electronic, Classical, Flat, and Custom).
* **OliX 48-Band Spectrum Visualizer**: Dynamic visual representation of audio frequency bands, reacting synchronously to music dynamics with smooth peak decay.
* **Dolby Studio (Cloud Dynamic Mastering)**: An exclusive dedicated cloud module using Dolby.io APIs. Upload any muddy, quiet, or unbalanced audio recording to Dolby's mastering cloud with one click to balance frequencies, reduce background noise, and master vocals to broadcast standards.

---

<h2 id="features">✨ Comprehensive Feature Tour</h2>

### 🤖 1. Artificial Intelligence &amp; Subtitles
* **Offline Faster-Whisper AI Subtitles**: Watching a foreign or untranslated video? Press <kbd>Ctrl</kbd> + <kbd>T</kbd>. SANDYPLAY executes a local `faster-whisper` + `ctranslate2` model accelerated by Silero VAD v6 to transcribe audio into synchronized subtitles in real time—**100% locally and completely offline without cloud latency**.
* **Sandytalks AI Assistant**: An intelligent conversational AI sidebar powered by Google Dialogflow and Gemini. Ask questions about the currently playing video or song, generate summaries, break down complex plots, or translate dialogue into your native tongue.
* **Smart Bilingual Synced Lyrics**: Displays original song lyrics alongside synchronized translated lyrics side-by-side (English, Tamil, Hindi, Telugu, Korean, Japanese, and more) so you always connect with the meaning.
* **Natural Language Command Palette**: Press <kbd>Ctrl</kbd> + <kbd>K</kbd> to trigger the AI command palette. Type natural commands (*"Play trending Tamil melody songs"*, *"Boost volume to 120%"*, *"Set sleep timer to 30 minutes"*), and SANDYPLAY executes them instantly.

### 🌐 2. The 6 Dedicated Online Studios

Accessible directly from the top navigation bar, SANDYPLAY embeds 6 dedicated streaming hubs:

| Studio | Highlights &amp; Capabilities |
| :--- | :--- |
| **📺 Online TV Studio** | Access **26,775+ Global Live Channels** across News, Sports, Entertainment, Movies, and Regional TV (India, USA, UK, Europe, Latin America, Asia). Features zero-lag catalog virtualization, stream health checking, verified HD mirrors, and M3U playlist import/export. |
| **🎵 Online Music Studio** | Explore global top charts, trending hits, and regional music (Tamil, Hindi, Telugu, Punjabi, Malayalam, International Pop). Streams up to **320kbps** with DES decryption, synced LRC lyrics, and album art extraction. |
| **🎙️ Online Podcast Studio** | Search and stream millions of podcast episodes and Podcast Index with background episode downloading. |
| **⛩️ Online Anime Studio** | Browse trending and seasonal anime with Japanese audio, English subtitles, and multi-language dubs (Tamil, Hindi, English). Supports dual-source audio synchronization and background episode downloading. |
| **🎬 Online Video Studio** | Web video search engine. Streams 1080p, 2K, and 4K video through a local parallel proxy (`ParallelStreamProxy` on port 8125) with multi-chunk prefetching for zero-buffering playback. |
| **🌐 Sandy Web Browser** | Integrated Chromium browser powered by QtWebEngine featuring multi-tab browsing, built-in ad blocker (`🛡️ AdBlock`), persistent sessions, download manager, and synchronized dark cyberpunk theme. |

---

<h2 id="hardware">⚡ Hardware Acceleration &amp; Core Engine</h2>

* **LibVLC 4K/8K NVDEC GPU Acceleration**: Direct hardware video decoding via NVIDIA CUDA, Intel QuickSync, and AMD DXVA2 allows effortless playback of high-bitrate 4K and 8K HDR content with near-zero CPU consumption.
* **RTL-SDR USB Hardware FM Tuner**: Plug any RTL2832U software-defined radio USB dongle into your PC, navigate to **FM Radio**, and listen to local over-the-air wideband FM broadcasts (76–108 MHz) completely offline. Features automatic frequency scanning, signal strength meter, and squelch threshold adjustment.
* **Parallel Stream Proxy (Port 8125)**: An internal multi-threaded HTTP proxy server that segments and downloads online media streams in parallel, ensuring smooth continuous playback even on restricted or throttled connections.
* **HDR**: Fine-tune contrast, brightness, saturation, gamma, and color hue in real-time with zero latency.
* **High-Speed Stream Downloader**: Built-in multi-threaded chunked downloader with automatic `ffmpeg` remuxing for video, audio, and subtitle streams.

---

<h2 id="showcase">📸 Interface Preview &amp; Showcase</h2>

<details open>
<summary><strong>📐 Click to toggle &mdash; UI Layout Architecture Diagram</strong></summary>
<br/>

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

---

<h2 id="installation">🚀 Quick Installation</h2>

### Windows 10 / 11 (64-bit)

<div align="center">
  <h3>Get the Official SANDYPLAY Setup v1.18:</h3>
  
  <a href="https://github.com/sandytalks/SANDYPLAY/releases/download/sandyplay1.18/SandyPlay_Setup_v1.18.exe">
    <img src="https://img.shields.io/static/v1?label=DOWNLOAD&message=SANDYPLAY%20v1.18%20INSTALLER&color=0ea5e9&style=for-the-badge&logo=windows&logoColor=white&labelColor=020c1b" height="42" alt="Download SandyPlay Setup v1.18"/>
  </a>
  <br/><br/>
  <p>
    <em>Version 1.18 &bull; Windows 10/11 (64-bit) &bull; </em>
  </p>
</div>

> [!IMPORTANT]  
> 1. Download **`SandyPlay_Setup_v1.18.exe`** from the release button above.
> 2. Run the installer &mdash; it bundles the complete LibVLC 4K Engine, OliX Audio Technology core, Faster-Whisper runtimes, codecs, and Visual C++ dependencies.
> 3. Launch SANDYPLAY from your desktop or start menu and start enjoying your media!

<br/>

---

<h2 id="shortcuts">⌨️ Keyboard Shortcuts</h2>

| Shortcut | Action | Shortcut | Action |
| :---: | :--- | :---: | :--- |
| <kbd>Space</kbd> | Play / Pause | <kbd>[</kbd> / <kbd>]</kbd> | Decrease / Increase Playback Speed |
| <kbd>F</kbd> / <kbd>Enter</kbd> | Toggle Fullscreen Mode | <kbd>C</kbd> | Cycle Aspect Ratio / Crop |
| <kbd>N</kbd> / <kbd>B</kbd> | Next / Previous Track | <kbd>Ctrl</kbd> + <kbd>L</kbd> | Toggle Floating Lyrics Panel |
| <kbd>→</kbd> / <kbd>←</kbd> | Seek Forward / Backward 10s | <kbd>Ctrl</kbd> + <kbd>T</kbd> | Toggle Offline Faster-Whisper AI Subtitles |
| <kbd>↑</kbd> / <kbd>↓</kbd> | Adjust Volume (&plusmn;5%) | <kbd>F5</kbd> | Open Equalizer &amp; OliX Audio DSP Dialog |
| <kbd>M</kbd> | Mute / Unmute Audio | <kbd>Ctrl</kbd> + <kbd>O</kbd> | Open Media File |
| <kbd>Ctrl</kbd> + <kbd>U</kbd> | Open Network Stream URL | <kbd>Ctrl</kbd> + <kbd>K</kbd> | Open AI Command Palette |
| <kbd>E</kbd> / <kbd>W</kbd> | OliX Gapless Crossfade Next / Prev | <kbd>?</kbd> | Open Interactive Keyboard Help Guide |

---

<h2 id="requirements">⚙️ System Requirements</h2>

<table width="100%">
<thead>
<tr>
  <th align="left" width="20%">Component</th>
  <th align="left" width="40%">Minimum Specification</th>
  <th align="left" width="40%">Recommended Specification</th>
</tr>
</thead>
<tbody>
<tr><td><b>Operating System</b></td><td>Windows 10 64-bit (Build 17763+)</td><td>Windows 11 64-bit</td></tr>
<tr><td><b>Processor (CPU)</b></td><td>Dual-Core 2.0 GHz x64</td><td>Quad-Core 3.0 GHz+ (Intel Core i5/i7 or AMD Ryzen 5/7)</td></tr>
<tr><td><b>System Memory (RAM)</b></td><td>4 GB</td><td>8 GB &ndash; 16 GB</td></tr>
<tr><td><b>Graphics Card (GPU)</b></td><td>DirectX 11 compatible integrated graphics</td><td>NVIDIA GTX 1060+ / RTX (NVDEC 4K/8K hardware decoding)</td></tr>
<tr><td><b>Storage Space</b></td><td>600 MB application space</td><td>3 GB+ (Whisper AI models &amp; stream caching)</td></tr>
<tr><td><b>Network Connection</b></td><td>Offline for local files &amp; FM radio</td><td>Broadband for 4K video, 26k+ TV channels &amp; online studios</td></tr>
</tbody>
</table>

<br/>

---

<h2 id="faq">❓ Frequently Asked Questions</h2>

<details>
<summary><strong>What audio technology powers SANDYPLAY?</strong></summary>
<br/>
<p>The entire application's audio processing, 10-band graphic equalizer, 10 speaker profiles, 48-band spectrum visualizer, and SoX resampler are powered exclusively by <b>OliX Audio Technology™</b>. Dolby is used specifically and solely for the <b>Dolby Studio</b> cloud audio mastering feature via Dolby.io.</p>
</details>

<details>
<summary><strong>How does the Live TV Studio handle slow internet connections?</strong></summary>
<br/>
<p>SANDYPLAY v1.18 employs a multi-tiered architecture: <b>1) Zero-lag catalog slicing</b> keeps the UI instantaneous (0.018s rendering) regardless of network speed. <b>2) LibVLC network cache is boosted to 6,000ms</b> with automatic reconnect, preventing playback stutter. <b>3) Playlists are cached for 7 days</b>, avoiding redundant downloads on startup.</p>
</details>

<details>
<summary><strong>Does Faster-Whisper AI subtitles require an active internet connection?</strong></summary>
<br/>
<p>No. After the initial automated model download, Faster-Whisper runs <b>100% locally and completely offline</b> on your CPU/GPU using CTranslate2 and Silero VAD v6. No voice or video data is ever sent to external servers.</p>
</details>

<details>
<summary><strong>How does the campus/college network bypass work?</strong></summary>
<br/>
<p>SANDYPLAY auto-detects <code>SecurityAppliance_SSL_CA.pem</code> in the installation directory and automatically injects it into all SSL contexts, Python requests, and yt-dlp sessions. In combination with built-in GoodbyeDPI (WinDivert), it bypasses deep packet inspection (DPI) and SNI filtering without requiring manual proxy setup.</p>
</details>

<details>
<summary><strong>Do I need API keys to use SANDYPLAY?</strong></summary>
<br/>
<p><b>No API keys are required</b> for any core functionality: local media playback, OliX Audio DSP, 26,775+ TV channels, 320kbps music streaming, anime, podcasts, equalizer, DTS spatializer, 48-band visualizer, or FM radio. A built-in key powers Sandytalks AI out of the box.</p>
</details>

<details>
<summary><strong>How do I listen to offline FM radio with RTL-SDR?</strong></summary>
<br/>
<p>Plug an RTL2832U USB tuner dongle into your PC with its antenna attached. Open <b>FM Radio</b> from the player. SANDYPLAY automatically connects to the hardware, pipes the raw I/Q stream through an internal demodulator pipeline, and plays crisp over-the-air FM radio without using any internet data.</p>
</details>

<br/>

---

<h2 id="roadmap">🗺️ Development Roadmap</h2>

<table width="100%">
<thead>
<tr>
  <th align="center" width="18%">Status</th>
  <th align="left">Milestone Highlights</th>
  <th align="center" width="18%">Version</th>
</tr>
</thead>
<tbody>
<tr><td align="center">✅ <b>Completed</b></td><td>Lyrics Engine &bull; Dolby Studio Cloud &bull; Faster-Whisper AI &bull; Hardware FM</td><td align="center">v1.14 &ndash; v1.16</td></tr>
<tr><td align="center">✅ <b>Completed</b></td><td>Offline Whisper AI CC &bull; RTL-SDR FM Tuner &bull; Glassmorphism High-DPI UI</td><td align="center">v1.17</td></tr>
<tr><td align="center">🚀 <b>Current</b></td><td><b>v1.18 Ultimate Edition &bull; OliX Audio Technology™ Core &bull; 26,775+ Live TV Channels &bull; Zero-Lag Virtualization &bull; 6,000ms Buffer &bull; Anime Multi-Audio &bull; HDR Master Tuner &bull; Setup v1.18</b></td><td align="center"><b>v1.18</b></td></tr>
<tr><td align="center">📋 <b>In Progress</b></td><td><b>Audio Relay for SandyPlay (Multi-device low-latency synchronized streaming)</b></td><td align="center"><b>v1.19</b></td></tr>
<tr><td align="center">📋 <b>Planned</b></td><td><b>Online OTT Studio (Integrated streaming hub)</b></td><td align="center"><b>v1.20</b></td></tr>
<tr><td align="center">💡 <b>Future</b></td><td>Discord Rich Presence &bull; Watch Party Sync &bull; DJ Performance Mode &bull; macOS Support</td><td align="center">Future</td></tr>
</tbody>
</table>

<br/>

---

<h2 id="tech-stack">🛠️ Technology Stack</h2>

<p align="center">
  <img src="https://img.shields.io/static/v1?label=Python&message=3.12%2B&color=3776AB&style=for-the-badge&logo=python" alt="Python"/>&nbsp;
  <img src="https://img.shields.io/static/v1?label=Audio&message=OliX%20Audio%20Technology%E2%84%A2&color=8B5CF6&style=for-the-badge" alt="OliX Audio"/>&nbsp;
  <img src="https://img.shields.io/static/v1?label=GUI&message=PyQt6&color=41CD52&style=for-the-badge" alt="PyQt6"/>&nbsp;
  <img src="https://img.shields.io/static/v1?label=Engine&message=LibVLC%204K&color=FF8800&style=for-the-badge&logo=vlc" alt="LibVLC"/>&nbsp;
  <img src="https://img.shields.io/static/v1?label=AI&message=Faster--Whisper&color=412991&style=for-the-badge" alt="Whisper"/>&nbsp;
  <img src="https://img.shields.io/static/v1?label=Cloud%20Mastering&message=Dolby.io&color=000000&style=for-the-badge" alt="Dolby.io"/>&nbsp;
  <img src="https://img.shields.io/static/v1?label=Hardware&message=RTL--SDR&color=E34F26&style=for-the-badge" alt="RTL-SDR"/>&nbsp;
  <img src="https://img.shields.io/static/v1?label=Installer&message=Inno%20Setup%206&color=00599C&style=for-the-badge" alt="Inno Setup"/>
</p>

* **Audio:** OliX Audio Technology™ (Full Core, 10-band Graphic EQ, 48-band Spectrum Visualizer, DTS 3D Spatializer, SoX HiFi Resampler)
* **Cloud Audio Dynamic Mastering:** Dolby.io Media Processing REST APIs (Dedicated exclusively to the Dolby Studio module)
* **Core Framework:** Python 3.12+ (PyInstaller 6 flat onedir deployment architecture)
* **Graphical Interface:** PyQt6 &amp; QtWebEngine (Cyberpunk Dark Glassmorphism, Dynamic Accent Palettes)
* **Media Playback Engine:** 64-bit LibVLC with full hardware acceleration (NVDEC, DXVA2, CUDA)
* **Local Machine Learning:** `faster-whisper` + `ctranslate2` + `onnxruntime` + Silero VAD v6
* **Software-Defined Radio:** `rtl-sdr` (`rtl_fm` streaming pipeline)
* **Network Acceleration &amp; Bypass:** `goodbyedpi` Windows WinDivert packet filter &amp; DNS-over-HTTPS (DoH)
* **Packaging &amp; Installer:** Inno Setup 6 (LZMA2 Ultra64 Solid Compression, Explorer shell refresh)

---

<h2 id="contributing">🤝 Contributing &amp; Community</h2>

<p align="center">
  <em>SANDYPLAY is free and open-source software. Community feedback, bug reports, and code contributions are always welcome!</em>
</p>

<p align="center">
  ⭐ Star the repository &nbsp;&bull;&nbsp; 🐛 Report bugs &nbsp;&bull;&nbsp; 💡 Suggest features &nbsp;&bull;&nbsp; 📻 Add radio stations &nbsp;&bull;&nbsp; 🎌 Improve stream scrapers &nbsp;&bull;&nbsp; 📣 Share with friends
</p>

<div align="center">
  <a href="https://github.com/sandytalks/SANDYPLAY/issues"><img src="https://img.shields.io/static/v1?label=Issues&message=Report%20Bug&color=ef4444&style=for-the-badge&logo=github" alt="Issues"/></a>&nbsp;&nbsp;
  <a href="https://github.com/sandytalks/SANDYPLAY/pulls"><img src="https://img.shields.io/static/v1?label=PRs&message=Welcome&color=22c55e&style=for-the-badge&logo=git" alt="PRs"/></a>&nbsp;&nbsp;
  <a href="https://github.com/sandytalks/SANDYPLAY/discussions"><img src="https://img.shields.io/static/v1?label=Discussions&message=Community&color=8b5cf6&style=for-the-badge" alt="Discussions"/></a>
</div>

<br/>

---

<h2 id="license">📄 License</h2>

<p><b>GPL 3.0 License</b> &mdash; Copyright &copy; 2026 Sandytalks Devops</p>

<sub>Third-party: LibVLC (LGPL) &bull; FFmpeg (LGPL/GPL) &bull; Faster-Whisper (MIT) &bull; PyQt6 (GPL) &bull; yt-dlp (Unlicense) &bull; Dolby.io &bull; Google Gemini API &bull; GoodbyeDPI (MIT) &bull; Silero VAD (MIT)</sub>

<br/><br/>

---

<div align="center">

<p><strong>Built with ❤️ by <a href="https://www.instagram.com/sandyplay/">Sandy</a></strong></p>

<p>
  <a href="https://www.instagram.com/sandyplay/"><img src="https://img.shields.io/static/v1?label=Instagram&message=@sandyplay&color=E4405F&style=for-the-badge&logo=instagram" alt="Instagram"/></a>&nbsp;&nbsp;
  <a href="https://github.com/sandytalks/SANDYPLAY"><img src="https://img.shields.io/static/v1?label=GitHub&message=sandytalks&color=181717&style=for-the-badge&logo=github" alt="GitHub"/></a>
</p>

<br/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=sandytalks/SANDYPLAY&type=Date&theme=dark"/>
  <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=sandytalks/SANDYPLAY&type=Date"/>
  <img src="https://api.star-history.com/svg?repos=sandytalks/SANDYPLAY&type=Date&theme=dark" alt="Star History" width="65%"/>
</picture>

<br/><br/>

<p>⭐ <b>If SANDYPLAY elevated your media experience &mdash; star the repository to fuel the next version!</b></p>

</div>

<br/>
