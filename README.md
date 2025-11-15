
# 🤖 Chatbot using WeChaty

This project is a simple chatbot built using **WeChaty**, a Python framework for building conversational bots that can interact on platforms like **WeChat**, **WhatsApp**, and others via the WeChaty Puppet service.

---

## 🚀 Features

- Replies automatically to messages (e.g. "ding" → "dong")
- Built using Object-Oriented Programming (OOP) structure
- Supports async message handling
- Can handle private chats and group mesg

---

## 🧠 How WeChaty Works

WeChaty connects to chat platforms through something called a **Puppet** —  
which acts as a middle layer between your code and the actual chat platform.

The main components are:
1. **Wechaty** – The core bot framework that listens to events.
2. **Puppet Service** – The backend that connects to chat apps (WeChat, WhatsApp, etc.)
3. **Bot Logic** – Your code that defines what the bot does when it receives messages or events.

When you run the bot:
- It connects to the puppet service.
- Listens for events like messages, logins, or friendships.
- Responds based on your defined logic.
## Steps to Run
pip install -r requirements.txt

python bot.py



