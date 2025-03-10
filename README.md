# 🎬 Subtitle Downloader  

A lightweight and efficient command-line tool to automatically fetch subtitles for movies and TV shows using OpenSubtitles and other providers.  

## 📌 Features  

- 🔍 **Automatic Subtitle Search** – Finds and downloads the best-matching subtitles for your videos.  
- 🌍 **Multi-Language Support** – Download subtitles in different languages.  
- 📂 **Batch Processing** – Fetch subtitles for an entire directory at once.  
- 📺 **Supports Multiple Formats** – Works with `.mp4`, `.mkv`, `.avi`, and more.  
- ⚡ **Fast & Lightweight** – Optimized for quick downloads with minimal resource usage.  
- 🛠 **Cross-Platform** – Works on Windows, macOS, and Linux.  

## 🚀 Installation  

### Prerequisites  
- **Python 3.x** installed  
- **pip** package manager  

### Steps  

1. **Clone the repository**  
   ```bash
   git clone https://github.com/uttercaviler/Subtitle-Downloader.git
   cd Subtitle-Downloader
2.**Install dependencies**
bash
Copy
Edit
pip install -r requirements.txt
🎬 Usage
To download subtitles for a single file:

bash
Copy
Edit
python subtitle_downloader.py /path/to/video.mp4
To download subtitles for all videos in a directory:

bash
Copy
Edit
python subtitle_downloader.py /path/to/directory
To specify a language (e.g., English):

bash
Copy
Edit
python subtitle_downloader.py /path/to/video.mp4 --lang en
⚙️ Configuration
Default language – Modify the script to set a preferred language for subtitles.
API configuration – OpenSubtitles may require an API key. Set up an account if necessary.
❓ Troubleshooting
Ensure that your video files are named correctly for better subtitle matching.
Check your internet connection if downloads fail.
Run the script with --help to see available options:
bash
Copy
Edit
python subtitle_downloader.py --help
🤝 Contributing
Contributions are welcome! If you'd like to improve this project:

Fork the repository.
Create a new branch (git checkout -b feature-branch).
Commit changes (git commit -m "Added new feature").
Push to the branch (git push origin feature-branch).
Create a pull request on GitHub.
