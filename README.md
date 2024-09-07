This Python program converts the text from a PDF file into audio using the `pyttsx3` text-to-speech (TTS) engine. It reads a given PDF, extracts the text from each page, and either reads it aloud or saves the spoken text to an audio file.

## Features
- **PDF Reader**: Utilizes `PyPDF2` to extract text from PDF files.
- **Text-to-Speech Engine**: Uses `pyttsx3` to convert the extracted text to speech.
- **Adjustable Speaking Rate & Volume**: Set the speech rate and volume according to your preference.
- **Voice Selection**: Automatically selects an English US voice if available.
- **Audio Output**: Saves the last extracted text as an audio file (optional).

## Requirements
- `PyPDF2` for reading PDF files
- `pyttsx3` for text-to-speech conversion

## How It Works
1. Open a PDF file and extract text from each page.
2. The `pyttsx3` engine reads the extracted text aloud or can save the output as an audio file.
3. You can adjust the speaking rate, volume, and choose a voice for the TTS engine.

## Usage
To use the program, update the `file` variable with the path to your PDF. The program will extract text from the PDF and read it using the TTS engine or save the audio to a file.
