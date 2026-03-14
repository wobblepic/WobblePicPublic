# WobblePic

An interactive image viewer where you can grab and wobble images like jelly.

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

- **Left-click + drag** on an image to wobble it.
- **Right-click + drag** for box selection segmentation.
- **Mouse wheel** to zoom in/out.
- Use the file browser panel on the left to navigate folders and open images.

## License

All rights reserved.
