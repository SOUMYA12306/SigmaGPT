# 🤖 SigmaGPT — AI-Powered Conversational Assistant

<p align="center">
  <img src="https://img.shields.io/badge/Node.js-v18%2B-green?style=for-the-badge&logo=nodedotjs" alt="Node.js" />
  <img src="https://img.shields.io/badge/React-2023%2B-blue?style=for-the-badge&logo=react" alt="React" />
  <img src="https://img.shields.io/badge/Gemini_API-Supported-orange?style=for-the-badge&logo=google" alt="Gemini API" />
  <img src="https://img.shields.io/badge/OpenAI-Integrated-brightgreen?style=for-the-badge&logo=openai" alt="OpenAI API" />
  <img src="https://img.shields.io/badge/License-MIT-purple?style=for-the-badge" alt="License" />
</p>

---

## 📌 About The Project

> **SigmaGPT** is a full-stack, production-ready AI Chatbot platform built to deliver real-time, streaming conversational responses with a modern, sleek dark-themed UI. Inspired by ChatGPT, it showcases high-performance API integration, backend state management, and seamless client-server interaction.

---

## 🌟 Key Features

- **⚡ Real-Time Streaming Responses:** Experience instant response generation using Server-Sent Events (SSE) with zero lag.
- **🎨 Sleek Dark-Themed UI:** Clean, modern, and responsive user interface engineered for an optimal user experience.
- **💬 Chat Session Management:** Easily create new chat sessions, preserve context, and browse through past conversation history.
- **🔑 Dual API Support:** Configurable to run with either **OpenAI API** or **Google Gemini API** for free-tier development and testing.
- **🛡️ Secure Environment Setup:** Isolated backend environment variable management via `.env` files to safeguard private credentials.

---

## 🛠️ Tech Stack & Architecture

| Layer | Technology Used |
| :--- | :--- |
| **Frontend** | React.js, HTML5, CSS3 / Modern Styling |
| **Backend** | Node.js, Express.js |
| **AI Integration** | Google Gemini API / OpenAI GPT Models |
| **Version Control** | Git & GitHub |

---

## 🚀 Quick Start Guide

Follow these simple steps to set up and run **SigmaGPT** on your local machine.

### 1️⃣ Clone the Repository
```bash
git clone [https://github.com/soumyac427/SigmaGPT.git](https://github.com/soumyac427/SigmaGPT.git)
cd SigmaGPT
cd Backend
npm installPORT=8080
OPENAI_API_KEY=your_openai_api_key_here
# Optional (for free tier setup via Gemini):
GEMINI_API_KEY=your_gemini_api_key_here# Terminal 1: Launch Backend Server
node server.js

# Terminal 2: Launch Frontend Application
cd ../Frontend
npm install
npm start
