# Robospeak-text-to-speech-

# RoboSpeak – Text-to-Speech Converter

**Description:**  
RoboSpeak is a simple text-to-speech Python application that converts user input into spoken audio using Windows' built-in speech engine (SAPI.SpVoice).

**Features:**
- Real-time voice output for typed text
- Works on Windows using `pywin32`
- Loop continues until user types "quit" or "exit"

**Technologies Used:**
- Python
- `win32com.client` (SAPI)

**How to Run:**
1. Ensure you’re using **Windows OS**.
2. Install the required module:
   ```bash
   pip install pywin32
