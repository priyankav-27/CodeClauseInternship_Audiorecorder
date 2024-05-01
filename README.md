# Audio Recorder App

This is a simple Audio Recorder application built using Python's tkinter library for the GUI, sounddevice for recording audio, and wavio for saving the recorded audio files.

## Features

- Record audio for a specified duration
- Save the recorded audio files with custom filenames
- View the list of recorded audio files
- Default save directory: `recordings`

## Requirements

- Python 3.x
- tkinter
- sounddevice
- wavio

## Installation

1. Clone the repository:

```bash
git clone https://github.com/priyankav-27/audio-recorder-app.git
 ```
2.Navigate to the project directory

```bash
cd audio-recorder-app
```
3.Install the required depencies
```bash
pip install -r requirements.txt
```
4.Run the application
```bash
python audio_recorder_app.py
```
## Usage

-Launch the application.
-Enter the duration (in seconds) for recording.
-Enter the desired filename for the recorded audio file.
-Click the "Record" button to start recording.
-Click the "Record" button again to stop recording.
-View the list of recorded audio files in the listbox.
