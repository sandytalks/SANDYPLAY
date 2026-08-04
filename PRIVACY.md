
# Privacy Policy for SandyPlay

**Effective Date:** August 2026 (or current date)
**Application:** SandyPlay Media Player

This Privacy Policy describes how SandyPlay ("the Application") handles your data. SandyPlay is an open-source desktop media player developed by Sandytalks.

### 1. Data We Collect (No Developer Telemetry)
**The developer of SandyPlay does NOT collect, store, or transmit any personal data, usage analytics, or telemetry to any developer-owned servers.** SandyPlay operates locally on your machine. 

### 2. Local Data Storage
To provide a personalized experience, SandyPlay saves certain data **locally on your hard drive** (typically in `%APPDATA%\SandyPlay` or `~/.sandyplay`). This local data includes:
*   Application settings and theme preferences.
*   Media playback history, favorites, and playlists.
*   Cached metadata, artwork, and lyrics.
*   Persistent browser cookies (if you log into the web player/Google AI).
*   Your personal API Keys (e.g., Google Gemini, Dolby.io) which are saved locally in plain text inside your configuration file.

You have full control over this data and can delete it at any time by clearing the application's configuration folder.

### 3. Third-Party Services & APIs
Because SandyPlay is a streaming media player and AI-assisted tool, it connects directly to third-party services over the internet. By using the Application, your device will communicate directly with these services, and you are subject to their respective privacy policies:

*   **Streaming Platforms (YouTube, JioSaavn, SoundCloud, Anime/IPTV sites):** When you search or stream media, your search queries and IP address are sent to these platforms. Video/Audio extraction is handled via `yt-dlp`.
*   **Google Gemini AI:** If you use the Sandytalks AI features, your chat prompts, currently playing song metadata, and Google login cookies are sent directly to Google's servers.
*   **Dolby.io:** If you use the Dolby Cloud Enhance feature, the audio file you select is temporarily uploaded to Dolby.io servers for processing.
*   **Lyrics & Metadata APIs:** When auto-fetching lyrics, the song title and artist name are sent to various public APIs (e.g., LRCLIB, Netease, Musixmatch, iTunes).
*   **GitHub API:** The Application periodically pings the official GitHub repository to check for software updates.

### 4. Security
While the Application does not transmit data to the developer, it stores your configurations (including API keys and cookies) locally. It is your responsibility to secure your local machine to prevent unauthorized access to these files.

### 5. Changes to This Policy
This Privacy Policy may be updated periodically to reflect changes in the software's features. Updates will be reflected in the application's GitHub repository.

### 6. Contact
If you have any questions regarding this privacy policy, please open an issue on the official GitHub repository:https://github.com/sandytalks/SANDYPLAY
