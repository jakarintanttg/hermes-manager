# Safe Export Policy

This repository contains a sanitized public/template view of Jet's Hermes agent manager.

Included:
- Agent role prompts (`SOUL.md`) where available
- Public/example profile configs (`config.example.yaml`)
- Workspace README, Protocols, and Templates
- Setup/operations docs and helper scripts

Excluded:
- `.hermes/` runtime directories
- `.env`, tokens, API keys, OAuth files, passwords
- Logs, sessions, cache, state databases
- Personal daily notes, private memory stores, output archives, transcripts, and runtime scratch data

Before every push, run a secret scan and inspect `git status`/`git diff`.
