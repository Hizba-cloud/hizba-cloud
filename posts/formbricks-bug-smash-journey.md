# 🚀 Smashing Bugs & Building Aesthetics: My Formbricks Open-Source Journey

*Published on: August 23, 2026*

Stepping into a massive, production-grade open-source codebase for the first time can feel like walking into a labyrinth. But as a developer and designer who loves clean aesthetics and "vibe coding," I decided it was time to dive headfirst into the **Formbricks Bug Smash Challenge**—and what a ride it has been!

---

## 💡 The Challenge & The Goal
Formbricks is an incredible open-source experience management and surveying platform built on a powerful modern stack (Next.js, TypeScript, Prisma). My goal wasn't just to clone the repository, but to genuinely understand the developer experience, hunt down configuration hurdles, and stabilize the local environment.

## 🛠️ Tackling the Hurdles
When setting up a large-scale repository locally, edge runtimes and environment variables can throw unexpected roadblocks. Here is how I broke down the fix:

*   **Edge Runtime Logger Handlers:** Resolved configuration conflicts in `apps/web/instrumentation.ts` and `sentry.edge.config.ts` to ensure clean, error-free telemetry execution.
*   **Next.js Bundling & Config:** Fine-tuned `apps/web/next.config.mjs` for seamless module resolution across server environments.
*   **Database Stability:** Configured robust environment variables (`.env.example`) and ironed out local PostgreSQL / Prisma connection timeouts.

## 📊 Organizing Like a Pro with GitHub Projects
To keep my workflow structured, I didn't just write code—I treated it like a real product launch! 
*   I set up a dedicated **GitHub Project Board** featuring a Kanban workflow (Backlog, In Progress, and Done).
*   I tracked every phase of my bug-fixing journey, transforming a chaotic debugging session into a clean, manageable roadmap.

## ✨ Wrapping Up
Open-source contribution is as much about patience and systematic problem-solving as it is about writing code. Polishing my repository with an aesthetic `README.md` and a fully managed project board made this challenge an unforgettable experience.

*Stay tuned for more updates as I dive deeper into code, design, and open-source contributions!*
