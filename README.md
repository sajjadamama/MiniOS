# Mini OS Simulation in C

This project is a terminal-based simulation of a mini operating system developed in C. It provides various functionalities including media playback, file and directory management, utilities, and system information, all controlled through a user-friendly command-line interface.

## Features

The Mini OS supports the following features:

### Media Playback
- Play audio files (MP3)
- Play video files (MP4)

### File and Directory Operations
- Create directories
- Create files
- Open files with `nano` editor
- Read file content
- Delete files
- List all files in the current directory
- Copy and move files

### System Utilities
- Simple calculator
- Notepad (nano)
- BMI calculator
- Fahrenheit to Celsius converter
- Display system information

### Games
- Word guessing game (2-player)

### Modes
- **User Mode:** Access all functionalities via a menu
- **Kernel Mode:** Displays hardware specifications such as:
  - Number of CPU cores
  - RAM size
  - HDD details

### Multi-terminal Execution
- Each functionality is launched in a new terminal window using `gnome-terminal`.

## Requirements

- GCC compiler
- Linux environment with:
  - `mpg123` for audio playback
  - `mpv` for video playback
  - `nano` for editing files
  - `gnome-terminal` for launching new terminals

## How to Compile and Run

1. **Compile the program:**
   ```bash
   gcc miniOS.c -o miniOS
