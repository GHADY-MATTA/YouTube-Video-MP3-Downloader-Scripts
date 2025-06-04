# 🎥 YouTube Video & MP3 Downloader Scripts (Python + yt\_dlp)

This repo contains two simple but powerful Python scripts for downloading YouTube content using `yt_dlp`. One downloads the **entire video**, and the other extracts **high-quality MP3 audio** directly into your Downloads folder.

---

## 📺 `download_video.py`

Download the best available **video + audio** stream and save it to your system's temp folder.

### ✅ Features:

* Downloads video in best format
* Auto-names output file
* Outputs full path
* Uses system temp folder for cleanup

### 🚀 Usage:

```bash
python download_video.py
```

### ✏️ Modify the Script:

Edit the last line to change the video:

```python
video_url = "https://www.youtube.com/watch?v=yqFfmwVufMo"
download_video(video_url)
```

### 📂 Output Example:

```
YourNameTemp\downloaded_video.mp4
```

---

## 🎵 `MP3-to-Downloads.py`

Extract **MP3 audio** from a YouTube video and save it directly to your `Downloads` folder.

### ✅ Features:

* Best audio quality (192kbps MP3)
* Clean filename from video title
* Saves to: `C:\Users\<YourUsername>\Downloads`

### 🚀 Usage:

```bash
python MP3-to-Downloads.py
```

### ✏️ Customize:

Set your own video URL in the script:

```python
url = "https://www.youtube.com/watch?v=yqFfmwVufMo"
download_youtube_mp3(url)
```

### 📂 Output Example:

```
yourName\Downloads\MyVideoTitle.mp3
```

---

## 🛠️ Requirements

Install `yt_dlp` and `ffmpeg` (required for MP3 conversion):

```bash
pip install yt-dlp
```

Make sure `ffmpeg` is installed and available in your system PATH:
[https://ffmpeg.org/download.html](https://ffmpeg.org/download.html)

Test it:

```bash
ffmpeg -version
```

---

## 💼 License

MIT License — use, modify, and share freely.

---


