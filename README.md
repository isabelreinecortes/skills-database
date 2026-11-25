# 🧠 Skills Database

**The largest open collection of AI agent skills** — 238 specialized instruction modules for Claude, Gemini, Antigravity, and other AI coding assistants.

[![Skills](https://img.shields.io/badge/skills-238-blue)](#-full-skill-index)
[![License](https://img.shields.io/badge/license-mixed-green)](#-license)
[![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-brightgreen)](#-contributing)

---

## 🤔 What Are Skills?

Skills are **plug-and-play knowledge modules** that turn a general-purpose AI assistant into a domain expert. Each skill is a self-contained folder with structured instructions, scripts, and resources that an AI agent loads on demand.

**Think of it this way:** instead of explaining your entire tech stack, security policies, or design system every time — you just point the AI to a skill, and it *already knows*.

```
You:   @stripe-integration add subscription billing to my SaaS
AI:    ✓ Loaded stripe-integration skill
       → Setting up Checkout Sessions, webhooks, dunning management...
```

---

## 🚀 Quick Start

### 1. Clone the repository

```bash
git clone https://github.com/isabelreinecortes/skills-database.git
```

### 2. Copy skills to your agent's directory

| Agent | Skills directory |
|-------|-----------------|
| Claude Code | `.claude/skills/` |
| Antigravity | `.gemini/skills/` |
| Gemini CLI | `.gemini/skills/` |
| Custom agents | Wherever your agent reads skills from |

### 3. Use a skill

```
@brainstorming help me design a task management app
@react-best-practices review my component architecture
@ethical-hacking-methodology run a pentest on my staging server
```

> **Tip:** You don't need all 238 skills — just copy the ones relevant to your project.

---

## 📂 Repository Structure

```
skills-database/
├── skill-name/
│   ├── SKILL.md              # Main instruction file (required)
│   ├── scripts/              # Helper scripts & utilities (optional)
│   ├── examples/             # Reference implementations (optional)
│   ├── resources/            # Templates, data files (optional)
│   └── references/           # Additional documentation (optional)
├── Anthropic/                # Official Anthropic skills collection
│   ├── algorithmic-art/
│   ├── canvas-design/
│   ├── doc-coauthoring/
│   ├── webapp-testing/
│   └── ...
└── README.md
```

Each skill only requires a `SKILL.md` file with YAML frontmatter (`name`, `description`) and markdown instructions.

---

## 🗂️ Skill Categories

### 🎨 Creative & Design
Build beautiful interfaces and visual content.

| Skill | Description |
|-------|-------------|
| `ui-ux-pro-max` | Full design intelligence: 50+ styles, 97 palettes, 57 font pairings, 9 tech stacks |
| `algorithmic-art` | Generate algorithmic art with p5.js |
| `canvas-design` | Design posters and artwork (PNG/PDF) |
| `frontend-design` | Production-grade frontend interfaces |
| `web-artifacts-builder` | Modern web apps with React, Tailwind, Shadcn/ui |
| `theme-factory` | Generate themes for documents and presentations |
| `slack-gif-creator` | High-quality GIFs for Slack |
| `scroll-experience` | Scroll-driven animations and interactions |
| `3d-web-experience` | 3D web experiences and visualizations |
| `interactive-portfolio` | Build interactive portfolio sites |

### 💻 Development & Engineering
Write better code, faster.

| Skill | Description |
|-------|-------------|
| `senior-fullstack` | Full-stack development patterns and best practices |
| `react-best-practices` | Modern React patterns and architecture |
| `nextjs-best-practices` | Next.js app router, SSR, optimization |
| `typescript-expert` | Advanced TypeScript patterns and utilities |
| `python-patterns` | Pythonic patterns and best practices |
| `nodejs-best-practices` | Node.js production patterns |
| `nestjs-expert` | NestJS architecture and patterns |
| `javascript-mastery` | Advanced JavaScript techniques |
| `bun-development` | Bun runtime development |
| `graphql` | GraphQL API design and implementation |
| `prisma-expert` | Prisma ORM best practices |
| `clean-code` | Clean code principles and refactoring |
| `software-architecture` | System design and architecture patterns |
| `architecture` | Software architecture decision records |

### 🧪 Testing & Quality
Ship with confidence.

| Skill | Description |
|-------|-------------|
| `test-driven-development` | TDD workflow: write tests first |
| `tdd-workflow` | Test-driven development lifecycle |
| `systematic-debugging` | Debug methodically, not randomly |
| `playwright-skill` | E2E testing with Playwright |
| `webapp-testing` | Web application testing strategies |
| `testing-patterns` | Testing patterns and anti-patterns |
| `code-review-checklist` | Comprehensive code review guidelines |
| `production-code-audit` | Audit production code for issues |
| `performance-profiling` | Performance profiling and optimization |
| `lint-and-validate` | Linting and validation pipelines |

### 🔒 Security & Penetration Testing
Find vulnerabilities before attackers do.

| Skill | Description |
|-------|-------------|
| `ethical-hacking-methodology` | Complete penetration testing lifecycle |
| `burp-suite-testing` | Web app security testing with Burp Suite |
| `sql-injection-testing` | SQL injection detection and prevention |
| `xss-html-injection` | XSS and HTML injection testing |
| `api-fuzzing-bug-bounty` | API fuzzing for bug bounty hunting |
| `metasploit-framework` | Metasploit exploitation framework |
| `red-team-tactics` | Red team attack methodologies |
| `red-team-tools` | Offensive security tool arsenal |
| `vulnerability-scanner` | Automated vulnerability scanning |
| `pentest-checklist` | Penetration testing checklists |
| `pentest-commands` | Essential pentest command reference |
| `active-directory-attacks` | Active Directory attack vectors |
| `cloud-penetration-testing` | Cloud infrastructure security testing |
| `aws-penetration-testing` | AWS-specific penetration testing |
| `linux-privilege-escalation` | Linux privilege escalation techniques |
| `windows-privilege-escalation` | Windows privilege escalation methods |
| `wireshark-analysis` | Network traffic analysis with Wireshark |
| `shodan-reconnaissance` | Internet-wide scanning with Shodan |
| `scanning-tools` | Security scanning tool reference |
| `smtp-penetration-testing` | SMTP service security testing |
| `ssh-penetration-testing` | SSH service security testing |
| `wordpress-penetration-testing` | WordPress security testing |

### 🤖 AI & Agents
Build and orchestrate AI systems.

| Skill | Description |
|-------|-------------|
| `ai-agents-architect` | Design multi-agent AI systems |
| `autonomous-agents` | Autonomous agent patterns |
| `autonomous-agent-patterns` | Agent autonomy design patterns |
| `agent-manager-skill` | Manage multiple CLI agents via tmux |
| `agent-evaluation` | Evaluate and benchmark AI agents |
| `agent-memory-systems` | Agent memory and context management |
| `agent-memory-mcp` | MCP-based agent memory |
| `agent-tool-builder` | Build custom tools for AI agents |
| `computer-use-agents` | Computer-use agent development |
| `crewai` | CrewAI multi-agent orchestration |
| `langgraph` | LangGraph agent workflows |
| `voice-agents` | Voice-powered AI agents |
| `voice-ai-development` | Voice AI application development |
| `prompt-engineer` | Prompt engineering techniques |
| `prompt-engineering` | Advanced prompt design |
| `prompt-library` | Reusable prompt templates |
| `prompt-caching` | Prompt caching strategies |
| `rag-engineer` | RAG pipeline design |
| `rag-implementation` | RAG implementation patterns |
| `llm-app-patterns` | LLM application design patterns |
| `langfuse` | LLM observability with Langfuse |
| `research-engineer` | AI research engineering |

### 📋 Planning & Workflow
Plan before you build.

| Skill | Description |
|-------|-------------|
| `brainstorming` | Brainstorm and design before coding |
| `writing-plans` | Write detailed implementation plans |
| `plan-writing` | Structured plan authoring |
| `planning-with-files` | File-based planning (Manus-style) |
| `executing-plans` | Execute plans with checkpoints |
| `concise-planning` | Lightweight planning for small tasks |
| `kaizen` | Continuous improvement methodology |
| `workflow-automation` | Automate repetitive workflows |
| `zapier-make-patterns` | Zapier & Make automation patterns |
| `using-git-worktrees` | Parallel work with Git worktrees |
| `dispatching-parallel-agents` | Fan out tasks to multiple agents |
| `parallel-agents` | Parallel agent coordination |
| `subagent-driven-development` | Coordinated multi-agent development |

### 📄 Documents & Office
Create and manipulate documents programmatically.

| Skill | Description |
|-------|-------------|
| `docx` / `docx-official` | Create, edit, and analyze Word documents |
| `xlsx` / `xlsx-official` | Work with Excel spreadsheets |
| `pptx` / `pptx-official` | Create and modify PowerPoint files |
| `pdf` / `pdf-official` | PDF manipulation and form filling |
| `doc-coauthoring` | Collaborative document authoring |
| `documentation-templates` | Documentation template library |
| `copy-editing` | Copy editing and proofreading |
| `copywriting` | Marketing copywriting |

### ☁️ Cloud & DevOps
Deploy and scale applications.

| Skill | Description |
|-------|-------------|
| `docker-expert` | Docker containers and orchestration |
| `aws-serverless` | AWS Lambda and serverless patterns |
| `azure-functions` | Azure Functions development |
| `gcp-cloud-run` | Google Cloud Run deployment |
| `firebase` | Firebase full-stack development |
| `vercel-deployment` | Vercel deployment strategies |
| `server-management` | Server administration |
| `deployment-procedures` | Deployment checklists and procedures |
| `github-workflow-automation` | GitHub Actions CI/CD |

### 💰 Business & SaaS
Build, launch, and grow products.

| Skill | Description |
|-------|-------------|
| `stripe-integration` | Payments, subscriptions, billing, webhooks |
| `micro-saas-launcher` | Launch a micro-SaaS from zero |
| `app-store-optimization` | App Store & Play Store optimization |
| `pricing-strategy` | Pricing models and strategies |
| `launch-strategy` | Product launch playbooks |
| `free-tool-strategy` | Free tool marketing strategy |
| `referral-program` | Referral and growth programs |
| `competitor-alternatives` | Competitor analysis frameworks |
| `product-manager-toolkit` | Product management tools and frameworks |
| `ai-product` | AI product development |
| `ai-wrapper-product` | Build AI wrapper products |
| `notion-template-business` | Notion template business |

### 📈 Marketing & SEO
Acquire and convert users.

| Skill | Description |
|-------|-------------|
| `seo-fundamentals` | SEO foundations and best practices |
| `seo-audit` | Complete SEO audit methodology |
| `programmatic-seo` | Programmatic SEO at scale |
| `schema-markup` | Structured data and rich snippets |
| `analytics-tracking` | Analytics setup and tracking |
| `paid-ads` | Paid advertising strategies |
| `social-content` | Social media content creation |
| `content-creator` | Content creation workflows |
| `marketing-ideas` | Marketing ideation framework |
| `marketing-psychology` | Psychology-driven marketing |
| `email-sequence` | Email sequence design |
| `email-systems` | Email infrastructure and deliverability |

### 🔧 CRO & Growth
Optimize every step of the funnel.

| Skill | Description |
|-------|-------------|
| `page-cro` | Landing page conversion optimization |
| `form-cro` | Form conversion optimization |
| `popup-cro` | Popup conversion optimization |
| `signup-flow-cro` | Signup flow optimization |
| `onboarding-cro` | User onboarding optimization |
| `paywall-upgrade-cro` | Paywall and upgrade flow optimization |
| `ab-test-setup` | A/B testing setup and analysis |

### 🔌 Integrations & APIs
Connect everything together.

| Skill | Description |
|-------|-------------|
| `algolia-search` | Algolia search implementation |
| `clerk-auth` | Clerk authentication setup |
| `hubspot-integration` | HubSpot CRM integration |
| `plaid-fintech` | Plaid financial data integration |
| `segment-cdp` | Segment customer data platform |
| `twilio-communications` | Twilio SMS, voice, and messaging |
| `salesforce-development` | Salesforce development |
| `shopify-development` | Shopify theme and app development |
| `shopify-apps` | Shopify app development |
| `inngest` | Inngest event-driven functions |
| `trigger-dev` | Trigger.dev background jobs |
| `bullmq-specialist` | BullMQ job queue management |
| `upstash-qstash` | Upstash QStash messaging |
| `neon-postgres` | Neon serverless Postgres |
| `nextjs-supabase-auth` | Next.js + Supabase authentication |

### 🛠️ Tooling & Misc
Specialized utilities and helpers.

| Skill | Description |
|-------|-------------|
| `git-pushing` | Git commit best practices |
| `bash-linux` | Bash scripting and Linux commands |
| `linux-shell-scripting` | Advanced shell scripting |
| `powershell-windows` | PowerShell scripting for Windows |
| `browser-automation` | Browser automation patterns |
| `browser-extension-builder` | Build browser extensions |
| `discord-bot-architect` | Discord bot development |
| `slack-bot-builder` | Slack bot development |
| `telegram-bot-builder` | Telegram bot development |
| `telegram-mini-app` | Telegram Mini App development |
| `mcp-builder` | Build MCP (Model Context Protocol) servers |
| `skill-creator` | Create new skills |
| `skill-developer` | Advanced skill development |
| `writing-skills` | Skill authoring tools and validation |
| `file-organizer` | File organization automation |
| `i18n-localization` | Internationalization and localization |
| `remotion-best-practices` | Remotion video rendering |
| `game-development` | Game development patterns |
| `mobile-design` | Mobile-first design patterns |
| `notebooklm` | Google NotebookLM integration |
| `viral-generator-builder` | Build viral content generators |

---

## 💡 Popular Skills to Start With

| You want to... | Use this skill |
|----------------|---------------|
| 🎨 Design a beautiful UI | `@ui-ux-pro-max` |
| 🧪 Write tests first | `@test-driven-development` |
| 🔒 Test security | `@ethical-hacking-methodology` |
| 💳 Add payments | `@stripe-integration` |
| 📝 Plan before coding | `@brainstorming` |
| 🐛 Fix bugs systematically | `@systematic-debugging` |
| ⚛️ Build with React | `@react-best-practices` |
| 🤖 Build AI agents | `@ai-agents-architect` |
| 📄 Generate documents | `@docx` or `@pdf` |
| 🚀 Deploy to production | `@vercel-deployment` |

---

## 🔍 Finding Skills

```bash
# List all skills
ls skills-database/

# Search by keyword
ls skills-database/ | grep "security"

# Read a skill's description
head -5 skills-database/skill-name/SKILL.md
```

---

## ✍️ Creating Your Own Skill

Each skill is just a folder with a `SKILL.md` file:

```markdown
---
name: my-awesome-skill
description: "What this skill does and when to use it"
---

# My Awesome Skill

## When to Use
- Use when [scenario 1]
- Use when [scenario 2]

## Instructions
[Step-by-step guide for the AI agent]

## Examples
[Code examples and usage patterns]
```

> **Pro tip:** Use the `@skill-creator` skill to auto-generate new skills!

---

## 🤝 Contributing

Contributions are welcome! To add a new skill:

1. Fork this repository
2. Create a new folder with your skill name (use `kebab-case`)
3. Add a `SKILL.md` with YAML frontmatter (`name`, `description`)
4. Add any supporting scripts, examples, or resources
5. Submit a Pull Request

**Guidelines:**
- One skill per folder
- Keep `SKILL.md` focused and actionable
- Include real-world examples when possible
- Test your skill with an actual AI agent before submitting

---

## 📜 License

This repository aggregates skills from multiple sources. Each skill may carry its own license (check individual folders for `LICENSE.txt`). Skills without an explicit license are shared for educational and personal use.

---

## 🌟 Acknowledgments

This collection includes skills from the community, including contributions from:
- [Anthropic](https://github.com/anthropics) — Official Claude skills
- [UI/UX Pro Max](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) — Design intelligence
- [Vibeship](https://github.com/vibeship) — SaaS and integration skills
- [zebbern](https://github.com/zebbern) — Security and penetration testing
- And many more community contributors

---

<p align="center">
  <b>Find the right skill. Load it. Build faster.</b><br>
  <sub>⭐ Star this repo if you find it useful!</sub>
</p>
