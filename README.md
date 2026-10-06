# 🎬 Reshi LUT Studio

Free online LUT studio — apply cinematic LUTs (.cube) to any video in your browser and export in original quality (up to 4K).

**Live:** https://reshikhan.github.io/Reshi-Lut/

## Features
- 🎞 8 built-in film LUTs (Teal & Orange, Warm Vintage, Cool Cinematic, Golden Hour, Cyberpunk, Vibrant Pop, Faded Film, Noir B&W) with true previews
- ＋ Upload your own `.cube` LUTs (3D LUTs)
- ⚡ Real-time WebGL preview with intensity slider + compare toggle
- ⬇ Export at native resolution (up to 4K), high-bitrate MP4/WebM, original audio kept
- 🔒 100% client-side — videos never leave the device

## How it works
Video frames are graded per-pixel in a WebGL fragment shader using trilinear 3D-LUT sampling, then re-encoded via `canvas.captureStream()` + `MediaRecorder` at high bitrate.

## Enable GitHub Pages
Settings → Pages → Deploy from a branch → `main` → `/(root)` → Save.
