
just download the file and run it


## 📂 Project Structure

```
Music and Youtube Video Downloader/
│
├── downloader.py               # Main Python application
├── run.bat                     # Quick launcher to double-click on Windows
├── frieren.txt                 # High-detail Braille Frieren mascot art
│
├── bin/                        # Local database & config
│   ├── mascot.txt              # Braille Frieren companion fetched during downloads
│   ├── beets_config.yaml
│   └── beets.db
│
├── Downloads/
│   ├── Videos/                 # Downloaded video files (.mp4 / .mkv)
│   └── Music/
│       ├── <Playlist Name>/    # Dedicated folder per playlist
│       │   ├── archive.txt     # Resume tracker
│       │   ├── Song 1.opus     # Contains embedded cover art, tags & lyrics
│       │   ├── Song 2.opus
│       │   └── ...
│       │
│       └── Single Tracks/      # Non-playlist individual songs
│           ├── archive.txt
│           └── SingleSong.opus
└── README.md
```

---

## 🙏 Credits & Third-Party Acknowledgments

This project is built upon and inspired by exceptional open-source software and public music APIs:

| Project / Library | Repository / Official URL | Purpose in Easyytdl |
| :--- | :--- | :--- |
| **yt-dlp** | [github.com/yt-dlp/yt-dlp](https://github.com/yt-dlp/yt-dlp) | High-performance media downloader core and stream format extractor. |
| **FFmpeg Builds** | [github.com/yt-dlp/FFmpeg-Builds](https://github.com/yt-dlp/FFmpeg-Builds) & [ffmpeg.org](https://ffmpeg.org/) | Video/audio stream muxing, post-processing, and conversion engine. |
| **Beets** | [github.com/beetbox/beets](https://github.com/beetbox/beets) | Powerful music tagging framework and autotagger for MusicBrainz release matching. |
| **album-art** | [github.com/lacymorrow/album-art](https://github.com/lacymorrow/album-art) | Official studio album cover art search engine powered by the Spotify Web API. |
| **Mutagen** | [github.com/quodlibet/mutagen](https://github.com/quodlibet/mutagen) | Audio tag manipulation for embedding ID3 tags, FLAC Picture blocks in Opus, and lyrics tags. |
| **MusicBrainz & CAA** | [musicbrainz.org](https://musicbrainz.org/) & [coverartarchive.org](https://coverartarchive.org/) | Open music encyclopedia and Cover Art Archive for official discography metadata. |
| **LRCLIB** | [github.com/tranxuanthang/lrcget](https://github.com/tranxuanthang/lrcget) & [lrclib.net](https://lrclib.net/) | Community-driven public database for synchronized and plain song lyrics. |
| **Lyrics.ovh** | [lyricsovh.docs.apiary.io](https://lyricsovh.docs.apiary.io/) | Online lyrics search API fallback. |
| **Requests** | [github.com/psf/requests](https://github.com/psf/requests) | HTTP client library for Python used to query music and lyrics APIs reliably. |
| **Beautiful Soup 4** | [crummy.com/software/BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/) | HTML/XML parsing library used for web scraping fallback queries. |

---
