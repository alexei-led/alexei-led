## Hey 👋

I build infrastructure and developer tools for systems that fail, scale, and lately think for themselves. Sometimes all three before lunch.

Shipping software professionally since 1995: bare metal, VMs, containers, Kubernetes, cloud, and now AI coding agents. Each wave promised to make the last one obsolete. All of them still page someone at 3 a.m.

### Building now: AI coding agents, with supervision

- [**claude-router**](https://github.com/alexei-led/claude-router) `new` — Claude Code plugin that picks the model and effort for each turn by two dials: how hard the turn is, and what kind of work it is. The cheap model runs the tests; the strong one writes the fix. No proxy.
- [**ccgram**](https://github.com/alexei-led/ccgram) — Telegram ↔ tmux bridge for Claude Code, Codex CLI and Pi. Watch parallel agent sessions and answer their prompts from your phone. Agents don't take coffee breaks; you still should.
- [**archfit**](https://github.com/alexei-led/archfit) `new` — Architecture-fitness gates for AI agents and CI. Tests stay green while module boundaries quietly rot; archfit fails the build when they do. [Why I built it](https://alexei-led.github.io/development/devops/architecture/ai/2026/08/23/the-tests-are-green-the-architecture-is-not.html).
- [**cc-thingz**](https://github.com/alexei-led/cc-thingz) — Portable skills, agents and hooks for Claude Code, Codex, Copilot, Cursor and Pi. Write a skill once, use it in every agent.

### Infrastructure classics

- [**pumba**](https://github.com/alexei-led/pumba) ![stars](https://img.shields.io/github/stars/alexei-led/pumba?style=flat-square&label=%E2%98%85) — Chaos testing, network emulation and stress testing for containers (Docker, containerd, Podman). Breaking things on purpose since 2016, so production can save its surprises for something new.
- [**kubeip**](https://github.com/doitintl/kubeip) ![stars](https://img.shields.io/github/stars/doitintl/kubeip?style=flat-square&label=%E2%98%85) — Static public IPs for Kubernetes nodes on GKE and EKS. For the firewall that only trusts IPs it has met before.
- [**spotinfo**](https://github.com/alexei-led/spotinfo) ![stars](https://img.shields.io/github/stars/alexei-led/spotinfo?style=flat-square&label=%E2%98%85) — Spot instance pricing, savings and interruption rates across AWS, GCP and Azure, offline. Spot pricing shouldn't be a mystery.
- [**secrets-init**](https://github.com/doitintl/secrets-init) ![stars](https://img.shields.io/github/stars/doitintl/secrets-init?style=flat-square&label=%E2%98%85) + [**kube-secrets-init**](https://github.com/doitintl/kube-secrets-init) — Pull AWS and GCP secrets into containers at startup, plus a webhook that wires it into Kubernetes Pods. Fewer secrets in `.env` files "just for now".

<sub>Retired with honors: [k8s-mcp-server](https://github.com/alexei-led/k8s-mcp-server) and [cloud-mcp-server](https://github.com/alexei-led/cloud-mcp-server), early MCP servers that gave AI assistants `kubectl` and the AWS CLI in a sandbox. Archived, still readable.</sub>

### Writing

I write at [alexei-led.github.io](https://alexei-led.github.io) about containers, Kubernetes, chaos engineering, and keeping AI agents honest.

`Go` · `Python` · `TypeScript` · `Kubernetes` · `AWS` · `GCP` · `MCP` · `AI agents`

<sub>Opinions are my own. Code is open source. Future is uncertain.</sub>
