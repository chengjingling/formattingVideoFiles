# Formatting Video Files

## About

This application examines 5 video files using `ffprobe` and generates a report of the fields that do not comply with the specified format. The video files are then converted into the specified format using `ffmpeg` as a new copy with "\_formatOK" at the end of the file name.

## Specified format

- Video format (container): mp4
- Video codec: h.264
- Audio codec: aac
- Frame rate: 25 FPS
- Aspect ratio: 16:9
- Resolution: 640 x 360
- Video bit rate: 2 – 5 Mb/s
- Audio bit rate: up to 256 kb/s
- Audio channels: stereo
