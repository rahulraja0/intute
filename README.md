# 📚 Intute – Personal AI Tutor & Study Assistant

> An AI-powered educational platform that provides personalized tutoring, interactive learning, and intelligent study assistance.

---

# 📖 Overview

Intute is an AI-powered educational assistant that helps students understand concepts through conversational AI. The application delivers real-time responses, interactive learning, and an intuitive interface for exploring topics across different domains.

The system is built using a modern React-based frontend integrated with Google Gemini AI. Additionally, the project includes Python utility modules for prompt handling, project analysis, diagnostics, and future backend extensibility.

---

# ✨ Features

- 🤖 AI-powered tutoring
- 💬 Real-time conversational interface
- 📖 Personalized learning assistance
- 📝 Markdown support
- 📐 LaTeX equation rendering
- 📊 Interactive charts
- ⚡ Fast and responsive UI
- 🧠 Gemini AI integration
- 🔧 Python utility modules
- 📄 PDF Export Support

---

# 🛠 Tech Stack

## Frontend

- React
- TypeScript
- Vite
- Tailwind CSS

## AI Integration

- Google Gemini API

## Python Utilities

- Python 3.x
- Prompt Processing
- Project Analysis
- Diagnostics
- Utility Scripts

## State Management

- React Context API
- Zustand

## Additional Libraries

- Recharts
- jsPDF
- html2pdf.js

---

# 🏗 Architecture Diagram

```text
                     +---------------------------+
                     |          User             |
                     +-------------+-------------+
                                   |
                                   |
                         User Interaction
                                   |
                                   ▼
                  +-------------------------------+
                  |      React + TypeScript UI    |
                  |                               |
                  | Components                    |
                  | Context API                   |
                  | Vite                          |
                  +---------------+---------------+
                                  |
                                  |
                        API Request / Prompt
                                  |
                                  ▼
                  +-------------------------------+
                  |      Google Gemini AI         |
                  |                               |
                  | Response Generation           |
                  | Natural Language Processing   |
                  +---------------+---------------+
                                  |
                                  |
                       AI Generated Response
                                  |
                                  ▼
                  +-------------------------------+
                  |      React Application        |
                  |                               |
                  | Chat Interface                |
                  | Study Assistance              |
                  | Dynamic Content               |
                  +---------------+---------------+
                                  |
                                  |
                        Utility Operations
                                  |
                                  ▼
                  +-------------------------------+
                  |      Python Utilities         |
                  |-------------------------------|
                  | analyzer.py                   |
                  | ai_agent.py                   |
                  | inference.py                  |
                  | vector_search.py              |
                  | prompt_engine.py              |
                  | debug.py                      |
                  | constants.py                  |
                  | runmodel.py                   |
                  +-------------------------------+
```

---

# 📂 Project Structure

```
intute/

├── components/
│   ├── console/
│   ├── demo/
│   ├── python/
│   │   ├── analyzer.py
│   │   ├── ai_agent.py
│   │   ├── constants.py
│   │   ├── debug.py
│   │   ├── inference.py
│   │   ├── prompt_engine.py
│   │   ├── runmodel.py
│   │   └── vector_search.py
│   ├── AgentEdit.tsx
│   ├── Header.tsx
│   ├── WelcomeScreen.tsx
│   └── UserSettings.tsx
│
├── contexts/
│
├── hooks/
│
├── lib/
│
├── App.tsx
├── index.tsx
├── package.json
├── vite.config.ts
├── README.md
└── .env
```

---

# ⚙ Installation

Clone the repository

```bash
git clone <repository-url>
```

Navigate to the project

```bash
cd intute
```

Install dependencies

```bash
npm install
```

Configure Environment Variables

```env
GEMINI_API_KEY=YOUR_API_KEY
```

Run the application

```bash
npm run dev
```

The application will start on

```
http://localhost:5173
```

---

# 🔄 Workflow

1. User opens Intute.
2. React renders the interface.
3. User enters a prompt.
4. The request is processed by Gemini AI.
5. AI generates an intelligent response.
6. The interface updates dynamically.
7. Python utility modules can assist with prompt handling, diagnostics, and future enhancements.

---

# 🚀 Future Scope

- Voice interaction
- AI-generated diagrams
- Personalized study plans
- Session history
- Multi-language support
- Cloud deployment
- FastAPI backend integration
- User authentication

---

# 👨‍💻 Author

**Rahul R**

AI Developer | React | TypeScript | Python

---

# 📜 License

This project is licensed under the MIT License.
