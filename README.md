# 🌉 Intern Bridge  

Intern Bridge is a **modern full-stack web application** designed to provide a seamless experience for **students, mentors, and recruiters**.  
It integrates role-based dashboards, authentication, notifications, and placement opportunities within a **responsive and scalable platform**.  

---

## 🚀 Features  

✨ **Frontend:** React + TypeScript + Vite  
🎨 **UI:** TailwindCSS + shadcn/ui components  
⚡ **Backend:** Node.js + Express-like routes (server + Netlify functions)  
🔐 **Authentication:** Login & Signup flows  
👥 **Role-specific dashboards:** Student, Mentor, Recruiter, Placement  
📅 **Calendar & Notifications Center**  
♻️ **Reusable UI components** for consistent design  

---

## 📂 Project Structure  

intern-bridge/
├── client/ # Frontend (React + TS + Tailwind)
│ ├── components/ # UI components
│ ├── pages/ # App pages (auth, dashboard, etc.)
│ ├── hooks/ # Custom React hooks
│ ├── lib/ # Utilities
├── server/ # Backend (Node.js + routes)
│ ├── routes/ # API route handlers
├── netlify/ # Serverless functions
├── public/ # Static assets
├── shared/ # Shared utilities (frontend & backend)
├── package.json # Dependencies
├── tailwind.config.ts
├── tsconfig.json
└── vite.config.ts

yaml
Copy code

---

## ⚙️ Installation & Setup  

1️⃣ **Clone the repository:**  
```bash
git clone <repo-url>
cd intern-bridge
2️⃣ Install dependencies:

bash
Copy code
pnpm install
3️⃣ Create a .env file at the root with required environment variables:

env
Copy code
VITE_API_URL=your_api_url
4️⃣ Start the development server:

bash
Copy code
pnpm dev
5️⃣ Build for production:

bash
Copy code
pnpm build
6️⃣ Deploy using Netlify or your preferred cloud platform.

📌 Available Scripts
▶️ pnpm dev – Start frontend in development mode

🏗️ pnpm build – Build for production

👀 pnpm preview – Preview production build

🧹 pnpm lint – Run lint checks

🤝 Contributing
Contributions are welcome! 🎉

Fork the repo

Create a new branch

Make your changes

Submit a pull request

For major changes, please open an issue first to discuss your ideas.

📜 License
📄 This project is licensed under the MIT License.

🙌 Acknowledgements
Made with ❤️ by the Intern Bridge Team.
