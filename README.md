# hermes-manager

Hermes Manager / Termy setup for Jet's AI team orchestration.

## Current role

Termy is the main Hermes bot and AI team orchestrator. It coordinates specialist agents for:

- Thai content/copywriting
- Thai long-form/book content
- Data and source-grounded research
- Local tools, automation, and GitHub workflows

## Local model note

Ollama is installed locally and `qwen3:8b` has been pulled and tested as a local fallback model. The main Termy processing model remains GPT-5.5 unless explicitly changed.

## Security note

This repository intentionally does **not** include local Hermes secrets, tokens, `.env` files, profiles with credentials, or private runtime state.
