# WobblePic

[![Website](https://img.shields.io/badge/Website-wobblepic.com-6c5ce7?style=for-the-badge)](https://www.wobblepic.com)

An interactive image viewer where you can grab and wobble images like jelly.

![WobblePic Screenshot](screenshot.png)

## Features

- **Wobble Effect** — Click and drag on an image to stretch it like skin. Release to watch it spring back with inertia.
- **Smart Segmentation** — Click on an object to auto-detect its boundary using SAM2 (Segment Anything Model 2), then wobble just that object.
- **File Browser** — Built-in file explorer panel to browse and open images.
- **GPU Accelerated** — OpenGL shader-based mesh deformation rendering.
- **Wide GPU Support** — ONNX Runtime + DirectML backend supports AMD, NVIDIA, and Intel GPUs.

## Download

Download the latest installer from the [Releases](https://github.com/igkang00/WobblePicPublic/releases) page.

## System Requirements

- Windows 10 or later (64-bit)
- DirectX 12 compatible GPU (for SAM2 segmentation)
- OpenGL 3.3+ support

## Installation

1. Download `WobblePic_Setup_x.x.x.exe` from [Releases](https://github.com/igkang00/WobblePicPublic/releases).
2. Run the installer and follow the instructions.
3. Launch WobblePic from the Start Menu or Desktop shortcut.

## Usage

```
WobblePic.exe [image_path_or_folder]
```

- **Click + drag** on an object to wobble it.
- **Click** outside the wobble area to select a different object.
- **Mouse wheel** to zoom, **middle-click + drag** to pan.
- **Arrow keys** or **Space/Backspace** to navigate images.

## License

WobblePic is freeware. Free to use, not for redistribution or modification.
