# 💬 Gemini AI Chatbot

An interactive, lightweight web-based chatbot that leverages **Google's Gemini 1.5 Flash API** to generate human-like responses. This project is built using **HTML, CSS, and JavaScript**, and styled for a modern, responsive experience.

## 🚀 Features
* Real-time two-way messaging interface
* Auto-resizing input area
* Typing indicator for enhanced UX
* Seamless integration with Gemini AI (via REST API)
* Responsive layout for mobile and desktop
* Styled avatars for user and AI messages

## 🧠 Tech Stack
* **Frontend**: HTML5, CSS3, Vanilla JavaScript
* **AI Model**: Google Gemini 1.5 Flash (via RESTful API)

## 🔧 Setup Instructions
1. **Clone the repo:**
```bash
git clone https://github.com/your-username/gemini-ai-chatbot.git
cd gemini-ai-chatbot
```
2. **Open `index.html` in your browser**
   No build tools or frameworks needed!

## 🌐 API Integration
The chatbot uses the Gemini 1.5 Flash API.
### Endpoint:
```
POST https://generativelanguage.googleapis.com/v1beta/models/gemini-1.5-flash:generateContent?key=YOUR_API_KEY
```
### Request Body:
```json
{
  "contents": [
    {
      "parts": [
        {
          "text": "Your message here"
        }
      ]
    }
  ]
}
```

⚠️ **Important:** Replace the API key with your own key. Never expose it publicly in production.

## 📸 Screenshots
![image](https://github.com/user-attachments/assets/dcb1c084-9e84-4d55-9461-cb4ebbd92615)

## 💡 Future Improvements
* Add support for file/image inputs
* Enable context/history-based conversations
* Store chat logs using localStorage or a backend
* Add voice input with Web Speech API
