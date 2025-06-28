# Jarvis: Personalized Learning Platform

## Overview
Jarvis is an AI-powered platform that transforms PDF notes into interactive learning experiences. Upload notes, get summaries, or ask questions, all through a sleek, accessible UI.

## Features
- **PDF Upload**: Upload lecture notes or study materials in PDF format.
- **AI Summarization/Q&A**: Generate concise summaries or ask questions about the content using Groq’s AI.
- **Responsive UI**: Clean, mobile-friendly interface with dark/light mode toggle.
- **Chat History** (Optional): Save interactions for future reference (using Firebase or mock DB).
- **Live Deployment**: Hosted on Vercel.

## Tech Stack
- **Frontend**: Next.js, Tailwind CSS
- **Backend**: Next.js API routes, Groq API
- **Storage** (Optional): Firebase Firestore
- **Deployment**: Vercel
- **Libraries**: `pdfjs-dist` (PDF parsing), `next-themes` (dark/light mode)

## Setup Instructions
1. Clone the repository: `git clone <repo-url>`
2. Install dependencies: `npm install`
3. Set environment variables in `.env.local`:
   - `GROQ_API_KEY`: Your Groq API key
   - (Optional) `FIREBASE_CONFIG`: Firebase credentials
4. Run locally: `npm run dev`
5. Deploy to Vercel: Follow Vercel’s CLI or GitHub integration.

## Usage
1. Visit the live app: `<vercel-url>`
2. Upload a PDF file (e.g., lecture notes).
3. Choose to summarize the content or ask a question.
4. View results in the UI and toggle dark/light mode for accessibility.

## Future Enhancements
- Support for images (OCR) and videos (transcription).
- User authentication with Clerk.
- Quiz and flashcard generation.
