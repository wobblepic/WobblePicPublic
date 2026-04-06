# WobblePic

[![Website](https://img.shields.io/badge/Website-wobblepic.com-6c5ce7?style=for-the-badge)](https://www.wobblepic.com)

An interactive image viewer where you can grab and wobble images like jelly.

![WobblePic Screenshot](screenshot.png)

## Features

- **Wobble Effect** — Click and drag on an image to stretch it like skin. Release to watch it spring back with inertia.
- **Smart Segmentation** — Click on an object to auto-detect its boundary using SAM2 (Segment Anything Model 2), then wobble just that object. Smooth mask boundaries via bilinear logits interpolation.
- **Pin Deformation** — Right-click or press P during wobble drag to pin the deformation in place. Pin up to 4 points, then wobble other areas while pins hold their shape.
- **Settings Panel** — Adjust Selection Range, Elasticity, and Bounce in real time via a translucent overlay panel.
- **File Explorer** — Built-in directory tree and file list for navigating folders and images. Right-click context menus, rename, and clipboard support.
- **GPU Accelerated** — OpenGL shader-based mesh deformation rendering at 60fps.
- **Wide GPU Support** — ONNX Runtime + DirectML backend supports AMD, NVIDIA, and Intel GPUs.
- **Wide Format Support** — JPG, PNG, BMP, GIF, WebP, TIFF, AVIF, HEIC/HEIF.
- **Ad-Free License** — Optional $3 one-time purchase to remove ads and unlock premium features (directory tree, panel customization).

## Download

Download the latest installer from the [Releases](https://github.com/wobblepic/WobblePicPublic/releases) page.

## System Requirements

- Windows 10 or later (64-bit)
- DirectX 12 compatible GPU (for SAM2 segmentation)
- OpenGL 3.3+ support

## Installation

1. Download `WobblePic_Setup_x.x.x.exe` from [Releases](https://github.com/wobblepic/WobblePicPublic/releases).
2. Run the installer and follow the instructions.
3. Launch WobblePic from the Start Menu or Desktop shortcut.

## Usage

```
WobblePic.exe [image_path_or_folder]
```

- **Click + drag** on an object to wobble it.
- **Right-click** or **P** during drag to pin the deformation.
- **Click** on a red pin dot to release it.
- **Click** outside the wobble area to select a different object.
- **Ctrl + drag** to move the selected segment.
- **Mouse wheel** to zoom, **middle-click + drag** to pan.
- **Arrow keys** or **Space/Backspace** to navigate images.
- **I** to toggle image info overlay, **Tab** to switch panel focus, **F1** for tutorial.

## License

WobblePic is freeware. Free to use, not for redistribution or modification.
