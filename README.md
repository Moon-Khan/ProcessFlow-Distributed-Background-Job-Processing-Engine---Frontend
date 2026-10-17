# ProcessFlow: Dashboard (Frontend)

React + TypeScript + Vite dashboard for ProcessFlow, a reliable background job processing engine.

It lets users upload CSV files, request PDF reports, and watch jobs move through *queued -> active -> completed / retrying / dead* live over WebSockets. Admins can inspect failures and replay dead-letter jobs.

**Status:** placeholder. Active development starts in **Phase 11** of the plan. Until then the backend phases are driven with load-test scripts, not the UI.

- Plan, architecture and experiments: see the [backend repository](https://github.com/Moon-Khan/ProcessFlow-Distributed-Background-Job-Processing-Engine---Backend) (`docs/PLAN.md`).
- Same workflow as the backend: phase branch + stacked PRs. Tags are prefixed `fe-` (e.g. `fe-v0.11.0`).
