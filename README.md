

#  Jarvis Assistant - Python, Streamlit & Speech Recognition

This repository contains a collection of AI-powered assistant tools built using **Python**, **Streamlit**, **Speech Recognition**, and **Text-to-Speech** technologies.
The project includes:

* **Jarvis Voice Assistant** (offline, command-based)
* **Jarvis AI Chatbot (Streamlit)** powered by Gemini
* **Text-to-Speech Automation Script**

Each module is designed to improve automation, provide hands-free system control, and deliver a personalized assistant experience.


# 1. Jarvis Voice Assistant (Python)

A smart voice-controlled assistant built using:

* "pyttsx3" for offline text-to-speech
* "speech_recognition" for converting voice to text
* "os" for system operations
* "pywhatkit" for optional automation tasks (WhatsApp, YouTube, etc.)

### Features

* Open Notepad via voice
* Open Chrome via voice
* Speak responses with pyttsx3
* Continuous listening loop
* Graceful stop command: **“Jarvis stop”**
* Handles recognition errors smoothly

# 2. Jarvis AI Chatbot (Streamlit + Gemini)

A Streamlit-based chatbot interface that uses **Google Gemini (generativeai)** and speaks responses using **pyttsx3**.

### Features

* Clean web UI using Streamlit
* Built-in text and speech response
* Image display and welcome message
* Dynamic conversation with Gemini model
* Personalized greeting with user’s name


# 3. Text-to-Speech Script (Python)

A simple but effective TTS script that greets multiple people using a loop.

# Features

* Uses pyttsx3 (works offline)
* Loops through a list of names
* Speaks a personalized message
* Good for batch audio generation


# Technologies Used

* **Python**
* **Streamlit**
* **pyttsx3** (Text-to-Speech)
* **speech_recognition**
* **pywhatkit**
* **Google Generative AI (Gemini)**
* **OS & Time modules**



# Future Improvements

* Add wake-word activation (e.g., “Hey Jarvis”)
* Add more voice commands
* Integrate system-level automation
* Add conversation history in Streamlit UI
* Add error handling logs
* Add UI themes for chatbot


# Author

Aditya Raj
Enthusiastic Python developer building AI-powered tools and assistants.
If you like the project, ⭐ star the repository to support future development!

