# KeyLogger

## Overview
This **KeyLogger** captures keystrokes, tracks mouse activity, takes screenshots, and records system information. It sends periodic reports via email and can also record microphone audio. Designed for monitoring purposes, it operates stealthily and removes traces after execution.

## Features
- **Keystroke Logging**: Records all typed keystrokes.
- **Mouse Activity Tracking**: Logs mouse movements, clicks, and scrolls.
- **Screenshot Capture**: Periodically takes screenshots of the screen.
- **Microphone Recording**: Captures ambient sound for a set duration.
- **System Information Retrieval**: Collects device details such as IP, OS, and processor info.
- **Automated Email Reports**: Sends logs to a specified email address.
- **Self-Destruct Mechanism**: Deletes itself after execution.

## Technologies Used
- **Python** (Core logic)
- **Pynput** (Keyboard & mouse tracking)
- **Pyscreenshot** (Screenshot capture)
- **Sounddevice & Wave** (Audio recording)
- **SMTP** (Email report delivery)
- **Platform & Socket** (System info retrieval)

## Setup Instructions
1. **Install Dependencies**:
   ```bash
   pip install pynput pyscreenshot sounddevice maskpass
   ```
   
2. Run the KeyLogger:
```bash
python Keylogger.py
```

3. Enter your email credentials when prompted.

## Disclaimer
This software is for **educational** and **ethical** use only. Unauthorized monitoring or misuse of this tool may violate laws. The developer is not responsible for any misuse.
