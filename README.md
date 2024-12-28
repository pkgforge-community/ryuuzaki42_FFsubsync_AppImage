
# FFsubsync_AppImage

## Repository: https://github.com/ryuuzaki42/FFsubsync_AppImage
    FFsubsync: 0.4.27

## Usage
```
# Base:
    ./FFsubsync*_JB.AppImage ffs

    ./FFsubsync*_JB.AppImage subsync

    ./FFsubsync*_JB.AppImage ffsubsync

# Examples:
    # Sync from video file
        ./FFsubsync*_JB.AppImage ffs video.mp4 -i unsynchronized.srt -o synchronized.srt

        ./FFsubsync*_JB.AppImage ffs video.mkv -i unsynchronized.srt -o synchronized.srt

    # Sync from subtitle reference file
        ./FFsubsync*_JB.AppImage ffsubsync reference.srt -i unsynchronized.srt -o synchronized.srt

# For help:
    ./FFsubsync*_JB.AppImage ffs -h

    ./FFsubsync*_JB.AppImage subsync -h

    ./FFsubsync*_JB.AppImage ffsubsync -h
```

---
https://github.com/smacke/ffsubsync

https://pypi.org/project/ffsubsync/

---
https://github.com/smacke/ffsubsync/tags
