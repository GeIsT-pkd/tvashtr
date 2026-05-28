# Tvashtr

Shareable Claude skills. Behavioral rule files you install once — Claude applies them automatically, every session.

---

## Skills

Each skill is a standalone `.md` file. Install it once — Claude picks it up automatically on every session.

| Category | Skill | What it does |
|---|---|---|
| Security | [kremlin-wall](./kremlin-wall.md) | Always-on ingestion defense. Protects Claude from prompt injection in agentic workflows, automated pipelines, and external content. |

---

## Install

**Terminal**
```bash
mkdir -p ~/.claude/skills && curl -s https://raw.githubusercontent.com/GeIsT-pkd/tvashtr/main/<skill-name>.md -o ~/.claude/skills/<skill-name>.md
```
Then add a reference line to `~/.claude/CLAUDE.md`. Each skill's page has the exact line to add.

**No terminal?**
Every skill has a matching `-installer.md` file. Open it → Cmd+A / Ctrl+A → Copy → paste into Claude → send: **install this**

---

*Tvashtr — Vedic god of craft and skill.*
