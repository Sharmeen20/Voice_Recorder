# VoiceRecorder 🎙️

A simple Python-based voice recorder that allows users to record audio for a custom duration and optionally play it back. The recording is saved with a timestamped filename for easy organization.

## 🚀 Features

- ⏱️ Adjustable recording duration
- 📁 Saves audio as WAV file with timestamp
- 🔊 Optional playback after recording
- 🧠 Handles invalid input gracefully

## 🧰 Requirements

- Python 3.6+
- `sounddevice`
- `scipy`
- `playsound`

Install dependencies:
```bash
pip install sounddevice scipy playsound

## How to Run

1. Clone the repository or download the script:
  ```bash
  git clone https://github.com/your-username/voice-recorder.git
  cd voice-recorder

2. Run the script:
  ```bash
  python voice_recorder.py

3. Follow the prompts:
  Enter recording duration in seconds
  Choose whether to play the recording

## Project Structure

voice-recorder/
├── voice_recorder.py
└── README.md

## Notes

The recording is saved in the current directory with a name like Recording_20251028_145830.wav.
You can change the sample rate or audio channels in the script if needed.
