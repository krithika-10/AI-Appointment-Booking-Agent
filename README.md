# 🤖 AI Appointment Booking Agent

A conversational AI agent built with **n8n** that allows users to book appointments through natural language chat. The agent understands user intent, collects details, and automatically creates calendar events — no manual input required.

---

## 🎥 Demo

👉 [Watch the demo recording](https://drive.google.com/file/d/1piSrOaMmAWBW3YzuRJKI0kscKA2wN65d/view?usp=sharing)

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| [n8n](https://n8n.io) | No-code workflow automation platform |
| OpenAI (GPT) | Natural language understanding and conversation |
| Google Calendar API | Automatic event creation upon booking confirmation |
| Simple Memory (n8n) | Maintains conversation context across messages |

---

## ⚙️ How It Works

1. User sends a message through the chat interface
2. The AI Agent (powered by OpenAI) understands the intent and asks for:
   - Name
   - Preferred date
   - Preferred time
3. Once all details are collected, the agent confirms the booking
4. A Google Calendar event is automatically created
5. The conversation context is maintained throughout using Simple Memory

---

## 🔁 Workflow Overview

```
Chat Trigger
     ↓
  AI Agent  ←→  Simple Memory (conversation context)
     ↓
OpenAI Chat Model (understands & responds)
     ↓
Google Calendar (creates the appointment event)
```

---

## 📦 How to Use This Workflow

1. Download the `workflow.json` file from this repo
2. Open [n8n](https://n8n.io) and log in
3. Click **"Import workflow"** and upload the JSON file
4. Connect your own credentials:
   - OpenAI API key
   - Google Calendar account
5. Activate the workflow and open the chat to test it

---

## 💡 What I Learned

- How to build AI agents using n8n's visual canvas
- Connecting large language models (OpenAI) to real-world tools
- Implementing conversation memory for multi-turn chat
- Integrating Google Calendar API through no-code automation
- End-to-end workflow design from user input to calendar output

---

## 👩‍💻 Built By

**Krithika S**  
BCA (Data Science) Student | Jyoti Nivas College Autonomous, Bengaluru  
[LinkedIn](#) • [GitHub](#)
