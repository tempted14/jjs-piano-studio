# JJS Piano Studio

Windows GUI for playing Visual Pianos-style Roblox/JJS piano layouts with
hotkeys, MIDI import, online MIDI search, live preview, and audio-to-MIDI
conversion.

The app lives in `outputs/`.

## Quick Start

Install Python 3.11, then run this in PowerShell:

```powershell
cd outputs
py -3.11 -m venv .venv
.\.venv\Scripts\python.exe -m pip install --upgrade pip
.\.venv\Scripts\python.exe -m pip install -r requirements.txt
.\.venv\Scripts\python.exe jjs_piano_studio.py
```

After setup, open the app anytime with:

```powershell
cd outputs
.\.venv\Scripts\python.exe jjs_piano_studio.py
```

Use Python 3.11. Python 3.13 may fail with the audio-to-MIDI packages.

## Main Files

- `outputs/jjs_piano_studio.py`: app launcher
- `outputs/roblox_piano_macro.py`: main GUI and playback engine
- `outputs/audio_to_midi_worker.py`: background audio conversion worker
- `outputs/requirements.txt`: Python packages
- `outputs/README_roblox_piano_macro.md`: full usage guide

Generated files, downloaded MIDI files, local settings, virtual environments,
and conversion logs are ignored by git.
