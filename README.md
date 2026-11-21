# Compi

Monorepo for the Compi chat app.

| Folder | What it is |
| --- | --- |
| `backend/` | Python microservices (auth, chat, gateway, AI) with Docker Compose. See `backend/README.md`. |
| `frontend/` | React + Vite + Tailwind chat UI. See `frontend/README.md`. |

CI lives in `.github/workflows/` and builds the backend images on pushes to `main` that touch `backend/`.
