# AkiraFlora.Ai

A modern AI assistant website with a student-first experience.

## Features
- ChatGPT/Gemini-style responsive interface
- Persistent local chat history in the browser
- New chat and recent chats
- Student shortcuts for explanations, quizzes, notes and study plans
- Image/PDF/text file attachment support
- Optional web-search mode through the OpenAI Responses API
- Browser voice input and read-aloud
- Dark/light theme
- Server-side OpenAI API key

## Run locally
1. Install Node.js 20+.
2. Run `npm install`.
3. Set `OPENAI_API_KEY` in your environment.
4. Run `npm start`.
5. Open `http://localhost:3000`.

## Deploy
Use a Node.js web-service host. Set the build/install command to `npm install`, start command to `npm start`, and add `OPENAI_API_KEY` as a secret/environment variable. Never put the API key in `public/` or in browser JavaScript.
