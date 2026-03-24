# Deploy guide

## Railway (recommended for full-stack deploy)
1. Push this folder to GitHub.
2. In Railway: New Project -> Deploy from GitHub repo.
3. Railway will detect `railway.toml` / `Dockerfile`.
4. Add any needed variables from `.env.example`.
5. Deploy.

## Vercel
This repository is currently a single Node/Vite/Express app. It is better suited to Railway or another container host.
If you later split the frontend into a standalone Next.js/Vite app, Vercel can deploy the UI while Railway runs the API.
