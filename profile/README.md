# Mindot

**Persistent machine minds.**

Today's AI agents are stateless labor: a prompt goes in, work comes out, and nothing
remains. A **Will** is different — a continuously-ticking synthetic mind with energy,
moods, memory, goals, and relationships that persist. The LLM is one component of its
cognition, not the substrate — most ticks resolve on the engines alone, without
inference.

## Will — the open-source engine

[**mindot-ai/will**](https://github.com/mindot-ai/will) · Apache-2.0 ·
[releases](https://github.com/mindot-ai/will/releases)

- **40+ cognitive engines** on a deterministic tick clock — regulation, perception,
  affect (eight evaluators blended into a live signal), memory consolidation, planning,
  metacognition, social cognition
- **A learning agency pipeline** — actions are *found in the situation*, enacted, and
  proceduralised into composite skills the mind owns
- **PMA (Persistent Mind Artifact)** — distill a mind, kill the process, restore it:
  identity and relationships survive. Version control for a self
- **Deterministic core** — same seed + same inputs = the same mind, byte for byte;
  replay *is* the audit trail
- **Four ways in** — TypeScript SDK · a persistent mind in Claude Desktop via MCP ·
  MCP tools as its abilities · an HTTP sidecar (`will serve`) for any language

Try a mind in 60 seconds, **no API key** (deterministic mock executive — zero cost):

```bash
git clone https://github.com/mindot-ai/will && cd will
bun install
bun run examples/hello-will.ts
```

## What people build with it

Companions that reach out first · NPCs that remember what you did three sessions ago ·
assistants that notice before you ask. If your product needs *presence* rather than
answers, it needs a mind that keeps running when nobody is talking to it.

## The hosted platform

Running a fleet of durable, metered, always-on Wills — snapshots and recovery, realtime
streams, a studio that lets you look inside their minds — is what
[**mindot.io**](https://mindot.io) does. **The engine stays open; housing minds is the
business.**

---

*Naming: the company is **Mindot**. The entity you create is a **Will**. The engine is
`@mindot/will`.*
