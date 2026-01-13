# Mudra

**A Gestural Exploration through Computer Vision**

Mudra investigates how traditional Indian hand gestures (mudras) from Bharatanatyam can be interpreted and reimagined through computational systems using real-time computer vision.

## Overview

This project uses MediaPipe and TouchDesigner to capture and analyze hand gestures, bridging classical dance traditions with modern interactive technology. The system integrates with Ableton Live 12 for audio-visual performance.

## Prerequisites

- TouchDesigner (latest version recommended)
- Ableton Live 12
- A working webcam or camera input

## Getting Started

### 1. Download Dependencies

Download the MediaPipe TouchDesigner project from:
```
https://github.com/torinmb/mediapipe-touchdesigner
```

### 2. Setup

1. Open TouchDesigner and create a new project
2. Import the MediaPipe TouchDesigner project file
3. Locate the `toxes` folder from the downloaded GitHub repository
4. Add the following components to your network:
   - **Hand Tracking TOX** - Create 3 copies of this component
   - **Face Detector TOX** - Add 1 instance at the end of your chain

### 3. Configuration

Connect the components as shown in the network diagram below:

<img width="2440" height="908" alt="Mudra_Network" src="https://github.com/user-attachments/assets/bfe3ff7b-1615-450d-8a58-5393626ee3e2" />

In the MediaPipe node settings:
- Select your preferred camera input from the available devices

### 4. Ableton Live Integration

Launch Ableton Live 12 and configure the connection with TouchDesigner to enable gesture-controlled audio manipulation.

## Usage

Once configured, the system will track hand gestures in real-time, allowing you to explore the computational interpretation of mudras with synchronized output.

## Dependencies

- [MediaPipe TouchDesigner](https://github.com/torinmb/mediapipe-touchdesigner) by torinmb
- Ableton Live 12

## Credits

- **Torin** - MediaPipe TouchDesigner integration and tools

## License

MIT License

Copyright (c) 2026 [Your Name]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

## Acknowledgments

This project explores the intersection of traditional Bharatanatyam dance and contemporary computer vision technology.

---

For questions or contributions, please open an issue or pull request.
