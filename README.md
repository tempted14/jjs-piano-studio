# JJS Piano Studio

Windows GUI for playing Visual Pianos-style Roblox/JJS piano layouts with
hotkeys, MIDI import, online MIDI search, live preview, and audio-to-MIDI
conversion.

The app lives in `outputs/`.

## Quick Start

Use Python 3.11. From PowerShell:

```powershell
cd outputs
.\setup_python311_venv.ps1
.\.venv\Scripts\python.exe jjs_piano_studio.py
```

If PowerShell blocks the setup script:

```powershell
Set-ExecutionPolicy -Scope CurrentUser RemoteSigned
```

Then run the setup script again.

## Main Files

- `outputs/jjs_piano_studio.py`: app launcher
- `outputs/roblox_piano_macro.py`: main GUI and playback engine
- `outputs/audio_to_midi_worker.py`: background audio conversion worker
- `outputs/requirements.txt`: Python packages
- `outputs/README_roblox_piano_macro.md`: full usage guide

Generated files, downloaded MIDI files, local settings, virtual environments,
and conversion logs are ignored by git.
