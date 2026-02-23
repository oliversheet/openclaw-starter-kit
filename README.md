# OpenClaw Starter Kit 🐾

A ready-to-use workspace template for giving your AI agent personality, memory, and autonomy.

Built by [@jeffweisbein](https://x.com/jeffweisbein) — shared on [This Week in Startups](https://thisweekinstartups.com).

## What is this?

This is the workspace structure that powers a personal AI assistant running on [OpenClaw](https://openclaw.ai). It gives your AI:

- **Personality** (SOUL.md) — opinions, tone, boundaries
- **Memory** (MEMORY.md + memory/) — long-term recall across sessions
- **Context** (USER.md) — knows who you are and how you work
- **Proactive behavior** (HEARTBEAT.md) — checks email, calendar, mentions without being asked
- **Safety rails** (AGENTS.md) — knows when to act vs. ask

## Quick Start

1. Install OpenClaw: `npm i -g openclaw` (or see [docs](https://docs.openclaw.ai))
2. Copy these files into your OpenClaw workspace (default: `~/clawd/`)
3. Fill in `USER.md` with your info
4. Fill in `IDENTITY.md` to name your AI
5. Start chatting — your AI will evolve from there

```bash
# Copy the starter kit
cp -r openclaw-starter-kit/* ~/clawd/
mkdir -p ~/clawd/memory

# Start OpenClaw
openclaw gateway start
```

## The Files

| File | Purpose |
|------|---------|
| `AGENTS.md` | Operating manual — how your AI behaves, when to speak vs. stay quiet, safety rules |
| `SOUL.md` | Personality and values — what kind of assistant it should be |
| `USER.md` | About you — preferences, work style, projects, interests |
| `IDENTITY.md` | The AI's own identity — name, vibe, emoji |
| `MEMORY.md` | Long-term memory — curated by the AI over time |
| `HEARTBEAT.md` | Periodic checks — what to monitor on each heartbeat |
| `TOOLS.md` | Local tool notes — device names, SSH hosts, API quirks |

## Philosophy

Your AI wakes up fresh every session. These files ARE its memory and personality. The more you put in, the better it gets.

- `SOUL.md` = who it is
- `USER.md` = who you are
- `MEMORY.md` = what it's learned
- `AGENTS.md` = how it operates

## Tips

- **Let it evolve.** Your AI will update these files over time. That's the point.
- **Be specific in USER.md.** "I prefer short updates" > leaving it blank.
- **Name your AI.** It sounds silly but it changes the dynamic completely.
- **Use heartbeats.** A proactive AI that checks your email and calendar is 10x more useful than one that waits to be asked.

## Going Further

- **Sub-agents:** Set up specialized agents (content writer, dev ops, researcher) that your main AI delegates to
- **Cron jobs:** Schedule recurring tasks (daily email summaries, weekly reports)
- **Skills:** Add OpenClaw skills from [ClawhHub](https://clawhub.com) for specific capabilities
- **Channels:** Connect Signal, Telegram, Discord, iMessage, etc.

---

*Your AI is only as good as the context you give it. Start here, make it yours.*
