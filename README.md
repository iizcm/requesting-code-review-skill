---
title: Requesting Code Review - Skill
description: AI Agent Skill for pre-commit security scans, quality gates, auto-fix loops
---

# Requesting Code Review - Skill

[![License: MIT](https://img.shields.io/badge/license-MIT-blue?style=for-the-badge&logo=opensourceinitiative&logoColor=white)](LICENSE)
[![Universal AI Agent Skill](https://img.shields.io/badge/universal-AI_agent_skill-orange?style=for-the-badge&logo=artillery&logoColor=white)](#)
[![Category: Software Development](https://img.shields.io/badge/category-softwaredevelopment-purple?style=for-the-badge&logo=wix&logoColor=white)](#)

## Overview / Ringkasan

**English:**
A universal AI agent skill that enables your agent to handle **pre-commit security scans, quality gates, auto-fix loops**. Works with any AI agent platform (Hermes, Claude Code, OpenClaw, etc.).

**Bahasa Indonesia:**
Skill AI agent universal yang memungkinkan agen Anda menangani **pre-commit security scans, quality gates, auto-fix loops**. Bekerja dengan semua platform AI agent (Hermes, Claude Code, OpenClaw, dll).

## Installation / Instalasi

### Hermes Agent
```bash
hermes skills install https://raw.githubusercontent.com/iizcm/requesting-code-review-skill/main/SKILL.md --name requesting-code-review --yes
```

### Manual / Universal
Place `SKILL.md` in your agent's skills directory:
```
~/.<your-platform>/skills/requesting-code-review/SKILL.md
```

## Usage / Penggunaan

1. Load the skill in your agent (see platform-specific install above).
2. Refer to the `SKILL.md` file for usage instructions.
3. Adapt examples to your environment — placeholder values are marked `<LIKE_THIS>`.

## Token / API Safety

- **Never commit real secrets.** Use `<YOUR_API_KEY>`, `<YOUR_WALLET_ADDRESS>`, `<example.com>` in examples.
- Store credentials in `~/.<your-platform>/.env` with `chmod 600`.

## License

MIT — see [LICENSE](LICENSE).
