# Simple Keylogger
This Python script logs keyboard input to a text file using the pynput library. It captures both regular and special keys and stores them in a file named key_log.txt.

Important Notice
This tool is for educational and ethical use only.
Do not use it on systems without explicit permission. Unauthorized use of keyloggers may be illegal and unethical.

Features
Logs all keystrokes (including special keys like Enter, Space, Shift)
Outputs to key_log.txt in the same folder
Runs in the background using pynput.keyboard.Listener

How to Use
Install dependencies:
pip install pynput

Run the script:
python keylogger.py
Keystrokes will be saved in key_log.txt.
To stop the script, use shift+F5 in the terminal of VS code, or modify the code to support a key combination (ESC).

Example output:
hello [Key.space] world [Key.enter]

Disclaimer
This script is meant strictly for learning purposes, such as understanding how keyboard listeners work. Always have consent before running keyloggers on any machine.
