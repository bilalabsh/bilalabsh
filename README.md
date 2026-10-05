# Hi, I'm Bilal 👋

Software engineer in Karachi working on **backend systems and AI**. I build .NET, Go and Python services, and the LLM agents that run on top of them.

- 🛠️ Software Engineer at **Folio3**: an integration platform (iPaaS) on .NET 8, and an AI assistant for it
- 🏆 CBOT Champion 2026 at Folio3, voted by colleagues across the company
- 🎓 BS Computer Science, FAST NUCES Karachi (2025)

---

## What I've built

### 📚 WalkerBook – AI book-publishing platform (live)
Turns a chat conversation into a full-length, formatted book, exported as PDF and DOCX.

- **AI service:** Python, FastAPI and a LangGraph multi-agent pipeline (supervisor, intake, outline, preview and chapter agents), with running chapter summaries so long books stay consistent, chapter-quality evaluation and LangSmith tracing
- **Frontend:** Next.js and TypeScript
- **Backend:** Go, PostgreSQL (22 migrations) and a job worker that runs 30-minute generations with progress tracking and retries

👉 [ai-publishing-engine](https://github.com/bilalabsh/ai-publishing-engine/tree/prod) · [ai-publishing-backend](https://github.com/walkerbooks/ai-publishing-backend/tree/prod)

### 🤖 Agentic Burq – AI assistant for an integration platform (Folio3, private)
Lets users build, edit, run and diagnose e-commerce ↔ ERP integrations in plain English.

- Multi-agent setup: a supervisor routing to specialist agents for lookups, building integrations and self-healing diagnostics
- MCP server with about 57 platform tools, OAuth scopes, per-tool permissions, audit logging and rate limits
- Every change is shown as a plan the user approves, and the model can never apply a change on its own
- A small classifier answers simple requests without the main model (about 0.5 s and $0.00007 per check)
- Built with Python, FastAPI, Claude Agent SDK, .NET 8 and Langfuse

*The code is company-owned, so it isn't public. Happy to walk through the design.*

### More projects

| Project | What it does | Stack |
|---|---|---|
| [Study-Snap](https://github.com/bilalabsh/Study-Snap) | Chat with your PDFs: a RAG study assistant with memory | Python, LangChain, Chroma, OpenAI |
| [Answer Sheet Validation](https://github.com/bilalabsh/Answer_Sheet_Validation) | Reads handwritten answer sheets and grades them against a marking scheme | Python, Llama 3.2 Vision (Groq), OpenCV |
| [Coding Questions Generator](https://github.com/bilalabsh/Coding_Questions_Generator) | Generates coding tests for a topic and difficulty level | Python, LangChain, OpenAI |
| [iParhai Recommendation Service](https://github.com/bilalabsh/Iparhai_RS) | Recommends weak topics and questions for students in an adaptive learning app (final year project) | FastAPI, MongoDB (Motor), scikit-learn |
| [Employee Management](https://github.com/bilalabsh/Employee-Management) | Layered ASP.NET Core app with JWT auth and Identity | C#, ASP.NET Core, EF Core, SQL Server |

---

## Tech I use

- **Languages:** C#, Python, Go, TypeScript, JavaScript, SQL, Swift
- **Backend:** .NET 8 / ASP.NET Core, FastAPI, Node.js, Go (Chi), REST APIs, SignalR
- **AI:** LangGraph, LangChain, Claude Agent SDK, MCP, OpenAI, Groq, Langfuse, LangSmith, RAG
- **Data & cloud:** PostgreSQL, SQL Server, MongoDB, Azure, Docker
- **Frontend & mobile:** Next.js, React, React Native, SwiftUI

---

## Get in touch

📧 memonbilal162@gmail.com · 💼 [linkedin.com/in/bilalabdul](https://www.linkedin.com/in/bilalabdul/)
