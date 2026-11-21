# ProcessFlow Frontend: notes for Claude

- Full plan and project rules: `../backend/CLAUDE.md` and `../docs/PLAN.md` (workspace-level docs). Read those first.
- **Don't write code until the user says so.** Frontend work is planned for Phase 11 (live status via WebSockets).
- Stack: React + TypeScript + Vite, Tailwind, Socket.IO client. Keep it minimal; the UI isn't the focus.
- Git: same workflow as the backend (one phase branch + one phase PR; stacked PRs only if the user asks). Tags prefixed `fe-` (e.g. `fe-p11-after`, `fe-v0.11.0`).
- GitHub remote: `https://github.com/Moon-Khan/ProcessFlow-Distributed-Background-Job-Processing-Engine---Frontend.git` (pushed 2026-10-17).
