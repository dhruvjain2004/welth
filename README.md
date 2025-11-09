# 💸 Full Stack AI Finance Platform

A cutting-edge **AI-powered Finance Management Platform** built using **Next.js, Supabase, Prisma, Inngest, ArcJet, and Shadcn UI**.  
This project integrates modern authentication, real-time data synchronization, AI-based analytics, and automated financial insights — all powered by the **Gemini API**.

---

## 🚀 Tech Stack

| Category | Technologies Used |
|-----------|-------------------|
| **Frontend** | Next.js 14 (App Router), Tailwind CSS, Shadcn UI |
| **Backend** | Prisma ORM, Supabase (PostgreSQL), Inngest (Event-driven backend) |
| **Authentication** | Clerk |
| **Email Service** | Resend API |
| **AI Integration** | Gemini API |
| **Security** | ArcJet |
| **Styling** | TailwindCSS + Shadcn UI Components |

---

## 🧠 Features

✅ AI-driven financial insights & trend analysis  
✅ User authentication via Clerk (Sign In / Sign Up / Onboarding flow)  
✅ Real-time financial data using Supabase  
✅ Secure API routes with ArcJet  
✅ Automated event workflows via Inngest  
✅ AI response generation using Gemini API  
✅ Email notifications with Resend API  
✅ Modern, responsive UI built with Shadcn components  

---

## 📁 Project Structure

```
📦 ai-finance-platform/
├── app/
│   ├── (auth)/           # Sign-in & Sign-up pages (Clerk)
│   ├── dashboard/        # Main finance dashboard (protected)
│   ├── onboarding/       # User onboarding flow
│   ├── api/              # Serverless API routes
│   └── layout.tsx        # Root layout with providers
│
├── components/           # UI components (Shadcn)
├── lib/                  # Utility functions, Prisma, and helpers
├── styles/               # Tailwind and global styles
├── prisma/               # Prisma schema and migrations
├── inngest/              # Event-driven tasks
├── .env.example          # Environment variables template
├── package.json
├── prisma/schema.prisma
└── README.md
```

---

## ⚙️ Environment Variables

Create a `.env` file in the root directory and add the following:

```bash
# Database
DATABASE_URL=
DIRECT_URL=

# Clerk Authentication
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding

# Gemini AI
GEMINI_API_KEY=

# Email Service
RESEND_API_KEY=

# ArcJet (Security)
ARCJET_KEY=
```

---

## 🧩 Setup Instructions

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/ai-finance-platform.git
cd ai-finance-platform
```

### 2️⃣ Install Dependencies

```bash
npm install
```

### 3️⃣ Set Up Database (Supabase + Prisma)

```bash
npx prisma generate
npx prisma db push
```

> Make sure your Supabase PostgreSQL connection string is in `.env`.

### 4️⃣ Run the Development Server

```bash
npm run dev
```

The app will be live at **https://welth-gamma-six.vercel.app/**

---

## 🧠 AI & Automation Setup

- **Gemini API:** Used for generating AI-driven finance summaries and forecasts.  
- **Inngest:** Handles background automation tasks (e.g., data sync, reminders).  
- **Resend API:** Sends transaction or insight emails automatically.  
- **ArcJet:** Provides endpoint security, anti-abuse protection, and access control.

---

## 🧑‍💻 Developer Experience

- Type-safe API integration using Prisma
- Fully modular and reusable Shadcn UI components
- TailwindCSS for rapid, responsive design
- Environment-aware and scalable configuration
- Future-proofed with App Router & Server Actions

---

## 🌐 Deployment

You can deploy this app easily using:

- **Vercel** → for Next.js hosting  
- **Supabase** → for Database + Auth  
- **Render / Railway** → for background tasks (optional)

---

## 📸 Preview

![AI Finance Dashboard Screenshot](https://github.com/user-attachments/assets/1bc50b85-b421-4122-8ba4-ae68b2b61432)

---

## 💡 Inspiration

This project showcases the potential of **Next.js full-stack development** combined with **AI-driven finance**.  
It demonstrates how **AI, event-driven architecture, and modern authentication** can revolutionize fintech apps.

---

## 🧾 License

This project is licensed under the **MIT License**.

---

## 🧑‍🏫 Credits

 
**Built with ❤️ by:** Dhruv Jain ([@DhruvJain](https://github.com/dhruvjain2004))
