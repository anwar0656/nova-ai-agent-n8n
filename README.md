# 🤖 Nova — AI Chat Agent Built with n8n

Nova is a **context-aware AI assistant** built entirely using **n8n**, a no-code automation platform.  
She uses **Groq’s LLaMA 3.3 model** for reasoning and a **PostgreSQL database** to store conversational memory — meaning she can *remember context across chats* like a real assistant.

---

## ⚡ How It Works

1. 💬 You send a message to Nova.  
2. 🤖 The message is processed using the **Groq API (LLaMA 3.3 model)**.  
3. 🧠 Chat memory is stored and retrieved from **PostgreSQL**.  
4. ⚡ Nova generates a smart, context-aware reply instantly.

---

## 🧩 Tech Stack

| Tool | Purpose |
|------|----------|
| **n8n** | No-code automation platform |
| **Groq API (LLaMA 3.3)** | AI text generation |
| **PostgreSQL** | Memory & context storage |
| **AI Agent Node** | Handles reasoning & response logic |

---

## 🧰 Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/anwar0656/nova-ai-agent-n8n.git
cd nova-ai-agent-n8n
```

### 2. Import Workflow into n8n
- Open n8n
- Click **Import from File**
- Select `nova-ai-agent.json`

### 3. Configure Environment Variables
Create a `.env` file based on `.env.example` and fill in your actual API keys and database details.

### 4. Run n8n
You can run n8n locally using Docker or npm:
```bash
n8n start
```

---


## 💡 Features

- Contextual conversation memory with PostgreSQL  
- Real-time AI responses powered by Groq’s LLaMA 3.3  
- 100% visual automation (no coding!)  
- Modular and easily extendable — add your own logic or APIs  

---

## 🛠 Future Improvements

- Add user authentication  
- Integrate voice input/output  
- Deploy as a Telegram/Slack chatbot  

---

## 📜 License

MIT License © 2025 Muhammad Anwar Baloch

---

## 🌐 Connect

Follow my [LinkedIn post](https://www.linkedin.com/posts/muhammad-anwar-62100b325_ai-nocode-automation-ugcPost-7385568696062214144-rHOc) for the story behind Nova 🚀
