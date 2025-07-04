# 🗣️ Text to Voice Converter

A simple web-based Text to Speech (TTS) application built with **HTML**, **CSS**, and **JavaScript**. This project uses the Web Speech API to convert user-entered text into spoken words using the system's voice engine.

---

## 🎯 Features

- Converts user-input text into speech
- Supports multiple voice options (if available in browser)
- Adjustable speech rate and pitch
- Real-time feedback and controls
- Fully responsive and beginner-friendly interface

---

## 🧠 How It Works

1. User enters text into the textarea.
2. Browser’s built-in **Web Speech API** processes the text.
3. User clicks "Speak", and the system reads the text aloud.
4. Optionally, users can select the voice, adjust pitch and rate.

---

## 🛠️ Technologies Used

- **HTML5** — markup structure
- **CSS3** — styling and layout
- **JavaScript (Vanilla)** — logic and Web Speech API integration

---

## 📁 Project Structure

TextToVoiceConverter/
│
├── index.html # Main HTML file
├── style.css # Styling for the app
└── script.js # JavaScript logic using SpeechSynthesis API

yaml
Copy
Edit

---

## 🧪 Browser Compatibility

✅ Supported in most modern browsers (Chrome, Edge, Firefox*)  
❌ May not work in some older or mobile browsers  
> ⚠️ Firefox has limited support for the `speechSynthesis` voices API.

---

## 📌 How to Use

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/TextToVoiceConverter.git
