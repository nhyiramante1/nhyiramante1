# Hey, I'm Nhyira 👋🏾

**Software developer · builder · creative technologist**

I build web and mobile apps, backend systems, and AI tools where the human
stays the author and the machine stays accountable.

I'm a Computer Science student at Calvin University (May 2028), working at the
intersection of software engineering, AI systems, and creative technology.

[![Portfolio](https://img.shields.io/badge/Portfolio-nhyiramante.com-111111?style=flat-square&logo=vercel&logoColor=white)](https://nhyiramante.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Nhyira_Mante-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nhyiramante1)
[![Email](https://img.shields.io/badge/Email-Say_Hello-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:nhyiramante1@gmail.com)

## 🚧 Currently Building

- **[Ballers HQ](https://apps.apple.com/us/app/ballers-hq/id6802320742)**
  *(iPhone app on the App Store, and [on the web](https://ball.nhyiramante.com))*:
  a campus football app built on an assurance contract. You pledge "I'm in if
  we hit 10," and when the tenth person taps in, every pledge becomes a yes at
  once. I started it as a web app on my TypeScript background, then learned
  Expo, EAS and Neon to take it from first commit to App Store approval in six
  weeks. TypeScript monorepo: Expo (React Native) app, Next.js API, Postgres on
  Neon with Drizzle, Better Auth, over-the-air updates. I designed the review
  process that let Claude Code and Codex build in parallel from one shared plan,
  with every change reviewed by a different agent and nothing shipped without my
  approval. The code is private;
  **[the case study](https://nhyiramante.com/projects/ballers-hq)** tells the story.

- **Reflective mind-mapping** *(research, AI Tools Lab,
  [AIToolsLab/writing-tools](https://github.com/AIToolsLab/writing-tools))*:
  an AI writing tool that helps you externalize *your own* thinking into a map
  without ever authoring structure for you. The AI questions and mirrors your
  words back; every card, hierarchy, and connection is user-authored, with the
  guarantees enforced in code and hardened by a property-based fuzz harness that
  attacks the system with an adversarial mock LLM. **Co-first author of a UIST
  2026 poster submission on this work; revising for resubmission.** On the
  product side, I migrated the platform's authentication from Auth0 to Better
  Auth: sessions, Google OAuth, protected endpoints, and the OAuth device
  authorization flow (built because a Word add-in taskpane can't rely on
  browser cookies).

- **[Duet](https://github.com/nhyiramante1/Local-Dual-Agent)**: a local
  multi-agent coding orchestrator. Claude Code and OpenAI Codex implement and
  review each other's work in isolated git worktrees, behind human plan and
  merge approvals. Persistent Node/TypeScript service, versioned HTTP API,
  SQLite persistence, and a web dashboard with a native tool-calling manager
  agent (Groq / Gemini / OpenAI-compatible). 200+ tests.

- **[Nhyira OS](https://nhyiramante.com)**: my personal site and creative
  platform for software, writing, media, and interaction design. Vite + React
  with scroll-driven motion, Hono API, deployed on Cloudflare Workers.

## 🧠 How I think about AI tools

- **Trust model judgment; verify model authority.** In Duet, agents propose;
  approving, merging, and running are human actions, enforced by the backend,
  not by prompts.
- **AI can reveal its thinking; it can't hand you an artifact to
  rubber-stamp.** The mind-map system shows the writer exactly what the AI is
  tracking and waiting for, but nothing reaches the map unless the user says it
  in their own words and confirms it.
- **Enforcement in code, calibration in config.** Guarantees live in tested
  code paths, including property-based fuzzing against an adversarial LLM, not
  in system prompts. If a constraint matters, there's a validator behind it.

## ✨ Selected Public Work

- **[Duet](https://github.com/nhyiramante1/Local-Dual-Agent)**  
  Claude Code and Codex implementing and reviewing each other's work, behind
  human approvals.

- **[First Thought](https://nhyiramante.com/projects/first-thought)**  
  A browser-based word-association game exploring language, pace, and
  reflection through play.

- **[Clicker Challenge](https://github.com/nhyiramante1/Clicker_Challenge)**  
  A 2D reaction-based shooter game built with Python, Tkinter, and Pygame.

## 💻 Tech Stack

### Product, Frontend and Mobile

<p>
  <img alt="React" src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB">
  <img alt="React Native" src="https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB">
  <img alt="Expo" src="https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=white">
  <img alt="Next.js" src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white">
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white">
  <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
  <img alt="Vite" src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white">
  <img alt="Tailwind CSS" src="https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white">
</p>

### Backend, Data and Platform

<p>
  <img alt="Node.js" src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white">
  <img alt="Hono" src="https://img.shields.io/badge/Hono-E36002?style=for-the-badge&logo=hono&logoColor=white">
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white">
  <img alt="Neon" src="https://img.shields.io/badge/Neon-00E599?style=for-the-badge&logo=neon&logoColor=black">
  <img alt="Drizzle" src="https://img.shields.io/badge/Drizzle-C5F74F?style=for-the-badge&logo=drizzle&logoColor=black">
  <img alt="SQLite" src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white">
  <img alt="Better Auth" src="https://img.shields.io/badge/Better_Auth-000000?style=for-the-badge&logo=betterauth&logoColor=white">
  <img alt="Vercel" src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white">
  <img alt="Cloudflare Workers" src="https://img.shields.io/badge/Cloudflare_Workers-F38020?style=for-the-badge&logo=cloudflare&logoColor=white">
  <img alt="Vitest" src="https://img.shields.io/badge/Vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white">
</p>

### Other Languages and Tools

<p>
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
  <img alt="C++" src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white">
  <img alt="C Sharp" src="https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=dotnet&logoColor=white">
  <img alt="Git" src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white">
</p>

## Beyond Code

I work as a writing consultant at my university's Rhetoric Center, the same
non-directive philosophy that shapes the AI tools I build. I edit video, led a
multimedia team for three years, and write about what I learn.

I've also earned international STEM recognition, including a Gold Medal at
the VANDA Science Global Finals and medals across Singapore math olympiads.

Explore the fuller story at **[nhyiramante.com](https://nhyiramante.com)**.
