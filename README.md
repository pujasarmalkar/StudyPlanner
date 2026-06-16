# Study Planner AI (Python)

AI-powered study schedule chatbot built with FastAPI + Groq (Llama 3.3).

## Project Structure

```
study-planner-python/
├── static/
│   └── index.html       ← Frontend chatbot UI
├── main.py              ← FastAPI backend
├── requirements.txt     ← Python dependencies
├── .env.example         ← Environment variable template
├── .gitignore
└── README.md
```

## Getting Started

### Prerequisites
- Python 3.10 or higher


### Installation

```bash
# 1. Clone the repo
git clone https://github.com/YOUR_USERNAME/study-planner-ai.git
cd study-planner-ai

# 2. Create and activate a virtual environment
python -m venv venv
source venv/bin/activate        # Mac/Linux
venv\Scripts\activate           # Windows

# 3. Install dependencies
pip install -r requirements.txt

# 5. Run the server
uvicorn main:app --reload
```

Open [http://localhost:8000](http://localhost:8000) in your browser.

## License

MIT

