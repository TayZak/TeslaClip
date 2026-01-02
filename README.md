# TeslaClip

**Free Tesla Dashcam & Sentry Mode Viewer with Real-Time Telemetry**

Watch your Tesla dashcam videos like never before! TeslaClip is a web-based viewer for TeslaCam, Sentry Mode, and saved clips. View up to 6 cameras simultaneously with real-time speed, GPS, autopilot status, and interactive HUD overlay. 100% free during beta, works entirely in your browser, and no upload required.

**Live Demo:** [https://teslaclip.com](https://teslaclip.com)

---

## Features

- **Multi-Camera Playback** - View up to 6 Tesla cameras simultaneously (front, back, left/right repeaters, left/right pillars)
- **Real-Time Telemetry Overlay** - HUD display showing speed, GPS, autopilot status, steering angle, pedals, g-force, and more
- **Interactive GPS Map** - Real-time route tracking with satellite and street view
- **Flexible Layouts** - Switch between front-only, front+back, front+sides, all cameras, or custom layouts
- **Variable Playback Speed** - Control playback from 0.1x to 10x speed
- **Local Processing** - All video processing happens in your browser - no uploads, complete privacy
- **Folder Memory** - Automatically remembers your last selected TeslaCam folder (Chrome/Edge)
- **Demo Videos** - Try the app instantly with sample videos without needing your own footage
- **Multi-Language Support** - Available in English, French, German, Spanish, and Italian

---

## Browser Compatibility

**Fully Supported** (with folder persistence):
- Chrome/Chromium 86+
- Microsoft Edge 86+
- Opera 72+
- Other Chromium-based browsers

**Partially Supported** (works but no folder persistence):
- Safari (macOS/iOS)
- Firefox

**Note:** The demo video feature works on all browsers.

---

## Usage

### Option 1: Use Your Own Tesla Videos

1. **Prepare your TeslaCam folder**
   - Connect your Tesla USB drive to your computer
   - Navigate to the `TeslaCam` folder

2. **Open TeslaClip**
   - Visit [https://teslaclip.com](https://teslaclip.com)
   - Click "Open TeslaCam Folder" on the landing page
   - Select your `TeslaCam` folder
   - Browse your clips in grid or map view

3. **Watch a clip**
   - Click on any clip to open the player
   - Use playback controls to play/pause, scrub timeline, and change speed
   - Switch between camera layouts
   - Toggle HUD elements and map visibility

### Option 2: Try the Demo

1. Visit [https://teslaclip.com](https://teslaclip.com)
2. Click "Try Demo Video" on the landing page
3. Sample videos will load instantly
4. Explore all features without needing your own videos

---

## Tesla Folder Structure

TeslaClip supports the standard Tesla folder structure:

```txt
TeslaCam/
├── SentryClips/
│ └── 2025-12-21_20-59-54/
│ ├── 2025-12-21_20-59-54-front.mp4
│ ├── 2025-12-21_20-59-54-back.mp4
│ ├── 2025-12-21_20-59-54-left_repeater.mp4
│ ├── 2025-12-21_20-59-54-right_repeater.mp4
│ ├── 2025-12-21_20-59-54-left_pillar.mp4
│ ├── 2025-12-21_20-59-54-right_pillar.mp4
│ ├── thumb.png (optional)
│ └── event.json (optional)
├── SavedClips/
│ └── [same structure]
└── RecentClips/
└── [same structure or loose files]
```



**Supported Video Naming:** `YYYY-MM-DD_HH-MM-SS-{camera_angle}.mp4`

**Supported Camera Angles:** front, back, left_repeater, right_repeater, left_pillar, right_pillar

---

## How It Works

TeslaClip extracts real-time telemetry data embedded in Tesla MP4 files, including GPS coordinates, vehicle speed, autopilot status, and more. This data is synchronized frame-by-frame with the video for accurate real-time display.

### Privacy First

All video processing happens entirely in your browser using modern web technologies. Your videos never leave your device, and no data is uploaded to external servers. TeslaClip uses local storage and browser APIs to provide a seamless experience while maintaining complete privacy.

### Technologies Used

TeslaClip is built with modern web technologies to deliver a fast and reliable experience:

- **Frontend Framework:** React 19.2.0 with TypeScript 5.9.3 for type-safe, component-based architecture
- **Build System:** Vite 5.4.21 for lightning-fast development and optimized production builds
- **Styling:** TailwindCSS 4.0.0 for responsive and customizable design
- **Routing:** React Router 7.11.0 for seamless navigation
- **Mapping:** Leaflet 1.9.4 + React Leaflet 5.0.0 for interactive GPS visualization
- **Video Processing:** MP4Box 2.3.0 for efficient MP4 parsing and manipulation
- **Telemetry Decoding:** Protobuf.js 8.0.0 to decode Tesla's telemetry format
- **Internationalization:** react-i18next for multi-language support (EN, FR, DE, ES, IT)

---

## Roadmap

We're continuously improving TeslaClip. Upcoming features include:
- Enhanced video export functionality
- Improved mobile experience
- Additional language support
- Performance optimizations

---

## Legal

- **Not affiliated with Tesla, Inc.** - TeslaClip is an independent project and is not endorsed by or affiliated with Tesla, Inc.
- **Privacy First** - All video processing happens locally in your browser. No data is uploaded to external servers.
- **User Control** - Users maintain full control of their video files at all times.

---

## License

Copyright (c) 2026 TeslaClip. All rights reserved.

This software and associated documentation files are proprietary and confidential. No part of this software may be reproduced, distributed, or transmitted in any form or by any means without the prior written permission of the owner.

---

## Support

For questions, bug reports, or feature requests:
- Visit our website: [https://teslaclip.com](https://teslaclip.com)
- Contact us through the app's feedback form

---

**Made with passion for Tesla enthusiasts worldwide.**
