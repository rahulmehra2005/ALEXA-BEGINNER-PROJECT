# ALEXA-BEGINNER-PROJECT
This project is a simple Voice Assistant built using Python libraries such as SpeechRecognition, pyttsx3, pywhatkit, Wikipedia, and pyjokes.

This project is a Voice-Controlled Virtual Assistant developed in Python that works similarly to Amazon Alexa. It listens to the user's speech through a microphone, processes the voice command, and performs various tasks automatically. The assistant can play YouTube videos or songs, tell the current time, provide quick information from Wikipedia, crack jokes, and respond to simple conversations. It uses speech recognition to convert voice to text and text-to-speech to reply back to the user, making interaction natural and hands-free.

 What This Assistant Can Do?
Function	Example Command	Output
Play YouTube music/video	“Alexa play Bollywood songs”	Opens YouTube and plays
Tell current time	“Alexa what’s the time?”	Speaks the time
Wikipedia search	“Alexa who is APJ Abdul Kalam?”	Tells a 1-line summary
Tell jokes	“Alexa tell me a joke”	Speaks a random joke
Fun replies	“Alexa are you single?”	Gives a funny response
🛠️ What You Need Before Running

Before executing the project, ensure the following:
✔ Python installed (recommended version: 3.10 – 3.12)
✔ A working microphone enabled in Windows privacy settings
✔ Internet connection (for speech recognition & YouTube actions)

Libraries Required

Install these Python modules using:
pip install SpeechRecognition
pip install pyttsx3
pip install pywhatkit
pip install wikipedia
pip install pyjokes
pip install pyaudio

⚠ If PyAudio fails, try:
pip install pipwin
pipwin install pyaudio

How to Run the Project?

Open Command Prompt / Terminal
Navigate to your project folder:
cd path/to/your/project
Run the script:
python alexa.py
You will see “Listening…” on the screen → now speak your commands starting with Alexa.

Example:

Alexa play Despacito

⛔ How to Stop the Assistant
You can stop the voice assistant by:
Pressing Ctrl + C in the terminal
Closing the terminal window
Stopping the Python program from your IDE (VS Code, PyCharm, etc.)

This is a beginner project so it can't do much, but can do the following functions:

| Function                 | Example Command                 | Output                  |
| ------------------------ | ------------------------------- | ----------------------- |
| Play YouTube music/video | “Alexa play Bollywood songs”    | Opens YouTube and plays |
| Tell current time        | “Alexa what’s the time?”        | Speaks the time         |
| Wikipedia search         | “Alexa who is APJ Abdul Kalam?” | Tells a 1-line summary  |
| Tell jokes               | “Alexa tell me a joke”          | Speaks a random joke    |
| Fun replies              | “Alexa are you single?”         | Gives a funny response  |
