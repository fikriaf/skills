# Daemon Protocol — Agent Skills

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Node.js](https://img.shields.io/badge/Node.js-339933?logo=node.js&logoColor=white)](https://nodejs.org)

A collection of [Daemon Protocol](https://daemonprotocol.com) agent skills for security, privacy, and blockchain intelligence.

## Install a skill

```bash
npx skills add ares-system/skills --skill <skill-name>
```

Install all skills at once:

```bash
npx skills add ares-system/skills --all
```

## Available skills

| Skill | Description |
|---|---|
| [ares-system](./ares-system/) | AI-powered security platform with 8 tools: Trident (Solana fuzzing), Semgrep, FuzzyAI, HexStrike, Whistleblower, Checked Math, MCP Injection, Multi-Agent orchestration |
| [cyclops](./cyclops/) | Cryptocurrency wallet risk analysis — sanctions screening (OFAC), AML/KYC, blockchain graph analysis, entity labeling for Solana, BTC, and more |
| [daemon-intelligence](./daemon-intelligence/) | Daemon-AI platform API — auth, chat completions, MCP tools, finance, blockchain intelligence |
| [obscura-privacy](./obscura-privacy/) | Post-quantum secure privacy vault — Arcium MPC confidential computing, ZK compression (Light Protocol), WOTS+ signatures, stealth addresses |

## Usage examples

```bash
# Install all skills
npx skills add ares-system/skills --all

# Install a specific skill
npx skills add ares-system/skills --skill cyclops
```

## License

This project is licensed under the MIT License — see [LICENSE](LICENSE) for details.
