# 🎙️ Generative AI Voice Assistant (OpenAI + IBM Watson)

This project implements a **full-stack AI-powered voice assistant** capable of understanding spoken user input, generating intelligent responses using a large language model, and replying back with synthesized speech. The system integrates **Speech-to-Text (STT)**, **Natural Language Processing (NLP)**, and **Text-to-Speech (TTS)** to enable seamless voice-based human–computer interaction.

---

## 🔍 Project Overview

The voice assistant accepts **audio input from users**, converts speech into text using **IBM Watson Speech-to-Text**, processes the text using **OpenAI’s GPT-based language model**, and converts the generated response back into speech using **IBM Watson Text-to-Speech**. A responsive web interface built with **HTML, CSS, and JavaScript** allows users to interact with the assistant in real time, while a **Flask backend** orchestrates API communication and response handling.

This project demonstrates end-to-end integration of **AI services, backend APIs, and frontend interaction**, making it suitable for real-world conversational AI applications.

---

## 🚀 Features

- Voice-based interaction using microphone input
- Speech-to-Text conversion using IBM Watson STT
- Intelligent response generation using OpenAI GPT models
- Text-to-Speech synthesis using IBM Watson TTS
- Full-stack architecture with Flask backend
- Interactive web interface with real-time responses
- Modular and extensible design

---

## 🛠️ Tech Stack

- **Backend:** Python, Flask  
- **Frontend:** HTML, CSS, JavaScript, Bootstrap  
- **AI / NLP:** OpenAI GPT (Chat Completions API)  
- **Speech Processing:** IBM Watson Speech-to-Text & Text-to-Speech  
- **Deployment:** Docker (container)

---

## 📂 Project Structure

```bash
generative-ai-chatbot/
├── server.py              # Flask backend server
├── worker.py              # STT, GPT processing, and TTS logic
├── templates/
│   └── index.html         # Frontend interface
├── static/
│   ├── css/
│   └── js/
├── requirements.txt       # Project dependencies
├── Dockerfile             # Container configuration
└── README.md              # Project documentation
```
---

## ⚙️ Installation & Setup

1️⃣ Clone the repository
```bash
git clone https://github.com/VaibhavUNavalagi/generative-ai-chatbot.git
cd generative-ai-chatbot
```
2️⃣ Install dependencies
```bash
pip install -r requirements.txt
```
---
##▶️ Running the Application (Docker)
```bash
docker build . -t generative-ai-voice-assistant
docker run -p 8000:8000 generative-ai-voice-assistant
```
---

### Open your browser and navigate to:
```bash
http://localhost:8000
```
---

## ⚙️ API Workflow

User records voice input from the browser

Audio is sent to the Flask backend

IBM Watson Speech-to-Text converts audio → text

Text is sent to OpenAI GPT for response generation

Generated response is converted to speech using IBM Watson Text-to-Speech

Audio and text responses are returned to the frontend

---

## 🧪 Results & Demonstration
🔹 Voice Interaction Interface
The user can speak directly into the application and receive intelligent spoken responses in real time.
<img width="800" height="600" alt="Image" src="https://github.com/user-attachments/assets/c7107c4e-3246-40e1-8697-77a7ce9e0ae0" />
<img width="800" height="600" alt="image" src="https://github.com/user-attachments/assets/93db939b-e982-4738-9ae2-94c6d867ead2" />

---

### 👤 Author

Vaibhav U Navalagi

---
