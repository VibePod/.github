# VibePod

One CLI for all AI coding agents — running in isolated Docker containers.
No required configuration, no setup, full observability.

## Quickstart

```bash
pip install vibepod
vp run <agent>
```

→ [Documentation](https://vibepod.dev/docs/) · [Website](https://vibepod.dev)

## Repositories

**[vibepod-cli](https://github.com/vibepod/vibepod-cli)** — The main CLI (`vp`). Install via pip, run any agent with a single command in an isolated Docker container.

**[vibepod-proxy](https://github.com/vibepod/vibepod-proxy)** — HTTP proxy that captures all outbound traffic from agent containers and logs it to SQLite for inspection and analysis.

**[vibepod-datasette](https://github.com/vibepod/vibepod-datasette)** — Analytics dashboard for browsing captured metrics and logs via Datasette, served at `localhost:8001`.

**[vibepod-agents](https://github.com/vibepod/vibepod-agents)** — Container definitions for all supported agents. Each agent is built and published to Docker Hub automatically via CI.

**[vibepod-skills](https://github.com/vibepod/vibepod-skills)** — Curated reusable skills that can be installed with `vp skills` for supported agents.

**[vibepod-skills-engine](https://github.com/vibepod/vibepod-skills-engine)** — Containerized skills manager used by `vp skills` to install, validate, sync, and update skill folders without requiring local Node tooling.
