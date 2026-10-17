# ProcessFlow Frontend: notes for Claude

- Full plan and project rules live in the backend repo: `../backend/CLAUDE.md` and `../backend/docs/PLAN.md`. Read those first.
- **Don't write code until the user says so.** Frontend work is planned for Phase 11 (live status via WebSockets).
- Stack: React + TypeScript + Vite, Tailwind, Socket.IO client. Keep it minimal; the UI isn't the focus.
- Git: same phase branch + stacked PR workflow as the backend. Tags prefixed `fe-` (e.g. `fe-p11-after`, `fe-v0.11.0`).
- GitHub remote: **not created yet** (as of 2026-10-17). The user will create the repo, then add it with `git remote add origin <url>` and `git push -u origin main`.
