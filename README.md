[README (3).md](https://github.com/user-attachments/files/25437935/README.3.md)
# 📬 Gmail & Google Calendar AI Agent (n8n Workflow)

This project is an **n8n automation workflow** that connects **Telegram**, **Gmail**, and **Google Calendar** through an **AI Agent** powered by OpenAI.

You can chat with the agent on Telegram to:
- Read emails from Gmail  
- Send emails via Gmail  
- Create events in Google Calendar  
- Receive confirmations back in Telegram  

All actions are intelligently decided by the AI Agent using natural language.

---

## 🚀 Features

- 🤖 AI-powered Telegram assistant  
- 📥 Read Gmail messages on demand  
- 📤 Send emails via Gmail  
- 📅 Create Google Calendar events  
- 🔁 Fully automated with n8n + LangChain  
- 🧠 Natural-language command handling  

---

## 🧩 Workflow Overview

1. **Telegram Trigger**  
   Receives incoming Telegram messages.

2. **AI Agent (LangChain)**  
   - Interprets user intent  
   - Decides whether to read email, send email, or create calendar events  
   - Uses OpenAI for reasoning  

3. **Gmail Tools**  
   - Get many messages  
   - Send messages  

4. **Google Calendar Tool**  
   - Create calendar events  

5. **Telegram Send Message**  
   Sends the AI response back to the user.

---

## 🗂️ Nodes Used

- Telegram Trigger  
- AI Agent (`@n8n/n8n-nodes-langchain.agent`)  
- OpenAI Chat Model  
- Gmail Tool (Get & Send)  
- Google Calendar Tool  

---

## ⚙️ Requirements

- n8n (cloud or self-hosted)
- Telegram Bot Token
- OpenAI API Key
- Gmail OAuth2 credentials
- Google Calendar OAuth2 credentials

---

## 🔐 Credentials Setup

### Telegram
- Create a bot using **@BotFather**
- Add Telegram API credentials in n8n

### OpenAI
- Add your OpenAI API key
- Select a chat model (example: `gpt-5-mini`)

### Gmail
- Enable Gmail API in Google Cloud
- Configure OAuth2 credentials in n8n

### Google Calendar
- Enable Google Calendar API
- Configure OAuth2 credentials in n8n

---

## 📥 Installation & Setup

### 1. Import Workflow
- Open n8n
- Go to **Workflows → Import**
- Paste the provided JSON workflow

### 2. Connect Credentials
- Attach all required credentials to each node
- Ensure Gmail & Calendar scopes are enabled

### 3. Activate Workflow
- Enable the workflow
- Send commands to your Telegram bot

---

## 🧠 Example Commands

- “Check my latest emails”  
- “Send an email to John about the meeting”  
- “Schedule a meeting tomorrow at 3 PM”  
- “Create a calendar event for Friday”  

---

## 🛡️ Safety & Usage Notes

- Review AI-generated email content before real-world use  
- Monitor API usage to avoid unexpected costs  
- Not recommended for sensitive or regulated data  

---

## 📄 License

MIT License — free to use, modify, and distribute.

---

## ⭐ Credits

Built with:
- n8n  
- Telegram Bot API  
- OpenAI  
- Gmail API  
- Google Calendar API  

---

## 🤝 Contributing

Pull requests and improvements are welcome.

---

Automate smarter, not harder ✨
