```
$ whoami
```

**Corey Epstein** — founder, builder, person who taught AI agents to do his job so he could do more of it.

I run multiple companies from a single terminal. Not because I'm efficient — because I built a system that is.

I don't use AI to write code faster. I use it to run entire operations: shipping products, managing email, writing content, analyzing data, deploying to production. Agents that actually work, not demos that look good in a tweet.

```
"There's a better way. Find it."
```

---

### The system

I built **[HQ](https://github.com/coreyepstein/hq-starter-kit)** — a personal operating system where AI agents are employees, not assistants.

```
HQ/
├── companies/          # 4 isolated business contexts (credentials never cross)
├── workers/            # 30+ specialized AI agents
│   ├── dev-team/       # 16 workers: architect → backend → frontend → QA → deploy
│   ├── content-team/   # 5 workers: brand → sales → product → legal → publish
│   └── ops/            # CFO, CMO, analyst, security scanner
├── projects/           # PRD-driven execution (write spec → agents build it)
├── knowledge/          # Searchable context per company, per domain
└── .claude/commands/   # 22 slash commands that orchestrate everything
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

Write a spec. Go to sleep. Wake up to working software. The agents pick tasks, write code, run tests, fix failures, and loop until the PRD is done. Each cycle captures learnings that make the next cycle better.

This isn't theoretical. It's how I ship production code across all my companies.

---

### What I've open-sourced

| Project | What it does |
|---------|-------------|
| **[hq-starter-kit](https://github.com/coreyepstein/hq-starter-kit)** | The full HQ framework — clone it, make it yours |
| **[ralph-methodology](https://github.com/coreyepstein/ralph-methodology)** | The autonomous coding loop documentation |
| **[mr-burns](https://github.com/coreyepstein/mr-burns)** | PRD-driven autonomous coding agent (TUI for Claude Code) |
| **[advanced-gmail-mcp](https://github.com/coreyepstein/advanced-gmail-mcp)** | Gmail MCP server — multi-account email from the terminal |
| **[advanced-slack-mcp](https://github.com/coreyepstein/advanced-slack-mcp)** | Slack MCP server — multi-workspace messaging |
| **[ralph-planner](https://github.com/coreyepstein/ralph-planner)** | Collaborative PRD planning with AI assistance |
| **[hq-architecture](https://github.com/coreyepstein/hq-architecture)** | Interactive visual guide to the HQ system |
| **[screenshotpath](https://github.com/coreyepstein/screenshotpath)** | Screenshot → clipboard path (tiny macOS utility) |

---

### The stack

```
Languages    TypeScript · Node.js · SQL
Frameworks   Next.js · React · Tailwind · Playwright
AI           Claude Code · MCP Protocol · qmd (semantic search)
Infra        Vercel · Neon (Postgres) · DynamoDB · Resend
Mail/Comms   Gmail MCP · Slack MCP · Post-Bridge API
```

---

### Background

CEO & Founder at [Voyage](https://vyg.ai) (SMS + AI for e-commerce). Chief Design Officer at [Abacus](https://goabacus.co) (enterprise AI for regulated industries). Building [Indigo AI](https://github.com/coreyepstein). MBA from UCLA Anderson. Ex-Deloitte. Based in Boulder, CO.

I've been building products for 15 years. The last two have been the most productive — because I stopped doing the work and started designing systems that do it for me.

---

<p align="center">
  <a href="https://x.com/coreyepstein"><img src="https://img.shields.io/badge/@coreyepstein-000?style=flat&logo=x&logoColor=white" alt="X"></a>&nbsp;&nbsp;
  <a href="https://linkedin.com/in/coreyepstein"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"></a>&nbsp;&nbsp;
  <a href="https://coreyepstein.com"><img src="https://img.shields.io/badge/coreyepstein.com-111?style=flat&logo=safari&logoColor=white" alt="Website"></a>
</p>

