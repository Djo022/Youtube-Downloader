# YouTube Downloader 🚀

A modern, high-performance YouTube downloader with a clean Dark Mode GUI. Built for both Windows (Desktop) and Android (Mobile).

## 🌟 Features
- **Dual Mode**: Download high-quality Video (MP4) or Audio-only (MP3).
- **Resolution Control**: Supports 360p, 720p, 1080p, and 4K.
- **Smart Fetch**: Automatically displays the video title as soon as you paste the link.
- **Progress Tracking**: Real-time progress bar with download speed (MiB/s).
- **Clean UI**: Built with CustomTkinter for a professional Windows look.

## 💻 Windows Installation (Recommended)
1. Go to the **Releases** tab on the right side of this page.
2. Download `GeminiDownloader.exe`.
3. **CRITICAL**: You must have **FFmpeg** installed for the app to merge video and audio correctly.
   - Run `winget install FFmpeg` in your Command Prompt to install it easily.

## 📱 Android Usage (we are still working on it, We are Sorry for wait!)
To run the mobile version:
1. Install **Pydroid 3** from the Google Play Store.
2. Open `main.py` from this repository and copy the code.
3. In Pydroid 3, go to the Terminal and type: `pip install yt-dlp flet`.
4. Paste the code into the editor and hit **Run**.

## 🛠️ Tech Stack
- **Language**: Python 3.x
- **Core Engine**: [yt-dlp](https://github.com/yt-dlp/yt-dlp)
- **Windows GUI**: CustomTkinter
- **Mobile GUI**: Flet
- **Processing**: FFmpeg
