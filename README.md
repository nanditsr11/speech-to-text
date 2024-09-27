## Speech to Text and Translation Application
This Python-based application captures speech in Hindi, translates it into English, and displays both the original and translated text in a GUI text editor. It continuously listens for speech input at random intervals between 5 and 10 seconds, making it interactive and responsive to audio input.

## Features
Captures speech input in Hindi using the speech_recognition library.
Translates recognized Hindi text into English using the googletrans library.
Displays both the original Hindi text and the translated English text in a user-friendly GUI.
Runs continuous speech recognition at random intervals, making it suitable for long-term use.

## Prerequisites
To run this application, ensure you have the following dependencies installed:

## Required Libraries:
SpeechRecognition: for speech recognition capabilities.
     pip install SpeechRecognition

PyAudio: for microphone access (required by SpeechRecognition).

## For Linux/macOS:
      pip install pyaudio

## For Windows, download the appropriate binary from here and install it using:
      pip install path/to/downloaded_file.whl

## googletrans: for language translation.

      pip install googletrans==4.0.0-rc1

## Tkinter: for creating the graphical user interface (Tkinter comes pre-installed with most Python distributions).

## For Ubuntu:
      sudo apt-get install python3-tk

## How to Run
Clone or download this repository.
      git clone <repository_url>
      cd <project_directory>

## Run the Python script.
      python script_name.py

## Usage:

Click on the Start Listening button to start capturing speech.
The application will listen for Hindi speech input and translate it to English.
Both the original Hindi text and the English translation will be displayed in the GUI text editor.

## GUI Components

## Text Editor: A scrollable text widget that displays recognized Hindi speech and its English translation.
Start Button: A button to start the continuous speech recognition process.

## Key Functions

# capture_speech(): Captures Hindi speech input from the microphone using the speech_recognition library.
# translate_text(): Translates the recognized Hindi text to English using googletrans.
# run_speech_to_text(): Orchestrates the speech capture and translation process, displaying both texts in the text editor.
# continuous_listening(): Continuously listens for speech at random intervals between 5 and 10 seconds.
# start_listening(): Starts the continuous listening function in a separate thread to avoid freezing the GUI.

## License
This project is open-source. Feel free to modify and distribute it.

