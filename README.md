
Page link:
https://abdulaziz.site.je/


# 🎙️ AI Voice Chatbot

A modern web-based AI Voice Chatbot that allows users to interact with Google's Gemini AI using voice. The application converts speech into text, sends it to the Gemini API through a secure PHP backend, and displays AI responses in a clean, responsive chat interface.

---

## ✨ Features

* 🎤 Voice-to-Text using the browser's Speech Recognition API
* 🤖 AI-powered responses using **Google Gemini API**
* 💬 Real-time chat interface
* 📱 Responsive design for desktop and mobile
* 🔒 Secure API key handling with PHP backend
* 🌍 Arabic language support (can be customized for other languages)
* ⚡ Lightweight and easy to deploy

---

## 🛠️ Technologies Used

* HTML5
* CSS3
* JavaScript (Vanilla)
* PHP
* Google Gemini API
* Web Speech API

---

## 📂 Project Structure

```text
├── index.html        # Main user interface
├── style.css         # Styling
├── app.js            # Voice recognition & frontend logic
├── speak.php         # Backend API handler
├── config.php        # Stores Gemini API key
└── README.md
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/voice-chatbot.git
cd voice-chatbot
```

### 2. Get a Gemini API Key

Create a Gemini API key from Google AI Studio.

### 3. Configure the API Key

Open:

```php
config.php
```

Add your API key:

```php
define('GEMINI_API_KEY', 'YOUR_API_KEY');
```

### 4. Run the project

Place the project inside your PHP server directory (XAMPP, WAMP, Laragon, etc.).

Example:

```
htdocs/
    voice-chatbot/
```

Start Apache and visit:

```
http://localhost/voice-chatbot/
```

---

## 🚀 How It Works

1. User clicks the microphone button.
2. Browser converts speech into text.
3. The text is sent to the PHP backend.
4. PHP securely sends the request to the Gemini API.
5. Gemini generates a response.
6. The response is displayed instantly in the chat.

---

## 📸 Preview

```
🎤 User speaks
      ↓
Speech Recognition
      ↓
JavaScript
      ↓
PHP Backend
      ↓
Google Gemini API
      ↓
AI Response
      ↓
Chat Interface
```

---

## 🌐 Browser Support

* ✅ Google Chrome (Recommended)
* ✅ Microsoft Edge
* ⚠️ Firefox (Limited Speech Recognition support)
* ⚠️ Safari (Limited support)

---

## 🔐 Security Notes

* Never upload your `config.php` containing a real API key.
* Keep your API key private.
* Add `config.php` to `.gitignore` if it contains sensitive information.

Example:

```gitignore
config.php
```

---

## 📌 Future Improvements

* Text-to-Speech (AI voice responses)
* Conversation history
* Multiple language support
* Dark mode
* User authentication
* Streaming AI responses
* Conversation export

---

## 👨‍💻 Author

Developed by **Abdulaziz Alharbi**

---

## 📄 License

This project is licensed under the MIT License.

Feel free to use, modify, and improve it for personal or educational purposes.
