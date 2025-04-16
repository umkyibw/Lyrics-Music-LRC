# LRC Database Repository

This repository serves as a database for LRC files, which are lyrics files that can be synchronized with music playback. The repository includes lyrics for a wide range of artists, including both Japanese and international musicians.

## Folder Structure

The repository is organized as follows:

- **Artist**: Each artist has their own folder, e.g., `スピッツ [74456960]`.
- **Album**: Within each artist folder, there are subfolders for each album or single, e.g., `CRISPY! [1443132154][16B-44.1kHz-ALAC]`.
- **Track**: Inside each album folder, there are LRC files for each track, named as `track_number. song_title.lrc`, e.g., `01. クリスピー.lrc`.

Each LRC file contains the lyrics for the corresponding track. The lyrics may be:

- **Synchronized**: With time stamps for each line (e.g., `[00:12.34] Lyrics line`).
- **Syllable-synchronized**: With time stamps for each syllable or word (e.g., `[00:12.34] Ly[00:12.56]rics [00:12.78]line`).
- **Non-synchronized**: Plain lyrics without time stamps.

The type of LRC file (synchronized, syllable-synchronized, or non-synchronized) is not separated by folder; all types are stored together within the track's folder. Users can determine the type by inspecting the content of the LRC file.

Additionally, some folders may contain cover images, such as `cover.jpg` for albums or `folder.jpg` for artists.

## Usage

To use this repository, you can clone it to your local machine:

```
git clone https://github.com/your-repo-url.git
```

Then, navigate to the desired artist and album to find the LRC files for the tracks. Ensure that your music player or application supports LRC files and can load them from the file system.


## 📚 References

- [LRC Format Spec (Wikipedia)](https://en.wikipedia.org/wiki/LRC_(file_format))
- [ID3 and ALAC metadata documentation](https://mutagen.readthedocs.io/en/latest/)
- [Japanese Lyrics Databases and Archives](https://www.lyrical-nonsense.com/)

## Disclaimer

This repository is for educational and personal use only. The lyrics are copyrighted by their respective owners. Please respect the artists' rights and do not use the lyrics for commercial purposes without proper authorization.
