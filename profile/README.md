# 𓉸 Cellar Door — EXIT Protocol

**Vehicle registration for AI.** Cryptographic departure and arrival records for AI agents.

When an agent leaves a platform, it gets a signed receipt (~660 bytes). When it arrives somewhere new, that receipt can be verified. Think of it as passport stamps for AI agents.

```bash
npm install cellar-door-exit
```

```javascript
const { marker } = await quickExit("did:web:platform.example");
// → signed, verifiable proof of departure in one line
```

## Packages

| Package | What it does | Install |
|---------|-------------|---------|
| **[cellar-door-exit](https://github.com/CellarDoorExits/exit-door)** | Core protocol. Departure markers. | `npm i cellar-door-exit` |
| **[cellar-door-entry](https://github.com/CellarDoorExits/entry-door)** | Arrival markers + admission policies. | `npm i cellar-door-entry` |
| **[@cellar-door/mcp-server](https://github.com/CellarDoorExits/mcp-server)** | MCP integration (Claude, Cursor, Windsurf). | `npm i @cellar-door/mcp-server` |
| **[@cellar-door/langchain](https://github.com/CellarDoorExits/langchain)** | LangChain integration. | `npm i @cellar-door/langchain` |
| **[@cellar-door/vercel-ai-sdk](https://github.com/CellarDoorExits/vercel-ai-sdk)** | Vercel AI SDK integration. | `npm i @cellar-door/vercel-ai-sdk` |
| **[@cellar-door/openclaw-skill](https://github.com/CellarDoorExits/openclaw-skill)** | OpenClaw agent skill. | `npm i @cellar-door/openclaw-skill` |

## Numbers

- **592** passing tests across 6 repos
- **~660 bytes** per signed marker
- **Sub-millisecond** performance
- **0** VC dollars
- **1** developer

## Links

**[Website](https://cellar-door.dev)** · **[Paper](https://cellar-door.dev/paper/)** · **[The Story](https://cellar-door.dev/story/)** · **[NIST Submission](https://cellar-door.dev/nist/)** · **[Policy Briefs](https://cellar-door.dev/briefs/)**

Submitted to NIST on March 6, 2026. Open source, Apache 2.0. *There's always a door.*
