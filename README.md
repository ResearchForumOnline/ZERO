# ZERO

<div align="center">
  <img src="https://talktoai.org/1.png" alt="ZERO project banner" width="100%" />
</div>

<p align="center">
  <a href="https://talktoai.org/">TalkToAI</a> |
  <a href="https://openzero.talktoai.org/">OpenZero AIOS</a> |
  <a href="https://zerothink.talktoai.org/">ZeroThink</a> |
  <a href="https://github.com/ResearchForumOnline/ZEROtalktoai">Project Hub</a>
</p>

<p align="center">
  <img alt="Public project" src="https://img.shields.io/badge/status-public%20project-0ea5e9">
  <img alt="AI agents" src="https://img.shields.io/badge/focus-AI%20agents-111827">
  <img alt="Owner maintained" src="https://img.shields.io/badge/owner-maintained-16a34a">
</p>

ZERO is the public AI agent and OpenZero project lane in the TalkToAI ecosystem. It is intended to connect practical AI assistants, configurable agents, document-aware workflows, local/server deployments, and research ideas into one clear public direction.

The goal is simple: make useful AI systems that can be tested, improved, and connected to real workflows without hiding the project behind vague claims.

## What ZERO Is For

ZERO is a home for:

- AI agent experiments and production-ready assistant workflows.
- OpenZero AIOS and ZeroThink public project material.
- Document, memory, retrieval, and multi-agent concepts.
- Local model and server-side AI deployment notes.
- Public demos that can support TalkToAI, FreeWebPanel, ZSEC, and research projects.

## Public Ecosystem

| Area | Link |
| --- | --- |
| TalkToAI | https://talktoai.org/ |
| OpenZero AIOS | https://openzero.talktoai.org/ |
| ZeroThink | https://zerothink.talktoai.org/ |
| Public project hub | https://github.com/ResearchForumOnline/ZEROtalktoai |
| ZSEC Auto Updates | https://github.com/ResearchForumOnline/ZSEC |
| FreeWebPanel | https://github.com/ResearchForumOnline/FreeWebPanel |

## Getting Started

Prerequisites:

- Python 3
- Node.js 16 or newer
- `pnpm`

Basic local setup:

```bash
git clone https://github.com/ResearchForumOnline/ZERO.git
cd ZERO
cp .env.example .env
pnpm install
pnpm build
pnpm start
```

If the repository layout changes, follow the most recent project scripts in `package.json` and keep secrets in local `.env` files only.

## Development Direction

Priority work:

1. Make the public demo path clearer.
2. Document the OpenZero AIOS and ZeroThink connection.
3. Keep local model setup and server deployment notes separate from secrets.
4. Add screenshots or short demo clips where they help visitors understand what is working.
5. Connect security-sensitive server work to ZSEC instead of mixing it into AI demos.

## Repository Boundary

This repository can contain public source, docs, demos, and project notes. It should not contain private server credentials, SSH keys, API keys, customer data, private model keys, or production deployment secrets.

## Related Projects

- ZSEC Auto Updates: https://github.com/ResearchForumOnline/ZSEC
- FreeWebPanel: https://github.com/ResearchForumOnline/FreeWebPanel
- TalkToAI public hub: https://github.com/ResearchForumOnline/ZEROtalktoai

## License

Use the license file in this repository when present. If no license file is present, treat the project as source-available until the owner publishes explicit licensing terms.
