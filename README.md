# Key-Logger

🔐 Educational Keylogger in Python

This is a **basic keylogger** built using Python’s `pynput` library for **educational and ethical purposes only**-. It records keystrokes and logs them to a file named `key_log.txt`

📌 Disclaimer

⚠️ This tool is intended strictly for:

- Personal use on your own machine

- Learning how keyboard event listeners work

- Ethical cybersecurity experiments.


Do not use this tool for spying, monitoring others without consent, or any illegal activity.

🧠 Features

- Records all keystrokes, including special keys (e.g., Enter, Space, Backspace).
- Saves logs to a `.txt` file.
- Runs in the terminal with visible prompts.
- Stops logging when you press the `Esc` key.

🔧 Requirements

- Python 3.x
- `pynput` library

Install the required library:

        pip install pynput

▶️ How to Run

- Save the script as keylogger.py

- Run it:

            python3 project5.py

- Start typing anywhere (terminal, browser, Notepad, etc.)

- Press Esc to stop the logger

- View recorded keystrokes in key_log.txt

  📝 Example Output

Hello world
123!

Your key_log.txt may look like:

Hello[space]world[enter]123!

🔄 How It Works

- Uses pynput.keyboard.Listener to detect key presses

- Normal characters are logged as-is

- Special keys are logged as [key_name]

- Writes every keystroke to key_log.txt in real-time

👤 Author

Gautam Singh

Cybersecurity & Python Enthusiast














