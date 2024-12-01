# Audio-to-Text Transcription with Real-Time Word Display

This project processes an audio file, splits it into smaller chunks, and converts the audio into text. The output text is displayed word by word with a delay, simulating a real-time speaking effect.

## Features

- **Audio Chunking**: Splits long audio files into smaller, manageable chunks for efficient processing.
- **Speech-to-Text Conversion**: Converts Arabic audio into text using Google’s speech recognition API.
- **Real-Time Word Display**: Prints the transcribed text word by word with a delay, simulating a speaking effect.

## Requirements

Make sure you have Python installed and the following libraries:

- `pydub`: For audio processing.
- `speech_recognition`: For speech-to-text conversion.

Install the required libraries using pip:

```bash
pip install pydub SpeechRecognition
