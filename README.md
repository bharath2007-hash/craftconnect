# CraftConnect — Project Scaffold

This is the empty folder/file structure for the AI-driven marketplace app, ready to open in VS Code as-is.

## Contents

- `craftconnect-app/` — React Native (Expo) mobile app
- `craftconnect-backend/` — Node.js/Express backend + Python AI microservices

## How to use

1. Unzip this and open the `craftconnect-project` folder in VS Code (`File > Open Folder`).
2. `cd craftconnect-app && npm install` once you're ready to start filling in the React Native app
   (you'll need to run `npx create-expo-app` separately or copy its generated config files into
   `app.json` / `package.json` / `babel.config.js`, since those are currently empty placeholders).
3. `cd craftconnect-backend && npm install` similarly, initializing with `npm init` / your framework
   of choice (Express or NestJS) to populate `package.json`.
4. For the Python AI microservices under `craftconnect-backend/src/ai-microservices/python/`,
   each subfolder has an empty `requirements.txt` and `main.py` — set up a virtualenv per service.

All files are currently empty placeholders that mirror the folder structure from the technical guide —
this gives you the exact skeleton to fill in without having to create folders/files by hand.
