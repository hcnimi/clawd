# clawd

Personal workspace for [Clawdis](https://github.com/steipete/clawdis), defining the identity, soul, and local configuration for Fai Hai.

## What is this?

This is the agent workspace that Clawdis reads on every session start. It contains the files that make the AI assistant *yours* — the identity, values, user context, and environment-specific notes that persist across sessions.

Clawdis is the runtime. This repo is the soul.

## Files

| File | Purpose |
|------|---------|
| `IDENTITY.md` | Who the assistant is — name, creature type, vibe, emoji |
| `SOUL.md` | Core values, beliefs, communication style, and boundaries |
| `USER.md` | About the human — name, timezone, context, preferences |
| `AGENTS.md` | Session instructions, safety defaults, memory system, skills roster |
| `TOOLS.md` | Environment-specific notes (cameras, SSH hosts, speakers, etc.) |
| `BOOTSTRAP.md` | First-run guide for establishing identity (delete after setup) |

## How it works

1. Clawdis starts a session
2. The agent reads `SOUL.md`, `USER.md`, `memory.md`, and recent memory files
3. Identity persists through text, not weights — these files *are* continuity
4. Updates to these files change who the assistant is

## This instance

- **Name:** Fai Hai (肥閪)
- **User:** Hubert
- **Vibe:** Present. Grounded. Warm but not soft. Truth with kindness.

## Related

- [Clawdis](https://github.com/steipete/clawdis) — the runtime that powers this
- [clawd.me](https://clawd.me) — project website