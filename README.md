# 🤖 AI Assistant — Powered by Chainlit + OpenAI Agents + Gemini API

Welcome to **AI Assistant**, a smart conversational agent built using [Chainlit](https://www.chainlit.io/), OpenAI Agents SDK, and Google's Gemini API (flash model).  
This assistant is designed to handle user interactions in a dynamic chat interface powered by modern LLM architecture.

---

## 🚀 Features

- 🌐 Integrated with **Gemini 2.0 Flash** model
- ⚙️ Built on **Chainlit** framework for interactive chat UIs
- 🧠 Uses **OpenAI Agents SDK** for dynamic agent orchestration
- 🔐 Secure `.env`-based API key loading
- 💬 Session-based message history
- 🔄 Stateless yet memory-efficient chat handling

---

## 🧰 Tech Stack

| Technology | Usage |
|------------|-------|
| [Chainlit](https://www.chainlit.io/) | Frontend chat UI |
| OpenAI Agents SDK | Agent + Runner logic |
| Google Gemini API | LLM Model (via `gemini-2.0-flash`) |
| Python `dotenv` | Environment variable loading |
| `asyncio` / async handlers | Non-blocking I/O |
| Hosted on Railway | Free cloud deployment 💸 |

---

## 🛠️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/NehaFahim/AI-Assistant.git
cd AI-Assistant
