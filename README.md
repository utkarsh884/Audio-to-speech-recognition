# Audio-to-Speech Recognition

A simple Jupyter Notebook project demonstrating how to convert audio files to transcribed text using Python's `SpeechRecognition` library and Google's Web Speech API.

## Overview

This repository contains a single Jupyter Notebook that showcases how to:
- Install and use the `SpeechRecognition` library.
- Load and process an audio file.
- Transcribe speech from the audio file using Google's Web Speech API.
- Handle errors such as missing files, unintelligible audio, or network issues.

## Features

- Minimal setup: One notebook, one main dependency.
- Clear, step-by-step demonstration suitable for beginners.
- Prints transcribed text or relevant error messages.
- Designed for use in Google Colab or local Jupyter environments.

## Getting Started

### Prerequisites

- Python 3.7+
- Jupyter Notebook or JupyterLab (or Google Colab)

### Installation

Clone the repository:
```bash
git clone https://github.com/utkarsh884/Audio-to-speech-recognition.git
cd Audio-to-speech-recognition
```

Open the notebook in Jupyter or upload it to Google Colab.

### Usage

1. Launch Jupyter Notebook or open the notebook in Google Colab.
2. Follow the instructions in the notebook:
   - Install the required package: `SpeechRecognition`
   - Set the path to your audio file (WAV format recommended).
   - Run the code cell to transcribe the audio using Google's API.

Example output:
```
You said: the delicious Roma a freshly baked bread filled the bakery
```
If the audio cannot be transcribed, or the file is missing, a helpful error message will be shown.

## Project Structure

- `Audio to speech recognition.ipynb` – Main notebook with code and instructions.

## Notes

- No sample audio files are included; you must provide your own audio file to test the notebook.
- Only Google's Web Speech API is demonstrated.
- The notebook can be extended to use other APIs or handle multiple files.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for improvements or new features.

## License

No license specified.
