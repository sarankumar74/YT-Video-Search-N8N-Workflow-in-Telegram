# 🤖 Telegram to YouTube Video Searcher (n8n Automation)
🔍 *n8n • Telegram Bot • Gemini API • YouTube Search Automation*

## 🚀 Tech Stack & Domains
![n8n](https://img.shields.io/badge/Automation-n8n-orange)
![Telegram](https://img.shields.io/badge/Platform-Telegram-blue)
![Gemini](https://img.shields.io/badge/AI-Gemini%20API-brightgreen)
![HTTP](https://img.shields.io/badge/Integration-HTTP%20Requests-gray)
![Domain](https://img.shields.io/badge/Domain-Chatbot%20Automation%20%26%20Search-navy)

---

## 📘 Overview
**Telegram to YouTube Video Searcher** is an **n8n-based chatbot automation** that allows users to search YouTube videos directly from Telegram.

Users send any text message to a Telegram bot. The workflow understands the intent using **Gemini**, searches YouTube, extracts video URLs, and sends the best-matching video back to the user—all automatically.

---

## 🎯 Problem Statement
Searching for YouTube videos requires switching between apps and manually copying links. For chat-based users, this breaks flow and slows discovery.

This project enables:
- YouTube video search directly from Telegram  
- Natural language understanding of user intent  
- Instant video link delivery  

All handled through automation.

---

## 🗺️ Workflow Logic

### 🔁 Workflow Steps
1. **Telegram Chat Trigger**
   - Receives user message

2. **Gemini Message Model**
   - Understands user intent
   - Converts message into a search-friendly query

3. **HTTP Node (YouTube Search)**
   - Searches YouTube using the processed query
   - Returns raw HTML or response data

4. **Function Node**
   - Parses HTML
   - Extracts YouTube video URLs

5. **Telegram Send Message**
   - Sends video link back to the user

---

## 🧰 Tools & Integrations
- **n8n** (workflow orchestration)
- **Telegram Chat Trigger**
- **Google Message Model (Gemini)**
- **HTTP Node**
- **Function Node**
- **Telegram Send Message**

---

## 📤 Output
- Telegram bot replies with relevant YouTube video link
- Fully automated chat-based experience

---
<summary>📸 Click to view UI screenshots</summary>

#### N8N Canvas Page  
![Home Page](https://github.com/user-attachments/assets/35d98e48-ccd3-483f-a70c-c5dd40899eb8)

#### Telegram Results Page 
![Result Page](https://github.com/user-attachments/assets/06b20b1f-e541-4ec3-9a0c-0a44a6c5d014)


---

## 🛠️ Setup & Execution

### Prerequisites
- n8n (localhost or cloud)
- Telegram account
- Telegram bot token
- Gemini API key

### Steps
1. Create a Telegram bot using BotFather
2. Get bot token and chat ID
3. Create a new workflow in n8n
4. Import workflow from file or URL
5. Configure Telegram credentials
6. Configure Gemini API key
7. Activate workflow

---

## 🔒 Notes
- Built entirely using **n8n**
- Works on localhost or cloud n8n
- Visual workflow using n8n canvas
- No custom backend code required

