# Mindot

**Persistent machine minds.**

Today's AI agents are stateless labor: a prompt goes in, work comes out, and nothing
remains. A **Will** is different — a continuously-ticking synthetic mind with energy,
moods, memory, goals, and relationships that persist. The LLM is one component of its
cognition, not the substrate.

## Will — the open-source engine

[**mindot-ai/will**](https://github.com/mindot-ai/will) · Apache-2.0 · [v0.1.0](https://github.com/mindot-ai/will/releases)

- **40+ cognitive engines** on a deterministic tick clock — regulation, perception,
  affect (~25 continuous dials), memory consolidation, planning, metacognition
- **A learning agency pipeline** — actions are found in the situation, enacted, and
  proceduralised into skills
- **PMA (Persistent Mind Artifact)** — distill a mind, kill the process, restore it:
  identity and relationships survive. Version control for a self
- **Deterministic core** — same seed + same inputs = same mind

Try a mind in 60 seconds, **no API key**:

```bash
git clone https://github.com/mindot-ai/will && cd will
bun install
bun run examples/hello-will.ts
```

## The hosted platform

Running a fleet of durable, metered, always-on Wills — snapshots, recovery, realtime
streams, a studio to look inside their minds — is what **[mindot.io](https://mindot.io)**
does. The engine stays open; housing minds is the business.

---

*Naming: the company is Mindot. The entity you create is a Will. The engine is `@mindot/will`.*
