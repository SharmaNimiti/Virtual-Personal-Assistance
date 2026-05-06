# 🎙️ Voice-Based Virtual Assistant with Authentication

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Status](https://img.shields.io/badge/Status-Active-success.svg)
![Project Type](https://img.shields.io/badge/Project-AI%20%7C%20Automation-orange)
![License](https://img.shields.io/badge/License-MIT-green.svg)

A Python-based **Voice Assistant** integrated with a basic **voice authentication system**.  
This assistant can recognize voice commands, respond using speech, and perform tasks like searching Wikipedia, opening websites, sending emails, and capturing images.

---

## 🚀 Features

- 🔐 **Voice Authentication**
  - Secure access using predefined voice passphrases
  - Basic identity verification before assistant activation

- 🗣️ **Speech Recognition**
  - Converts voice input into text using Google Speech API

- 🔊 **Text-to-Speech**
  - Responds to users with voice output using `pyttsx3`

- 🌐 **Web Automation**
  - Open:
    - YouTube
    - Google
    - StackOverflow
    - Gmail

- 📚 **Wikipedia Integration**
  - Fetch and speak summarized information

- 📷 **Camera Access**
  - Capture images using webcam

- ⏰ **Real-Time Updates**
  - Tells current system time

- 📧 **Email Functionality**
  - Send emails via SMTP

- 💬 **Interactive Experience**
  - Greets users based on time of day

---

## 🛠️ Tech Stack

- **Python**
- `SpeechRecognition`
- `pyttsx3`
- `wikipedia`
- `smtplib`
- `ecapture`
- `webbrowser`

---

## ⚙️ How It Works

```text
1. Start the application
2. Voice authentication is triggered
3. User speaks passphrase
4. If authenticated:
   → Assistant activates
   → Listens to commands
   → Executes tasks
   → Responds via voice

🎤 Example Commands
"Open YouTube"
"Search Wikipedia for Artificial Intelligence"
"What is the time"
"Open Google"
"Take a photo"
"Send email"
