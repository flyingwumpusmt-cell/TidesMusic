TidesMusic 🌊

TidesMusic is a modern, Spotify-like music player for Windows that supports YouTube search, playlists, radio streaming, podcasts, and more. Designed for smooth, animated UI and multiple themes.

Features
YouTube search and playlist support
Radio station streaming (Dutch stations included)
Podcast playback
Fully animated playback controls
Multiple themes: Dexter 🩸, Forest 🌲, Helldivers 2 🔫
Pulse effect on playlist items
Volume control slider
Album art display for tracks
Modern, responsive GUI
No ads
No Ads

TidesMusic is completely ad-free. Enjoy music without interruptions or popups.

Installing Dependencies

Before running Tides, make sure all required Python packages are installed.

Step 1: Check your Python path

Locate your Python executable. Common paths:

Default Python 3.11:
C:\Program Files\Python311\python.exe
Custom Python 3.14 install:
C:\Users\<YourUser>\AppData\Local\Python\pythoncore-3.14-64\python.exe
Step 2: Install all dependencies

Open PowerShell and run the following (replace the path if different):

& "C:\Program Files\Python311\python.exe" -m pip install --upgrade pip PyQt6 python-vlc yt-dlp requests feedparser Pillow

This will install:

PyQt6 → GUI
python-vlc → audio playback
yt-dlp → YouTube search and playlist support
requests → web requests
feedparser → podcast RSS feeds
Pillow → image handling
Step 3: Run TidesMusic

Navigate to the folder containing Tides.py and run:

& "C:\Path\To\Python.exe" Tides.py

TidesMusic should now launch with full functionality.

https://github.com/flyingwumpusmt-cell/TidesMusic/releases/latest

Download the latest release from the Releases
.

Contributing

Contributions are welcome! Please submit a pull request or open an issue to suggest improvements or report bugs.

License

This project is open-source under the MIT License.
