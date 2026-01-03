# 🤖 Ghost-AI

**Ghost-AI** is a real-time, production-grade **AI chatbot** built using modern **Generative AI and web technologies**, designed for fast streaming responses, live web search, and persistent multi-session conversations.



---

## 🚀 Features

- ⚡ **Real-time streaming responses** using **Server-Sent Events (SSE)**
- 🌐 **Live web search integration** via **Tavily** for up-to-date information
- 💾 **Persistent conversation management** with SQLite + SQLAlchemy
- 🧠 **Context-aware chat titles** auto-generated using LLM summarization
- 🔄 **Seamless UX** — create, delete, search, and update conversations without page refresh
- 🐳 **Dockerized architecture** for consistent local and production deployments

---

## 🛠 Tech Stack

### Frontend
- **Next.js**
- **React**
- **TypeScript**
- **Tailwind CSS**

### Backend
- **FastAPI**
- **Python**
- **Server-Sent Events (SSE)**

### AI & LLM
- **Gemini**
- **LangChain**
- **LangGraph**
- **Tavily Search Tool**

### Database & Infra
- **SQLite**
- **SQLAlchemy**
- **Docker**

---

## 📌 Key Implementations

### 🔴 Real-Time Streaming (SSE)
- Implemented SSE to stream LLM responses token-by-token
- Improved perceived response time by **40–60%** compared to traditional request/response APIs

### 🌍 Live Web Search
- Integrated **Tavily** to fetch real-time web data
- Enables answers beyond model knowledge cutoff

### 💬 Persistent Conversation Manager
- Conversations stored in **SQLite** using **SQLAlchemy**
- Supports:
  - Create conversations
  - Delete conversations
  - Search conversations
  - Update titles
- Eliminates page refresh and improves session continuity

### 🏷 Auto-Generated Chat Titles
- Uses **LLM summarization** on the first **3 user messages**
- Generates concise, context-aware titles
- Reduced “Untitled” sessions by **~85%**

---

## 🧩 System Architecture

Client (Next.js + React)
|
| SSE Stream
v
Backend (FastAPI)
|
| LLM Orchestration
v
Gemini + LangChain + LangGraph
|
| Live Search
v
Tavily


---


📬 Contact
Aman Agrawal
Final-year B.Tech, IIIT Bhopal
🔗 LinkedIn: https://www.linkedin.com/in/aman-agrawal-269233252
📧 Email: aman.agraw.35@gmail.com

⭐ If you find this project useful, consider giving it a star!


