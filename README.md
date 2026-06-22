<div align="center">

<img src="public/favicon.svg" alt="Logo" width="80" height="80" />

# ✦ Andrea Polazzo — Personal Portfolio

### *Web & App Developer*

**Building useful tools and clean interfaces**

[![Next.js](https://img.shields.io/badge/Next.js-16.1.6-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)](https://nextjs.org/)
[![React](https://img.shields.io/badge/React-19.2.4-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://react.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.3-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.4-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)](https://tailwindcss.com/)
[![Three.js](https://img.shields.io/badge/Three.js-0.170-000000?style=for-the-badge&logo=threedotjs&logoColor=white)](https://threejs.org/)

[![Live Demo](https://img.shields.io/badge/🌐_Live_Demo-Visit_Portfolio-6366f1?style=for-the-badge)](https://andreapolazzo.com)
[![GitHub](https://img.shields.io/badge/GitHub-AndreaPolazzo-181717?style=for-the-badge&logo=github)](https://github.com/AndreaPolazzo)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/andrea-polazzo-235a383a3/)

</div>

---

## Overview

A personal portfolio site built with Next.js, showcasing web and app projects through an interactive 3D experience (physics-based ID card, particle backgrounds), live GitHub/coding stats, and a portfolio-aware AI chatbot assistant.

---

## Tech Stack

```
Next.js 16  ·  React 19  ·  TypeScript  ·  Tailwind CSS  ·  Node.js
Three.js  ·  React Three Fiber  ·  Rapier (physics)  ·  Framer Motion
next-intl (EN/ID)  ·  Groq + Gemini (AI chatbot)
```

---

## Getting Started

### Prerequisites

```bash
Node.js >= 18.0.0
npm >= 9.0.0
```

### 1. Clone the repository

```bash
git clone https://github.com/AndreaPolazzo/PersonalBlog.git
cd PersonalBlog
```

### 2. Install dependencies

```bash
npm install
```

### 3. Configure environment variables

Create a `.env.local` file in the root directory:

```env
# GitHub Integration (for stats section)
NEXT_PUBLIC_GITHUB_USERNAME=your_github_username
GITHUB_TOKEN=github_pat_your_personal_access_token

# WakaTime Integration (for coding stats)
WAKATIME_API_KEY=waka_your_wakatime_api_key

# AI Chatbot — Groq (primary LLM provider)
GROQ_API_KEY=gsk_your_groq_api_key

# AI Chatbot — Gemini (automatic fallback)
GEMINI_API_KEY=your_gemini_api_key
```

### 4. Run the development server

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

### 5. Build for production

```bash
npm run build
npm start
```

### Available Scripts

| Command | Description |
|---------|-------------|
| `npm run dev` | Start development server with Turbopack |
| `npm run build` | Build optimized production bundle |
| `npm start` | Serve the production build locally |
| `npm run lint` | Run ESLint checks |

---

## Contact

| Platform | Link |
|----------|------|
| 📧 **Email** | [andrea@andreapolazzo.com](mailto:andrea@andreapolazzo.com) |
| 💼 **LinkedIn** | [andrea-polazzo](https://www.linkedin.com/in/andrea-polazzo-235a383a3/) |
| 🐙 **GitHub** | [@AndreaPolazzo](https://github.com/AndreaPolazzo) |

---

<div align="center">
<sub>© 2026 Andrea Polazzo · All rights reserved.</sub>
</div>
