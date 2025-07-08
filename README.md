# 🔴 Reddex — AI-Powered Social Platform
[![Next.js](https://img.shields.io/badge/Next.js-15-black?style=flat-square&logo=next.js)](https://nextjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0+-blue?style=flat-square&logo=typescript)](https://www.typescriptlang.org/)
[![Sanity CMS](https://img.shields.io/badge/CMS-Sanity.io-ff4747?style=flat-square&logo=sanity)](https://www.sanity.io/)
[![OpenAI](https://img.shields.io/badge/AI-OpenAI-00a67f?style=flat-square&logo=openai)](https://openai.com/)
[![Clerk](https://img.shields.io/badge/Auth-Clerk-24292f?style=flat-square&logo=clerk&logoColor=white)](https://clerk.com/)
[![TailwindCSS](https://img.shields.io/badge/Styling-TailwindCSS-38bdf8?style=flat-square&logo=tailwindcss)](https://tailwindcss.com/)
[![Vercel](https://img.shields.io/badge/Deployed%20on-Vercel-black?style=flat-square&logo=vercel)](https://vercel.com/)

Reddex is a full-stack, modern social platform built with Next.js 15, Sanity CMS, and OpenAI-powered moderation tools. It empowers users to create, manage, and engage in communities — all with blazing-fast performance and intelligent, automated content moderation.

## 🚀 Features

### ⚙️ Full-Stack Architecture
- Next.js 15 with App Router, Server Components & Server Actions
- TypeScript for type safety
- Turbopack for lightning-fast builds

### 🧠 AI-Powered Moderation
- Vercel AI SDK + OpenAI integration
- Context-aware moderation decisions
- Inappropriate content detection & censorship
- Tool-calling enabled reporting system

### 📝 Content Management (Sanity CMS)
- Real-time post, comment, and community updates
- Custom content schemas and rich text editor
- Media uploads and optimization

### 🔐 Authentication
- Secure auth with Clerk
- Protected routes and content

### 🧑‍🤝‍🧑 Community & Engagement
- Subreddit-style community creation
- Voting system for posts and comments
- Nested comment threading
- User profiles with activity history

### 💡 UI/UX
- Responsive Tailwind CSS design
- Beautiful components with Radix UI
- Skeleton loaders, transitions & intuitive UX
- Time-ago timestamps and smart search

## 📸 Preview

<img width="1440" alt="Screenshot 2025-06-26 at 3 35 14 AM" src="https://github.com/user-attachments/assets/e1fb1b88-6fbf-46f2-bc6b-340be098c6b7" />


## 🛠️ Tech Stack

| Layer        | Tech                           |
|--------------|--------------------------------|
| Frontend     | Next.js 15, Tailwind CSS, Radix UI |
| Backend/API  | Next.js Server Actions         |
| Auth         | Clerk                          |
| CMS          | Sanity.io                      |
| AI/LLMs      | Vercel AI SDK, OpenAI API      |
| Hosting      | Vercel                         |

## 📦 Installation

### 1. Clone the repo

```bash
git clone https://github.com/siddhantchasta/reddex.git
cd reddex
```

### 2. Install dependencies

```bash
npm install
# or
yarn install
```

### 3. Configure Environment Variables

Create a `.env.local` file in the root directory:

```env
# 👉 Clerk (Authentication)
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key

# 👉 Sanity CMS
NEXT_PUBLIC_SANITY_PROJECT_ID=your_sanity_project_id
NEXT_PUBLIC_SANITY_DATASET=production
SANITY_API_ADMIN_TOKEN=your_sanity_admin_token

# 👉 OpenAI (for AI-powered moderation)
OPENAI_API_KEY=your_openai_api_key

# 👉 Base URL
NEXT_PUBLIC_BASE_URL=http://localhost:3000
```

### 4. Run the development server

```bash
npm run dev
# or
yarn dev
```

App will be live at `http://localhost:3000`

## 🚀 Deployment

Reddex is optimized for Vercel deployment.

1. Push your code to GitHub  
2. Go to [vercel.com](https://vercel.com/)  
3. Import your repository  
4. Add your environment variables in the Vercel dashboard  
5. Click **Deploy**

## 📄 License

MIT License. See [`LICENSE`](./LICENSE) for more info.

## 📬 Contact

Made with ❤️ by [@siddhantchasta](https://github.com/siddhantchasta)
