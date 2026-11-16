# Rotana Star CRM — Protected Release

This repository contains an AES-256 encrypted & licensed build of Rotana Star CRM.
It requires **Node.js 22.13+ or 24 LTS** and valid owner keys (`CRM_MASTER_KEY` + `CRM_LICENSE_TOKEN`).

## Setup & Run
```bash
npm --prefix backend install --omit=dev
cp backend/.env.example backend/.env
# Fill CRM_MASTER_KEY, CRM_LICENSE_TOKEN, and JWT_SECRET inside backend/.env
npm start
```
