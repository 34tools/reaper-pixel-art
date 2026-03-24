# 🎨 Reaper Pixel Art Generator

**Turn any photo into pixel art directly on the Reaper DAW timeline.**

Each pixel becomes a colored media item on a track. The result looks like this:

![example](example.png)

## How it works

1. Open the web page
2. Upload a photo, choose canvas size and color palette
3. Click **Generate** — a `.lua` script downloads to your computer
4. In Reaper: **Actions → Load ReaScript** → select the file → **Run**
5. Watch your image appear on the timeline ✨

## 🌐 Try it

**[reaper-pixel-art.github.io/reaper-pixel-art](https://34tools.github.io/reaper-pixel-art/)** ← replace with your link

No installation required. Everything runs in the browser — your photo never leaves your device.

## Settings

| Option | Description |
|--------|-------------|
| **32×32** | Fast, minimal detail |
| **64×64** | Recommended — good balance |
| **96×96 / 128×128** | High detail, more tracks |
| **Full RGB** | Maximum color accuracy |
| **NES** | 54 colors, classic 8-bit look |
| **CGA** | 16 colors, DOS-era style |
| **Game Boy** | 4 colors, maximum retro |

## Requirements

- [Reaper](https://www.reaper.fm/) DAW (any recent version)
- A modern browser to run the generator page
- The [SWS Extension](https://www.sws-extension.org/) for Reaper (needed for auto-zoom feature)

## Local use

You can also just download `index.html` and open it locally — no server needed.
