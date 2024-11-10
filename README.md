# Keylogger Project

This is a simple keylogger built using Python that captures key events (key presses, key holds, and key releases) and logs them into both a text file (`key_log.txt`) 
A JSON file (`key_log.json`). The project uses Python's `tkinter` library for creating the graphical user interface (GUI) and `pynput` for handling keyboard events.

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Technical Requirements](#technical-requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Generated Files](#generated-files)
- [Important Notes](#important-notes)
- [License](#license)

## Project Overview

This project is designed to log every key event during a session, which includes:
- **Key Press**: When a key is pressed.
- **Key Hold**: When a key is held down.
- **Key Release**: When a key is released.

The keylogger uses a simple GUI with two buttons — **Start** and **Stop** — allowing the user to control the logging process. 
All captured key events are written to a text file and saved in a structured JSON format.

> **Important**: This project is for educational purposes only. Make sure you have explicit permission to use it on any system.

## Features

- **Start/Stop Logging**: Easily start and stop the keylogging process using a graphical user interface.
- **Key Capture**: Records all key events, including pressing, holding, and releasing keys.
- **Text and JSON Logs**: Saves the captured keys in both a human-readable text file (`key_log.txt`) and a structured JSON file (`key_log.json`).
- **Cross-Platform**: Works on all major platforms, including Windows, macOS, and Linux (as long as `pynput` is supported).

## Technical Requirements

Before using the keylogger, ensure you have the following Python environment setup:

- **Python 3.6+**: This project requires Python 3.6 or higher.
- **Dependencies**:
  - `tkinter` (for GUI): Comes pre-installed with Python, but some systems may require separate installation.
  - `pynput` (for key events handling): Can be installed via pip.

## Installation

1. **Clone this repository**:
   First, clone the repository to your local machine.
   ```bash
   git clone https://github.com/sanjai104/Keylogger.git
   cd keylogger
   ```
2. **Install dependencies**:
   Install the required Python libraries. If you don't have pynput installed, you can install it using pip:
   ```bash
   pip install pynput
   ```
3. **Run the script**:
    After installing the dependencies, run the keylogger script:
   ```bash
   python keylogger.py
   ```

## Usage

1. **Starting Keylogger**:
   - Open the GUI, and click on the Start button to begin logging the keys. The keylogger will start capturing key events (press, hold, and release).
   - A message will appear in the GUI indicating that the keylogger is running and that key events are being saved to the files.
2. **Stopping Keylogger**:
   - Click the Stop button to stop the keylogger and disable the key event capturing.
   - Once stopped, the logs will be saved, and the GUI will notify you that the keylogger has stopped.
3. **Viewing Logs**:
   - You can view the captured key events in the `key_log.txt` , where the keys are logged in a simple text format.
   - The `key_log.json` file will contain the same data in a structured format that can be processed programmatically.
  
## GUI Interface

- **Start Button**: Initiates the keylogging process.
- **Stop Button**: Stops the keylogging process.
- **Status Label**: Displays the current status of the keylogger (whether it is running or stopped).

## Generated Files

1. `key_log.txt`
   A text file that logs all the captured key events. It will record key events as strings, one per line:
   - Pressed 'a'
   - Held 'a'
   - Released 'a'
   - Pressed 'b'
2. `key_log.json`
   A JSON file that contains a structured record of the captured key events. This format allows for easier parsing and processing:
   [
  {"Pressed": "'a'"},
  {"Held": "'a'"},
  {"Released": "'a'"},
  {"Pressed": "'b'"}
]

## Important Notes

- **Legal and Ethical Considerations**: This keylogger is meant for educational purposes only. Unauthorized usage of a keylogger is illegal and unethical. Always get explicit permission from the owner of the device you intend to use this on.
- **Potential Risks**: Keyloggers can be misused, so use this code responsibly. Be aware of the risks associated with data collection, security, and privacy violations.
- **Security**: The captured data is stored locally. Ensure that you take appropriate measures to protect this data and prevent unauthorized access.

## License
This project is open-source and available under the MIT License.

Feel free to modify, distribute, or contribute to this project.



 






