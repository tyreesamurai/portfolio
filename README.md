# 💬 Language Learning Chatbot

## 📌 Overview
An AI-powered chatbot designed to help users improve their foreign language writing skills. The app allows users to submit diary entries in their target language and receive grammar corrections, vocabulary suggestions, and stylistic feedback in real-time. It leverages LLMs for natural language processing and thoughtful correction.

## 🧪 Tech Stack
- **Backend:** Python, FastAPI, LangChain, OpenAI/GPT
- **Frontend:** React (or Expo if mobile-focused)
- **Infrastructure:** Docker, GitHub Actions
- **Optional Features:** PostgreSQL (logs), Redis (caching), Auth (OAuth)

---

## 🎯 Goals
- ✅ Analyze and correct diary entries in multiple languages
- 🤖 Leverage LLMs for deep linguistic feedback
- 🔐 Provide optional user accounts and entry history
- 📱 Deliver intuitive UI for typing and viewing feedback
- 🌍 Support language detection and switching

---

## 🧱 Milestones

| Phase         | Description                                      | Status         |
|---------------|--------------------------------------------------|----------------|
| Design        | UI mockups, API plan, prompt structure           | 🟡 In Progress |
| Backend       | LLM pipeline, FastAPI endpoints, logging         | ⚪ Not Started  |
| Frontend      | Text input form, corrections view, theme design  | ⚪ Not Started  |
| Testing       | Prompt testing, input validation, UI feedback    | ⚪ Not Started  |
| Deployment    | API + UI containerization and hosting            | ⚪ Not Started  |

---

## 🎨 Design

### 📄 Prompt Flow (LangChain)
- [ ] Accept diary entry input
- [ ] Detect input language
- [ ] Run correction chain:
  - Grammar & syntax fixes
  - Vocabulary and tone suggestions
  - Explanation for changes
- [ ] Return structured response for UI display

### 🖼️ UI Wireframes
To be added:

- `/assets/design/input-screen.png`
- `/assets/design/correction-output.png`
- `/assets/design/history-log.png`

---

## 🚧 Development Roadmap

### 🧠 Prompt Design
- [x] Define correction prompt templates
- [ ] Test prompt on real-world diary entries
- [ ] Refine output format (JSON)

### 🛠️ Backend
- [ ] Set up FastAPI server
- [ ] Build `/analyze` POST endpoint
- [ ] Integrate LangChain with OpenAI API
- [ ] (Optional) Store logs in PostgreSQL

### 💻 Frontend
- [ ] Create diary entry submission form
- [ ] Display inline corrections with highlights
- [ ] Add entry history view for signed-in users

### 🧪 Testing
- [ ] Prompt unit tests with test inputs
- [ ] Backend response validation
- [ ] Frontend input/output tests

### 🚀 Deployment
- [ ] Dockerize backend and frontend
- [ ] Set up GitHub Actions for linting/tests
- [ ] Deploy to Vercel (frontend) and Fly.io (backend)

---

## 🧠 Inspiration

As a language learner, it’s hard to get timely and detailed writing feedback. This app aims to bridge that gap using AI to give actionable corrections while preserving learning context.

---

## 📬 Contact

Want to test it or help with development?  
Open an issue in this repo or reach out via [GitHub](https://github.com/tyreesamurai).
