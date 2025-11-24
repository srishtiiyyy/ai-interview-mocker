Interview Mocker – AI Mock Interview Platform

Interview Mocker is an AI-powered mock interview web application built using Next.js, Clerk Authentication, TailwindCSS, Shadcn UI, and OpenAI/Anthropic.
It allows users to simulate real interview environments, answer questions, get instant AI feedback, and track their progress.

🚀 Features

🔐 Secure authentication with Clerk

🤖 AI-generated interview questions based on role & experience

🧠 Instant feedback and evaluation

🎤 Optional voice-based questions/answers

📊 Dashboard to view previous interviews

🎨 Modern UI using Tailwind + Shadcn

⚡ Blazing fast performance (Next.js App Router)

🛠️ Tech Stack
Component	Tech
Frontend	Next.js 14+, React
Styling	TailwindCSS, Shadcn UI
Auth	Clerk
AI Models	OpenAI / Anthropic
Database	Prisma / Supabase / MongoDB (your choice)
Deployment	Vercel
📁 Project Structure
interview-mocker/
│
├── app/
│   ├── (auth)/
│   │   ├── sign-in/
│   │   ├── sign-up/
│   ├── dashboard/
│   ├── interview/
│   ├── api/
│   │   └── generate/
│   │       └── route.js
│   └── layout.js
│
├── components/
│   ├── ui/
│   ├── navbar.jsx
│   └── interview-card.jsx
│
├── lib/
│   ├── openai.js
│   ├── auth.js
│   └── utils.js
│
├── styles/
│   └── globals.css
│
├── public/
├── middleware.js
├── tailwind.config.js
├── package.json
└── README.md

⚙️ Environment Variables

Create a .env.local file:

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key

OPENAI_API_KEY=your_openai_api_key    # if using OpenAI
ANTHROPIC_API_KEY=your_anthropic_key  # if using Claude

DATABASE_URL=your_database_url (optional)
