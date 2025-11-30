# yt-shorts-maker

Automate creation and upload of vertical YouTube Shorts (FFmpeg + n8n workflows).

## What it does
- Generates 9:16 vertical videos using FFmpeg (drawtext overlays, audio mixing, scaling)
- Integrates with n8n to pick media, render videos, and upload to YouTube
- Safe text sanitization for FFmpeg drawtext (prevents filter-graph breakage)
- Optional: caption/subtitle generation and automatic titling

## Quick start
1. Clone:
```bash
git clone https://github.com/YOUR_USERNAME/yt-shorts-maker.git
cd yt-shorts-maker
