# 🤖 AI Agent

A toy version of an **AI Agent** inspired by Claude Code, built as part of the Boot.dev course.  
This project demonstrates how to build a simple agentic workflow in Python, integrating with the **Gemini API**.

---

## 🚀 Features
- Accepts coding tasks as input (natural language).
- Chooses from a set of predefined functions to attempt solving the task.
- Uses the **Gemini API** for reasoning and assistance.
- Runs in a clean **CLI environment**.

---

## 🛠️ Tech Stack
- **Python 3.12+**
- **[uv](https://github.com/astral-sh/uv)** for project & dependency management
- **python-dotenv** for environment variables
- **Google Gemini API**

---

## 📂 Project Structure
```
ai-agent/
└── aigent/
    ├── main.py           # Entry point
    ├── .env              # API keys & secrets (not committed)
    ├── .venv/            # Virtual environment
    ├── pyproject.toml    # Project dependencies
    ├── uv.lock           # Lock file
    └── README.md         # Project description
```

---

## ⚙️ Setup & Installation

1. **Clone the repo**
   ```bash
   git clone https://github.com/sahilpatel318/AI_Agent.git
   cd AI_Agent/aigent
   ```

2. **Create & activate virtual environment**
   ```bash
   uv venv
   source .venv/bin/activate
   ```

3. **Install dependencies**
   ```bash
   uv add python-dotenv google-genai
   ```

4. **Set up environment variables**  
   Create a `.env` file in the root with:
   ```env
   GEMINI_API_KEY=your_api_key_here
   ```

5. **Run the agent**
   ```bash
   python main.py
   ```

---

## 📜 License
This project is for **educational purposes only** as part of the Boot.dev course.  
Feel free to fork and experiment!

