# GenAIHub
GenAIHub is an AI-powered content generation platform that helps creators, developers, and businesses automate their workflows. It supports generating blog content, YouTube SEO (titles, descriptions, tags), Instagram captions, text improvements, and even code snippets — all in one place.

## 🚀 Features
* ✍️ **Content Generation** – Generate blogs, captions, and marketing content.
* 🎥 **YouTube SEO Tools** – Titles, descriptions, tags optimized for visibility.
* 📊 **Productivity Boost** – AI-powered text improvements and rewriting.
* 💻 **Code Generation** – Get clean, optimized code in multiple languages.
* 🕒 **History Tracking** – Save and revisit previous generations.
* 🔐 **Authentication** – Secure login with [Clerk](https://clerk.dev/).

## 🛠️ Tech Stack
* **Frontend:** React, Next.js, Tailwind CSS
* **Backend:** Next.js API Routes
* **AI API:** Google Gemini API
* **Auth:** Clerk Authentication
* **Database:** PostgreSQL
* **Hosting:** Vercel

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/<your-username>/genaihub.git
cd genaihub
```

Install dependencies:

```bash
npm install
# or
yarn install
```

Set up environment variables in `.env.local`:

```env
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key
GEMINI_API_KEY=your_gemini_api_key
```

Run the development server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

## 📖 Usage

1. Sign up or log in with Clerk authentication.
2. Select a content type (Blog, YouTube, Code, Captions, etc.).
3. Provide your input/prompt.
4. Generate AI-powered results instantly.
5. Save or copy results for future use.

✨ **GenAIHub – AI tools for creators, developers, and businesses.**

Do you want me to **create and push the README.md file directly to your GitHub repo** (I can give you the `git` commands), or just give you the file content so you can add it manually?
