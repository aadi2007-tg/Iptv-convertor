 📺 IPTV Portal + Stalker + Xtream to M3U Converter

This is a Python script that converts **Portal**, **Stalker Portal**, and **Xtream Codes IPTV** data into **M3U playlist files** for use with IPTV players like Kodi, VLC, IPTV Smarters, and more.

---

## ✅ Features

- 🎯 **Three Modes Supported**:
  - **Portal to M3U** — Basic portal loader using MAC address.
  - **Stalker Portal to M3U** — with serial/device ID.
  - **Xtream Codes to M3U** — Fetch live streams and categories from Xtream-compatible panels.

- 🗂️ **Genre Filtering** — Select specific genres to include in your M3U file.

- 🖼️ **Logo Support** — Automatically adds TV logos and EPG IDs.

- 🧠 **Smart Stream Handling**:
  - Detects and replaces `ffmpeg` or `localhost/ch/` URLs with your custom domain (optional).

- 🧪 **Auto-generates**:
  - Serial number
  - Device IDs
  - Folders and filenames

- 💾 Saves M3U files to:  
  `/sdcard/Stalker_Portal_to_M3U/` (Android)  

---

## 📦 Requirements

- Python 3.x
- Internet connection
- The `requests` library:
  ```bash
  pip install requests
  
