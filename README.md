# Video Engines

This repository contains precompiled binary engines such as `yt-dlp` and `ffmpeg` used by various applications developed by Pondok Algoritma.

These binaries are hosted here to enable automatic downloading by applications like:

- Vidura, Universal video downloader
- Narrify, is an AI-powered tool that turns text or dialogue into fully narrated videos. It combines realistic text-to-speech (TTS) voiceovers with automated video generation — perfect for education, storytelling, tutorials, and more.
- Other internal or public video-related tools

---

## Downloads

Download the latest versions from the [Releases](https://github.com/pondokalgoritma/video-engine/releases) tab.

| Engine  | Platform | Filename        | Direct Download |
|---------|----------|------------------|-----------------|
| yt-dlp  | Windows  | `yt-dlp.exe`     | [Download](https://github.com/pondokalgoritma/video-engines/releases/latest/download/yt-dlp.exe)   |
| ffmpeg  | Windows  | `ffmpeg.exe`     | [Download](https://github.com/pondokalgoritma/video-engines/releases/latest/download/ffmpeg.exe)   |
| yt-dlp  | Mac OS   | `yt-dlp_macos`   | [Download](https://github.com/pondokalgoritma/video-engines/releases/latest/download/yt-dlp_macos) |
| ffmpeg  | Mac OS   | `ffmpeg_macos`   | [Download](https://github.com/pondokalgoritma/video-engines/releases/latest/download/ffmpeg_macos) |
| yt-dlp  | Linux    | `yt-dlp_macos`   | [Download](https://github.com/pondokalgoritma/video-engines/releases/latest/download/yt-dlp_linux) |
| ffmpeg  | Linux    | `ffmpeg_macos`   | [Download](https://github.com/pondokalgoritma/video-engines/releases/latest/download/ffmpeg_linux) |


---

## Usage in Applications

Applications developed by **Pondok Algoritma** automatically check and download these engines during runtime if they are not present locally.

You do **not** need to manually configure these files as long as the application handles engine setup.

---

## Source Licenses

This repository **does not modify** any engine binary. All files remain under their original open-source licenses:

- **yt-dlp**
  - License: [Unlicense](https://github.com/yt-dlp/yt-dlp/blob/master/LICENSE)
  - Homepage: https://github.com/yt-dlp/yt-dlp

- **ffmpeg**
  - License: [LGPL v2.1](https://ffmpeg.org/legal.html)
  - Homepage: https://ffmpeg.org

---

## Maintained by

**Pondok Algoritma**  
GitHub: [@pondokalgoritma](https://github.com/pondokalgoritma)

---
