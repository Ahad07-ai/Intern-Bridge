Pulse Haven

Pulse Haven is a modern full-stack web application designed to provide a seamless experience for students, mentors, and recruiters. It integrates role-based dashboards, authentication, notifications, and placement opportunities within a responsive and scalable platform.

🚀 Features

Frontend: React + TypeScript + Vite

UI: TailwindCSS + shadcn/ui components

Backend: Node.js + Express-like routes (server + Netlify functions)

Authentication: Login & Signup flows

Role-specific dashboards: Student, Mentor, Recruiter, Placement

Calendar & Notifications Center

Reusable UI components for consistent design

📂 Project Structure
pulse-haven/
├── client/          # Frontend (React + TS + Tailwind)
│   ├── components/  # UI components
│   ├── pages/       # App pages (auth, dashboard, etc.)
│   ├── hooks/       # Custom React hooks
│   ├── lib/         # Utilities
├── server/          # Backend (Node.js + routes)
│   ├── routes/      # API route handlers
├── netlify/         # Serverless functions
├── public/          # Static assets
├── shared/          # Shared utilities (frontend & backend)
├── package.json     # Dependencies
├── tailwind.config.ts  
├── tsconfig.json  
└── vite.config.ts  

⚙️ Installation & Setup

Clone the repository:

git clone <repo-url>
cd pulse-haven


Install dependencies:

pnpm install


Create a .env file at the root with required environment variables:

VITE_API_URL=your_api_url


Start the development server:

pnpm dev


Build for production:

pnpm build


Deploy using Netlify or your preferred cloud platform.

📌 Available Scripts

pnpm dev – Start frontend in development mode

pnpm build – Build for production

pnpm preview – Preview production build

pnpm lint – Run lint checks

🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss your ideas.

📜 License

This project is licensed under the MIT License.
