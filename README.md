<h1 align="center">TagPilot</h1>

<p align="center">
  Fix the tags on your music files: find missing metadata, artwork and synced lyrics,<br>
  and write them back safely.
</p>

<p align="center">
  <a href="../../releases/latest"><img alt="Download latest APK" src="https://img.shields.io/badge/Download-latest%20APK-0F9D8F?style=for-the-badge&logo=android&logoColor=white"></a>
</p>

<p align="center">
  <img alt="Latest release" src="https://img.shields.io/github/v/release/Saiprasadsharma/TagPilot-releases?label=latest%20build&color=0F9D8F">
  <img alt="Android 7.0+" src="https://img.shields.io/badge/Android-7.0%2B-3DDC84?logo=android&logoColor=white">
  <img alt="Downloads" src="https://img.shields.io/github/downloads/Saiprasadsharma/TagPilot-releases/total?color=0F9D8F">
</p>

---

TagPilot works on the music already on your phone (MP3, FLAC and M4A). It shows which tracks are missing tags, looks up the correct details online, and writes them into the files so every music player sees them. **Every write backs the file up first**, so a failed write can't corrupt a song.

## Install

1. Open the **[latest release](../../releases/latest)** and download the `.apk` file.
2. Open the file on your phone. If Android asks, allow your browser or file manager to **install unknown apps**.
3. Launch TagPilot and allow access to your music files.

Requires **Android 7.0 or newer**. Internet is only needed for online lookups; editing works offline.

> Every build is signed with the same key, so you can install a newer APK over the old one and keep your settings.

## What it does

| | |
|---|---|
| 📚 **Library** | Tracks and Albums tabs, filters for missing tags, artwork and lyrics, natural-order sorting, search and a mini player. Finds albums whose tracks disagree on Album Artist and fixes them in one go. |
| ✏️ **Tag editor** | Title, artist, album, album artist, genre, year, track and disc numbers, composer, lyrics and comments. One-tap lookup on iTunes with MusicBrainz as a fallback. |
| 🖼️ **Artwork** | Pick from your phone, iTunes or the Cover Art Archive. Covers are resized before embedding, and the size is adjustable in Settings. |
| 🎤 **Lyrics** | Find synced lyrics from [LRCLIB](https://lrclib.net), or sync them yourself: play the song and tap as each line starts. Saved as standard LRC, so players and car stereos show them in time. |
| 🛡️ **Safe writes** | The original file is copied first and restored automatically if anything fails. Android asks permission before any file is changed. |

## Releases

A new APK is built and published here automatically for every change. Each release is named **Build N** and its notes show what changed.

## Credits

Metadata from the [iTunes Search API](https://performance-partners.apple.com/search-api) and [MusicBrainz](https://musicbrainz.org), artwork from the [Cover Art Archive](https://coverartarchive.org), lyrics from [LRCLIB](https://lrclib.net), and tag handling by [jaudiotagger](https://github.com/Adonai/jaudiotagger).
