# voice-transcribe

A simple CLI tool that transcribes audio files (m4a/mp3/wav) using OpenAI Whisper.

## Requirements
- Python 3.10+
- ffmpeg

### Install ffmpeg (macOS)
```
brew install ffmpeg
```

## Install (recommended)
Use pipx so it installs in an isolated environment and exposes the `transcribe` command globally:
```
pipx install git+https://github.com/<YOUR_USERNAME>/voice-transcribe.git
```

## Usage
transcribe input.m4a
transcribe input.m4a output.txt
transcribe input.m4a output.txt turbo

## Models
tiny, base, small, medium, large, turbo