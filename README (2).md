# 🕷️ Telegram Spider-Man AI Agent (n8n Workflow)

This project is an **n8n automation workflow** that connects **Telegram** with an **AI Agent** powered by OpenAI.  
The agent role-plays as **Spider-Man**, responding to user messages with witty, heroic, in-character dialogue.

The workflow listens for incoming Telegram messages, sends them to an AI agent with a custom system prompt, and replies back to the same Telegram chat.

---

## 🚀 Features

- 🤖 AI-powered Telegram bot
- 🕷️ Fully in-character Spider-Man personality
- 💬 Real-time message handling
- 🔁 End-to-end automation using n8n
- 🧠 Uses OpenAI chat models via LangChain nodes

---

## 🧩 Workflow Overview

1. **Telegram Trigger**
   - Listens for incoming messages
2. **AI Agent (LangChain)**
   - Receives message text
   - Applies Spider-Man system prompt
   - Generates a response using OpenAI
3. **Send Telegram Message**
   - Sends AI response back to the original chat

---

## 🗂️ Nodes Used

- `Telegram Trigger`
- `AI Agent (@n8n/n8n-nodes-langchain.agent)`
- `OpenAI Chat Model`
- `Telegram Send Message`

---

## ⚙️ Requirements

- n8n (self-hosted or cloud)
- Telegram Bot Token
- OpenAI API Key
- Internet access

---

## 🔐 Credentials Needed

### Telegram
- Create a bot using **@BotFather**
- Add Telegram credentials in n8n

### OpenAI
- Add your OpenAI API key in n8n credentials
- Select a chat-capable model (e.g. `gpt-5-mini`)

---

## 📥 Installation & Setup

### 1. Import Workflow
- Open n8n
- Go to **Workflows → Import**
- Paste the provided JSON workflow

### 2. Configure Credentials
- Attach your **Telegram API** credentials
- Attach your **OpenAI API** credentials

### 3. Activate Workflow
- Enable the workflow
- Send a message to your Telegram bot

---

## 🧠 System Prompt (Personality)

The AI agent is instructed to:

- Stay fully in character as Spider-Man
- Never acknowledge being an AI
- Use witty humor and friendly sarcasm
- Act as if actively protecting the city

You can modify the system prompt inside the **AI Agent node**.

---

## 🧪 Example Use Cases

- Fun roleplay Telegram bot
- Character-based chat agents
- AI personality experiments
- Learning n8n + LangChain workflows

---

## 🛡️ Safety Notes

- This project is for entertainment and learning
- Do not deploy for sensitive or critical use cases
- Monitor usage to avoid excessive API costs

---

## 📄 License

MIT License — free to use, modify, and share.

---

## ⭐ Credits

Built with:
- n8n
- Telegram Bot API
- OpenAI
- LangChain

---

## 🕸️ With great power comes great automation.
