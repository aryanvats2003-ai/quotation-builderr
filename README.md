# Quotation Builder (EaseMyTrip)

This repository contains a full-stack Quotation Builder (backend + frontend) ready to upload to GitHub.

## Quick start (Docker)
1. Clone or extract this repo.
2. Copy `.env.example` files if you need to change defaults.
3. From repo root:
   ```
   docker compose up --build
   ```
4. Frontend: http://localhost:3000
   Backend API: http://localhost:5000

## Deploy
- Backend: Render / Railway (point to `backend/`)
- Frontend: Vercel (point to `frontend/`)

Default admin credentials (after running `init-admin` or via seed):
- Email: admin@easemytrip.com
- Password: admin123

