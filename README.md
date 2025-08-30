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
- Backend: Render / ### 🚀 Deploy Backend on Render

[![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://render.com/deploy)

> After clicking, connect your GitHub repo → select the `backend` folder →  
> Build Command: `npm install`  
> Start Command: `node server.js`  
> Add Environment Variables (from `.env.example`):
Railway (point to `backend/`)
- Frontend: Vercel (point to `frontend/`)

Default admin credentials (after running `init-admin` or via seed):
- Email: Aryanvats2003@gmail.com
- Password: admin123

