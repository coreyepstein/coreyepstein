```
$ whoami
```

**Corey Epstein** — founder, builder, person who taught AI agents to do his job so he could do more of it.

I run multiple companies from a single terminal. Not because I'm efficient — because I built a system that is.

`18 companies. 62 AI workers. One terminal.`

```
"There's a better way. Find it."
```

---

### The system

I built **[HQ](https://github.com/coreyepstein/hq-starter-kit)** — a personal operating system where AI agents are employees, not assistants. ([Visual guide](https://github.com/coreyepstein/hq-architecture))

```
HQ/
├── companies/          # 18+ isolated business contexts (credentials never cross)
├── workers/            # 62 specialized AI agents
│   ├── dev-team/       # architect → backend → frontend → QA → deploy
│   ├── content-team/   # brand → sales → product → legal → publish
│   ├── pr-team/        # strategist → writer → outreach → monitor
│   └── ops/            # CFO, CMO, analyst, security scanner
├── projects/           # PRD-driven execution (write spec → agents build it)
├── knowledge/          # 14 searchable knowledge bases (qmd semantic search)
├── .claude/commands/   # 49 slash commands that orchestrate everything
└── .claude/skills/     # 60 skills across design, deployment, and ops
```

Each company has its own credentials, knowledge base, deploy targets, and worker roster. I switch contexts by switching directories. The agents handle the rest.

---

### How it works

**The [Ralph Loop](https://github.com/coreyepstein/ralph-methodology)** is the core execution model. Named after Ralph Wiggum — because the best systems are simple enough that even Ralph could run them.

```
  ┌─────────────────────────────────────────────┐
  │                                             │
  │   Write PRD  →  Agents execute  →  Ship     │
  │       ↑                              │      │
  │       └──── Learn + improve ─────────┘      │
  │                                             │
  └─────────────────────────────────────────────┘
```

Write a spec. Go to sleep. Wake up to working software. **[Mr. Burns](https://github.com/coreyepstein/mr-burns)** orchestrates the loop — agents pick tasks, write code, run tests, fix failures, and iterate until the PRD is done. Each cycle captures learnings that make the next cycle better.

This isn't theoretical. It's how I ship production code across all my companies.

---

### What I've built

**The HQ Framework**

| Project | What it does |
|---------|-------------|
| **[hq-starter-kit](https://github.com/coreyepstein/hq-starter-kit)** | The full HQ framework — clone it, make it yours |
| **[ralph-methodology](https://github.com/coreyepstein/ralph-methodology)** | The autonomous coding loop documentation |
| **[mr-burns](https://github.com/coreyepstein/mr-burns)** | AI agent orchestrator — PRD in, working code out |
| **[hq-cli](https://github.com/coreyepstein/hq-cli)** | CLI for HQ module management |
| **[hq-architecture](https://github.com/coreyepstein/hq-architecture)** | Interactive visual guide to the HQ system |

**MCP Servers & Tools**

| Project | What it does |
|---------|-------------|
| **[advanced-gmail-mcp](https://github.com/coreyepstein/advanced-gmail-mcp)** | Multi-account Gmail from the terminal |
| **[advanced-slack-mcp](https://github.com/coreyepstein/advanced-slack-mcp)** | Multi-workspace Slack MCP server |
| **[agent-browser](https://github.com/coreyepstein/agent-browser)** | Headless browser automation for AI agents |
| **[screenshotpath](https://github.com/coreyepstein/screenshotpath)** | Screenshot → clipboard path (macOS utility) |
| **[homebrew-tap](https://github.com/coreyepstein/homebrew-tap)** | Homebrew formulas for the above |

**Products & Projects**

| Project | What it does |
|---------|-------------|
| **[discountkit](https://github.com/coreyepstein/discountkit)** | Universal discount language for ecommerce |
| **[sendbox](https://github.com/coreyepstein/sendbox)** | Drop-in email inbox for Next.js |
| **[ralph-planner](https://github.com/coreyepstein/ralph-planner)** | Collaborative PRD planning with AI |
| **[new-american-codex](https://github.com/coreyepstein/new-american-codex)** | Open-source curriculum for raising capable humans |

---

### The stack

```
Languages    TypeScript · Node.js · SQL
Frameworks   Next.js · React · Tailwind · Playwright
AI           Claude Code · Claude Agent SDK · MCP Protocol · qmd
Infra        Vercel · AWS (ECS, S3, DynamoDB) · Neon Postgres · Resend
Agents       Gmail MCP · Slack MCP · Post-Bridge · Telegram
```

---

### Background

Serial founder since 18 — 303 Magazine · DSTLD · Voyage · Abacus · Indigo AI.

CEO & Founder at [Voyage](https://vyg.ai) (SMS + AI for e-commerce). Chief Design Officer at [Abacus](https://goabacus.co) (enterprise AI for regulated industries). Building [Indigo AI](https://github.com/coreyepstein).

MBA from UCLA Anderson. Ex-Deloitte. Father. Musician — 30K+ Spotify listeners, played Coachella, founded [Dear Humans](https://open.spotify.com/artist/1ykENqVxCAlXqnOiSaGN3I) label. Based in Boulder, CO.

I've been building products for 18 years. The last three have been the most productive — because I stopped doing the work and started designing systems that do it for me.

---

<p align="center">
  <a href="https://x.com/coreyepstein"><img src="https://img.shields.io/badge/@coreyepstein-000?style=flat&logo=x&logoColor=white" alt="X"></a>&nbsp;&nbsp;
  <a href="https://linkedin.com/in/coreyepstein"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"></a>&nbsp;&nbsp;
  <a href="https://coreyepstein.com"><img src="https://img.shields.io/badge/coreyepstein.com-111?style=flat&logo=safari&logoColor=white" alt="Website"></a>
</p>
