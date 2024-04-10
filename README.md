# Music Player Command Line Tool

## Overview
Welcome to the Music Player Command Line Tool! This tool allows you to play your favorite music in the highest quality and bitrate, either from a song name or via a YouTube link. It utilizes several libraries to provide a seamless music experience.

## Features
- High-quality and high-bitrate music playback.
- Autoplay functionality for continuous listening.
- User-friendly controls for managing playback.
- Ability to play music directly from YouTube URLs.

## Getting Started

### Prerequisites
- Ensure you have Python installed on your system.

### Installation
1. Download the latest release from the 'Releases' section.
2. Unzip the downloaded file to your preferred directory.

### Usage

#### For Linux Users:
Open your terminal and navigate to the directory where you unzipped the files. Then, run the following command to start the tool with root privileges:
```bash
sudo su -c 'python controller.py'
```
### For Windows Users:
If you encounter any issues or errors, please install `ffmpeg` and `yt-dlp` executables separately, and add them to your PATH environment variable. Then, navigate to the tool's directory and run the following command:

```bash
python controller.py
```
