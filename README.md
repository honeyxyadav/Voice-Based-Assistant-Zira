# 🎙️ Zira - Python Voice Assistant

Zira is a simple **voice-controlled personal assistant** built in Python.  
It can greet you, search Wikipedia, open websites, play music, tell the time, and launch applications like Chrome and Git Bash — all using your voice commands.

---

## 🚀 Features
- 🗣️ Text-to-Speech using **pyttsx3**  
- 🎤 Speech Recognition using **speech_recognition**  
- 📚 Search queries on **Wikipedia**  
- 🌐 Open popular websites (YouTube, Google, Stack Overflow, University site)  
- 🎶 Play music from your local system  
- ⏰ Tell the current time  
- 🖥️ Open applications like Chrome and Git Bash  
- 📴 Exit gracefully with voice commands like **quit** or **shut down**  

---

## 📂 Project Structure
├── zira.py # Main assistant code
├── requirements.txt # Python dependencies
└── README.md # Documentation

## ⚙️ Installation & Setup

### 1. Clone the repository
```bash
git clone https://github.com/your-username/zira-voice-assistant.git
cd zira-voice-assistant

### 2. Create a virtual environment
python -m venv .venv
source .venv/bin/activate   # On Linux/Mac
.venv\Scripts\activate      # On Windows

### 3. Install dependencies
pip install -r requirements.txt

### 4. Run the assistant
python zira.py

📝 Usage

Run the program.
Zira will greet you based on the time of day.
Speak commands like:
"Open YouTube"
"Search Python in Wikipedia"
"Play music"
"What’s the time?"
"Open Chrome"
"Quit"

📦 Dependencies

pyttsx3
 – Text-to-speech
SpeechRecognition
 – Speech to text
Wikipedia
 – Wikipedia API
google
 – Google search results
datetime
 – Time handling (standard lib)
os
 – System operations (standard lib)
webbrowser
 – Open websites (standard lib)
