Mind Mend App

A modern mental wellness companion built using React, TypeScript, Vite, Tailwind, shadcn-ui, Supabase, and AI-powered mood analysis.

🚀 Features

Mood tracking

Journaling system

AI-generated suggestions (Gemini-based)

Supabase Authentication

Supabase Database + Edge Functions

Clean UI with Tailwind + shadcn-ui

Fully responsive

🛠 Tech Stack

Frontend: React, TypeScript, Vite

Styling: Tailwind CSS, shadcn-ui

Backend: Supabase (Auth, Postgres, Edge Functions)

AI: Gemini API (custom Edge functions)

📦 Installation & Setup
1️⃣ Clone the repository
git clone https://github.com/Harsha-v-r/Mind-Mend-App.git

2️⃣ Navigate into the project folder
cd Mind-Mend-App

3️⃣ Install dependencies
npm install

4️⃣ Start development server
npm run dev

🔑 Environment Variables

Create a file named .env.local in the project root:

VITE_SUPABASE_URL=""
VITE_SUPABASE_PUBLISHABLE_KEY=""
SUPABASE_SERVICE_ROLE_KEY=""
GEMINI_API_KEY=""


⚠️ Do NOT commit .env.local to GitHub.

🌐 Deployment (Vercel)

Go to https://vercel.com

Import this repository

Add all environment variables from .env.local

Build command:

npm run build


Output directory:

dist


Deploy 🚀

📁 Project Structure
Mind-Mend-App/
│
├── src/
│   ├── components/
│   ├── pages/
│   ├── hooks/
│   ├── lib/
│   └── styles/
│
├── supabase/
│   ├── migrations/
│   └── functions/
│
├── public/
├── package.json
└── README.md

🧑‍💻 Contributing

Fork the repo

Create a new branch:

git checkout -b my-feature


Commit changes:

git commit -m "Add new feature"


Push:

git push origin my-feature


Create a Pull Request

📜 License

This project is maintained and owned by Harsha-v-r.
Feel free to fork or contribute if allowed.
