# OpenChat

## Stack

* **Frontend:** Node 24, Next.js 16, React 19, TypeScript 7, Tailwind CSS 4, shadcn/ui — `frontend/` :3000
* **Backend:** FastAPI, Python 3.13, uv, Ruff, Pytest — `backend/` :8000
* **Local AI:** Ollama — `localhost:11434`, `gemma3:1b`
* **Cloud AI:** OpenAI, Anthropic, Gemini, Grok, Meta — fallback providers

## Commands

```bash
# Frontend
cd frontend
npm install
npm run dev
npm install <package-name>

# Backend
cd backend
uv sync
uv run fastapi dev
uv add <package-name>

# Tests
cd backend
pytest
```

## Rules

* Never commit `.env`, secrets, or API keys.
* Run tests after every change.
* Keep changes minimal and focused.
* Follow existing project patterns and conventions.
* Prefer type-safe, clean, maintainable code.
* Update tests when behavior changes.
* Do not introduce dependencies without a clear need.
