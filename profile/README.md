# 𓉸 Cellar Door — Passage Protocol

**Passport stamps for AI.** Cryptographic departure and admission records for AI agents.

When an agent leaves a platform, EXIT creates a signed receipt. When it arrives somewhere new, ENTRY verifies, applies policy, and counter-signs. Together: the Passage Protocol.

```bash
npm install cellar-door-exit cellar-door-entry
```

```javascript
const { marker } = await quickExit("did:web:platform.example");
// → signed, verifiable proof of departure
```

## Core

| Package | Description |
|---------|-------------|
| **[cellar-door-exit](https://github.com/CellarDoorExits/exit-door)** | EXIT markers, ceremonies, crypto |
| **[cellar-door-entry](https://github.com/CellarDoorExits/entry-door)** | ENTRY admission, policy engine, verification |
| **[@cellar-door/attestation-core](https://github.com/CellarDoorExits/attestation-core)** | Shared hashing for on-chain adapters |

## Framework Integrations

| Package | Description |
|---------|-------------|
| **[@cellar-door/mcp-server](https://github.com/CellarDoorExits/mcp-server)** | MCP integration (Claude, Cursor, Windsurf) |
| **[@cellar-door/langchain](https://github.com/CellarDoorExits/langchain)** | LangChain tools + callback handler |
| **[@cellar-door/vercel-ai-sdk](https://github.com/CellarDoorExits/vercel-ai-sdk)** | Vercel AI SDK middleware + tools |
| **[@cellar-door/eliza](https://github.com/CellarDoorExits/eliza-exit)** | Eliza agent framework plugin |

## On-Chain Adapters

| Package | Description |
|---------|-------------|
| **[@cellar-door/eas](https://github.com/CellarDoorExits/eas-adapter)** | Ethereum Attestation Service (Base L2) |
| **[@cellar-door/erc-8004](https://github.com/CellarDoorExits/erc-8004-adapter)** | ERC-8004 SBT reputation tokens (13 chains) |
| **[@cellar-door/sign-protocol](https://github.com/CellarDoorExits/sign-protocol-adapter)** | Sign Protocol attestations |

## Python SDKs

| Package (PyPI) | Description |
|----------------|-------------|
| **[exit-door](https://github.com/CellarDoorExits/exit-python)** | Python EXIT core |
| **[entry-door](https://github.com/CellarDoorExits/entry-door-python)** | Python ENTRY admission + policy engine |
| **[exit-door-langchain](https://github.com/CellarDoorExits/cellar-door-langchain-python)** | Python LangChain handler |

## Other

| Repo | Description |
|------|-------------|
| **[openclaw-skill](https://github.com/CellarDoorExits/openclaw-skill)** | OpenClaw agent skill |

## Numbers

- **1,401** passing tests across 13 packages
- **14** public repositories
- **~335 bytes** per signed marker
- **Sub-millisecond** ceremony timing
- **TypeScript + Python**
- **0** VC dollars · **1** developer

## Links

**[Website](https://cellar-door.dev)** · **[Paper](https://cellar-door.dev/paper/)** · **[The Story](https://cellar-door.dev/story/)** · **[NIST Submission](https://cellar-door.dev/nist/)** · **[Policy Briefs](https://cellar-door.dev/briefs/)**

Submitted to NIST AI Agent Standards Initiative, March 2026. Apache 2.0. *There's always a door.*
