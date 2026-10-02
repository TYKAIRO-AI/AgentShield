# 🛡️ AgentShield

> **A TYKAIRO AI product** — Founded by **Mahmoud Hisham**

**Evidence-based security inspection for AI Skills and MCP servers — before you trust them.**

[![Product](https://img.shields.io/badge/product-AgentShield-informational)](#what-agentshield-inspects)
[![MCP Security](https://img.shields.io/badge/MCP-security-informational)](#what-agentshield-inspects)
[![TYKAIRO AI](https://img.shields.io/badge/by-TYKAIRO%20AI-informational)](https://github.com/TYKAIRO-AI)

AI Skills and MCP servers can interact with files, commands, dependencies, credentials, environment variables, and external services. AgentShield helps developers inspect that risk surface before installing or connecting third-party agent tooling.

## Start with the free Lite inspector

Want to try the idea first?

➡️ **[AgentShield MCP Inspector Lite](https://github.com/TYKAIRO-AI/AgentShield-MCP-Inspector)** is the free public edition for basic MCP tool-metadata and schema inspection.

Use Lite to inspect MCP capability signals and receive explainable `SAFE`, `REVIEW`, and `HIGH RISK` verdicts.

## What AgentShield inspects

- Risky scripts and command-execution indicators
- File-system access and permission exposure
- Dependencies and lifecycle/install scripts
- Network endpoints and potential outbound-data paths
- Credentials, secrets, and environment-variable access
- MCP configuration, tools, and schemas
- Prompt-injection and suspicious instruction patterns
- Obfuscated or suspicious code indicators
- Integrity changes using file fingerprints
- Security-relevant changes between package versions

## Evidence, not a “safe / unsafe” badge

AgentShield produces findings with context and evidence rather than claiming that a package is absolutely safe or malicious.

## Local-first approach

The product is designed around local inspection and minimizing unnecessary exposure of source code during analysis.

## Example report

See [docs/SAMPLE-REPORT.md](docs/SAMPLE-REPORT.md).

## Product availability

**AgentShield is a commercial product. This repository is documentation-only.**

The scanner implementation, detection rules, paid Skill package, and production configuration are intentionally **not included** in this public repository.

➡️ **Get AgentShield:** https://capafy.ai/agent/agentshield-ai-skill-mcp-security-scanner/1745400974

## Public ecosystem

- [AgentShield MCP Inspector Lite](https://github.com/TYKAIRO-AI/AgentShield-MCP-Inspector) — free public MCP inspection project
- [TYKAIRO AI](https://github.com/TYKAIRO-AI) — organization and related AI/MCP products

If you are evaluating the project publicly, star the Lite repository so other MCP developers can discover the free tool.

## Responsible positioning

AgentShield is a risk-inspection tool. A finding is not, by itself, proof that software is malicious, and absence of findings is not a guarantee of security.

## Ownership

**Developer / Publisher:** Mahmoud Hisham  
**Organization:** TYKAIRO AI  
**Product:** AgentShield  
**Copyright © 2026 Mahmoud Hisham. All rights reserved.**

This public repository provides product documentation only. No rights to the proprietary AgentShield implementation, paid package, detection rules, or commercial assets are granted by publication of this repository.

---

**Scan first. See the evidence. Understand the risk. Then decide.**
