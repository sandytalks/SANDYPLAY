# Privacy Policy for SANDYPLAY Media Player

**Effective Date:** November 2026 
**Application:** SANDYPLAY Media Player  
**Developer:** Sandytalks Devops &bull; [GitHub Repository](https://github.com/sandytalks/SANDYPLAY) &bull; [Official Portal](https://www.instagram.com/sandyplay/)

---

### Introduction & Core Privacy Philosophy

SANDYPLAY is an open-source, client-side multimedia player, streaming studio, and Audio acoustic suite developed by Sandytalks. 

> **Our Promise:**  
> **SANDYPLAY does NOT collect, store, sell, or transmit any personal data, telemetry, usage statistics, or crash reports to any developer-owned or private servers.**  
> SANDYPLAY is architected from the ground up as a decentralized, privacy-first desktop application. The application runs locally on your machine, and your media files, playback habits, and credentials remain solely in your custody.

---

### 1. Data We Do NOT Collect

* **No Analytics or Telemetry:** There are zero tracking SDKs, analytics beacons (Google Analytics, Mixpanel, etc.), or usage monitors compiled into the application.
* **No Account Creation:** You do not need to register an account with Sandytalks to use SANDYPLAY.
* **No Media Scanning or Logging:** The developer does not know what songs, videos, radio streams, live TV channels, or local files you open, stream, or download.
* **No Remote Keylogging or Prompts Snooping:** Prompts entered into the AI assistant or command palette are never sent to Sandytalks.

---

### 2. Audio Engine & DSP Architecture: OliX Audio Technology™

* **100% Local On-Device Processing:** The entire internal audio architecture—including the **OliX Signature Sound** 3D spatializer, 10-band graphic equalizer, 10 hardware speaker profiles, 48-band spectrum visualizer, SoX HiFi resampler,  **100% locally on your PC's CPU/GPU**.
* **Zero Audio Telemetry:** No audio signals, waveform data, microphone feeds, or equalization measurements are ever transmitted over the network.
* **Dolby Studio :**  
  * Dolby technology is used **exclusively and specifically** for the optional **Dolby Studio** .
  * Only when you explicitly click *"Enhance Current Track"*, the selected audio file is temporarily uploaded over encrypted HTTPS to Dolby.io REST APIs (`api.dolby.com`) for cloud-based dynamic mastering, dialogue enhancement, and noise reduction. Once processed, the mastered audio is returned directly to your PC and the temporary cloud copy is purged according to Dolby.io's retention policies.

---

### 3. Artificial Intelligence & Machine Learning Privacy

* **Offline Faster-Whisper AI Subtitles:**
  * Subtitle transcription via Faster-Whisper runs **100% locally and completely offline** using CTranslate2 and Silero VAD v6.
  * After the initial model weights are downloaded to your machine, no audio data, dialogue transcripts, or SRT files are ever sent to the cloud. Subtitles are generated and cached strictly on your local disk.
* **Google Gemini AI (Sandytalks AI Assistant & Command Palette):**
  * When you deliberately open the Sandytalks AI sidebar or use natural language queries in the Command Palette (<kbd>Ctrl</kbd> + <kbd>K</kbd>), your text prompt and basic track title metadata are transmitted directly to Google's Generative AI API (`generativelanguage.googleapis.com`) over TLS/HTTPS.
  * If you supply your own Google Gemini API key, communications occur directly between your PC and Google under [Google's Privacy Policy](https://policies.google.com/privacy) and Google AI Terms of Service.

---

### 4. Local Data Storage & User Control

To provide a seamless, persistent media experience, SANDYPLAY stores configuration files, playlists, and caches locally on your hard drive (under `%USERPROFILE%\.sandyplay\` or `%APPDATA%\SandyPlay\` on Windows):

| Stored Item | Purpose &amp; Contents | Location |
| :--- | :--- | :--- |
| **`sandyplay_config.json`** | Theme accents, speaker mode, volume, equalizer presets, window bounds, and user-provided API keys (stored locally in plain text). | Local Storage |
| **`playback_history.json`** | Recently opened media files, resume playback positions, and play timestamps. | Local Storage |
| **`favorites.json`** | Your favorited music tracks, online radio stations, anime series, and TV channels. | Local Storage |
| **`tv_cache.json` &amp; `iptv_playlist.m3u`** | Cached TV station listings and channel mirrors (persisted for 7 days to preserve your network bandwidth). | Local Storage |
| **`lyrics_cache/`** | Downloaded `.lrc` synchronized lyrics files for offline viewing. | Local Storage |
| **`artwork_cache/`** | Cached album art, artist portraits, and video thumbnail images. | Local Storage |
| **`faster_whisper/`** | Local Faster-Whisper machine learning model weights (e.g. `base.en`, `tiny.en`). | Local Storage |
| **`web_browser_profile/`** | Chromium session storage, cookies, and HTTP cache when using the integrated Sandy Web Browser. | Local Storage |
| **`downloads_state.json`** | Download queue state, progress checkpoints, and completed tasks. | Local Storage |

> [!TIP]
> **Complete User Data Ownership:**  
> You can wipe all history, cookies, cached artwork, or configuration files at any time by deleting the `.sandyplay` directory or clicking **Clear History / Reset Cache** in the application settings or the web browser.

---

### 5. Third-Party Network Services & Streaming APIs

SANDYPLAY connects directly to public internet services and streaming APIs to discover and playback media. When using these features, your device communicates directly with the respective third-party servers. Your IP address and search terms are subject to their respective privacy terms:

1. **Streaming Media Platforms:**
   * Video and audio stream discovery is powered by `yt-dlp` and direct stream decoders. Requests originate directly from your IP address to media host servers.
2. **Online Radio &amp; Metadata:**
   * Streams are fetched directly from station broadcast servers. Track metadata is retrieved via stream titles.
3. **Podcasts:**
   * Podcast queries interact with Search API and individual podcast RSS feed servers.
4. **Lyrics &amp; Metadata APIs:**
   * Automated lyrics matching queries public APIs . Only the song title and artist name are sent.
5. **Software Update Checks (GitHub API):**
   * SANDYPLAY periodically queries the public GitHub Releases API (`api.github.com/repos/sandytalks/SANDYPLAY/releases/latest`) to inform you when a new version of SANDYPLAY is available. No user identifiers are attached to this request.

---

### 6. Network Utilities &amp; Hardware Features

* **RTL-SDR Hardware FM Radio Tuner:**
  * When using a connected RTL2832U USB dongle, raw RF signals are demodulated locally via `rtl_fm`. This feature operates **100% offline** without any internet connection.
* **GoodbyeDPI &amp; WinDivert Packet Filter:**
  * The optional network booster uses the open-source WinDivert kernel driver locally to modify TCP/IP packet fragmentation and bypass deep packet inspection (DPI) and SNI throttling imposed by local ISPs. **It does not route your traffic through any remote VPN server or third-party proxy.**
* **Local Proxy Server (`127.0.0.1:8125`):**
  * The Parallel Stream Proxy binds exclusively to `127.0.0.1` (localhost). It is completely inaccessible from external networks and does not log or transmit your viewing history.
* **SSL Certificate (`SecurityAppliance_SSL_CA.pem`):**
  * If placed in the application folder, this root certificate is loaded strictly into local Python and VLC SSL contexts to resolve HTTPS blocking on strict educational or enterprise networks.

---

### 7. Security Best Practices for Users

Because SANDYPLAY does not transmit your data to remote developer servers, your security and privacy depend on securing your local machine:
* If you enter personal API keys or log into streaming platforms via the built-in browser, these credentials reside locally in your user profile.
* We recommend keeping your operating system updated, using disk encryption (e.g. Windows BitLocker), and restricting physical access to your machine.
* To clear all saved sessions in the web browser, click **Logout & Clear Session** in the browser menu.

---

### 8. Changes to This Privacy Policy

We may update this Privacy Policy to reflect future features or architectural updates (such as upcoming multi-device audio relay features). Any revisions will be published directly to this file in the official GitHub repository with an updated effective date.

---

### 9. Contact & Inquiries

If you have questions, feedback, or security concerns regarding this Privacy Policy or SANDYPLAY's data handling, please contact us:
* **GitHub Issues:** [https://github.com/sandytalks/SANDYPLAY/issues](https://github.com/sandytalks/SANDYPLAY/issues)
* **GitHub Discussions:** [https://github.com/sandytalks/SANDYPLAY/discussions](https://github.com/sandytalks/SANDYPLAY/discussions)
* **Official Developer Portal:** [@sandyplay on Instagram](https://www.instagram.com/sandyplay/)
