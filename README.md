# Jungod (Huang Yijun)

**Aerospace engineering + CS @ Northwestern Polytechnical University** · grad-school-bound (2027) · building with AI agents every day.

I design, run, and debug **AI agent systems** — and I'm actively looking for **remote AI roles**: agent engineering, AI testing & eval, prompt systems.

---

## What I'm good at

| | |
|---|---|
| **Building full apps quickly** | Tauri desktop app (Rust + React) that manages agent projects & prompt versions, with a Cloudflare Worker sync backend — 75 commits in 3 days, ships macOS / Windows / Linux from one codebase |
| **Running agents at scale** | ~8B tokens/month of agent usage on this machine alone (160–250B/month across both machines) — I know where real agent workflows break: context bloat, prompt drift, eval gaps |
| **DeepSeek Harness ecosystem** | Author of [`dsh-anchored-standard`](https://github.com/Jungod1121/dsh-anchored-standard) (★24) — a two-phase agent preset plugin, published in the DSH plugin community |
| **Robotics / SLAM** | Quadrotor autonomy (ROS 2), visual / point SLAM pipelines; exposure to vision-language-agent stacks from aerospace research |
| **Photography** | Contracted photographer at Visual China Group — a trained eye applied to product and UI design |

## Featured project

### [agent-workbench](https://github.com/Jungod1121/agent-workbench-app)

A local-first desktop app to own the **lifecycle of AI agent projects**: `idea → building → testing → live` pipeline, versioned prompts with line-level diff & one-click rollback, cross-machine sync through a ~50-line Cloudflare Worker.

The hard parts other apps punt on — prompt versioning, staged project management, offline-first sync — are the core. Built dogfooding my own daily agent workflow (12 real projects tracked).

**Stack:** Rust (three-layer backend + versioned SQLite migrations) · React + Vite (glass-morphism UI, 4-language i18n) · Tauri 2 · Cloudflare Worker sync · GitHub Actions 3-OS builds

## Currently

- Building a portfolio for **remote AI testing / eval / agent roles**
- Dogfooding my own agent-workflow tooling
- Exploring agent-eval tooling (Promptfoo, custom Bad-Case loops)

---

Open to collaboration and remote AI work — GitHub is the best way to reach me (or the contact info on any pinned project page).