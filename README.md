<div align="center">

# RdyIntervu

### AI-Powered Mock Interview Platform

Practice technical and behavioral interviews with AI voice agents and receive real-time feedback analysis.

<br/>

<img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" />
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
<img src="https://img.shields.io/badge/TailwindCSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" />
<img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" />
<img src="https://img.shields.io/badge/Vapi_AI-111827?style=for-the-badge" />

</div>

---

## Features

- AI-generated mock interviews
- Real-time voice interaction
- Technical and behavioral interview modes
- AI-powered feedback and scoring
- Interview transcript analysis
- Authentication system with Firebase
- Personalized interview dashboard
- Fully responsive modern UI

---

## Tech Stack

- Next.js
- TypeScript
- Tailwind CSS
- Firebase
- Vapi AI
- Google Gemini
- shadcn/ui
- Zod

---

## Environment Variables

Create a `.env.local` file in the root directory:

```env
NEXT_PUBLIC_VAPI_WEB_TOKEN=

NEXT_PUBLIC_VAPI_WORKFLOW_ID=

GOOGLE_GENERATIVE_AI_API_KEY=

NEXT_PUBLIC_BASE_URL=

NEXT_PUBLIC_FIREBASE_API_KEY=

NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=

NEXT_PUBLIC_FIREBASE_PROJECT_ID=

NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=

NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=

NEXT_PUBLIC_FIREBASE_APP_ID=

FIREBASE_PROJECT_ID=

FIREBASE_CLIENT_EMAIL=

FIREBASE_PRIVATE_KEY=
```

---

## Getting Started

### Clone the Repository

```bash
git clone <your-repository-url>
```

### Install Dependencies

```bash
npm install
```

### Start Development Server

```bash
npm run dev
```

Visit:

```bash
http://localhost:3000
```

---

## Project Structure

```bash
app/            # Next.js routes
components/     # Reusable UI components
firebase/       # Firebase configuration
lib/             # Utility functions
prisma/         # Database schema
public/         # Static assets
```

---

## Core Modules

### AI Interview Generation

Dynamic interview generation based on:

- Role
- Experience level
- Tech stack
- Interview type

### AI Feedback System

Performance analysis including:

- Communication
- Technical knowledge
- Problem-solving
- Confidence
- Overall assessment

---

## Author

### Rohan Yadav

B.Tech CSE • Gautam Buddha University

---

## License

This project is intended for educational and development purposes.
