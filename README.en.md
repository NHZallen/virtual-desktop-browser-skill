# Virtual Desktop Browser (English)

A skill for OpenClaw/agents that runs **Chromium in non-headless mode** on **Xvfb virtual display (fixed 1200x720x24)** and performs **human-like automation** with PyAutoGUI.

## Features
- Start/stop Xvfb + Chromium
- Mouse click, keyboard typing, hotkeys
- Scroll, screenshot, pixel color
- Image template matching (OpenCV)
- Window activation

## System dependencies
```bash
sudo apt-get update
sudo apt-get install -y xvfb chromium-browser \
  libnss3 libgconf-2-4 libxss1 libasound2 \
  libatk1.0-0 libatk-bridge2.0-0 libcups2 \
  libdrm2 libgbm1 libgtk-3-0 libxshmfence1 x11-utils
```

## Python dependencies
```bash
pip install -r requirements.txt
```

## Files
- `SKILL.md`: skill description + tool interface
- `skill.py`: implementation

## Author
Creator: **Allen Niu**
