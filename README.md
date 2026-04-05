🌊 TidesMusic

TidesMusic is a modern, Spotify-like music player for Windows with YouTube & playlist support, radio streaming, podcasts, and smooth animated UI. Fully ad-free and themeable!

🎵 Features
🔎 YouTube Search & Playlist Support
📻 Radio Streaming (Dutch stations included)
🎙 Podcast Playback
✨ Animated Playback Controls
🎨 Themes: Dexter 🩸 | Forest 🌲 | Helldivers 2 🔫
💓 Pulse Effect on playlist items
🔊 Volume Control Slider
🖼 Album Art Display
🖥 Modern, Responsive GUI
🚫 No Ads
🚫 No Ads

TidesMusic is completely ad-free — enjoy uninterrupted music!

🛠 Installing Dependencies

Before running TidesMusic, install all required Python packages.

Step 1️⃣: Check your Python Path

Locate your Python executable. Common paths:

Default Python 3.11:
C:\Program Files\Python311\python.exe
Custom Python 3.14 install:
C:\Users\<YourUser>\AppData\Local\Python\pythoncore-3.14-64\python.exe
Step 2️⃣: Install All Dependencies

Open PowerShell and run the following command (replace the path if different):

& "C:\Program Files\Python311\python.exe" -m pip install --upgrade pip PyQt6 python-vlc yt-dlp requests feedparser Pillow

✅ This installs:

🖥 PyQt6 → GUI
🎵 python-vlc → Audio playback
🔎 yt-dlp → YouTube & playlist support
🌐 requests → Web requests
🎙 feedparser → Podcast RSS feeds
🖼 Pillow → Image handling
Step 3️⃣: Run TidesMusic

Navigate to the folder containing Tides.py and run:

& "C:\Path\To\Python.exe" Tides.py

TidesMusic should now launch with full functionality! 🎶

📦 Releases

Download the latest release from the Releases
 page.

🤝 Contributing

Contributions are welcome! Please submit a pull request or open an issue to suggest improvements or report bugs.

📜 License

This project is open-source under the MIT License.
