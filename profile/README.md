# Mindot

**AI that matters in the real world needs two things: a mind that persists, and
a world it can safely act on. Mindot builds both.**

Every autonomous operation needs three properties — Automation / Intelligence /
Determinism (AID) — and each has a home here:

| | The question it answers | What answers it |
| :--- | :--- | :--- |
| **Automation** | *What happens next?* | **Ripplix** — the agentic backbone: scheduler, deadline watcher, command router |
| **Intelligence** | *What should happen?* | **Will** — a persistent mind, with the safety modules around it |
| **Determinism** | *What actually happened?* | **VLX** — an append-only, hash-chained, independently verifiable ledger |

---

## For builders

### Will — the open-source engine for persistent machine minds

[**mindot-labs/will**](https://github.com/mindot-labs/will) · Apache-2.0 ·
[releases](https://github.com/mindot-labs/will/releases)

A Will is a continuously-ticking synthetic mind with energy, moods, memory, goals
and relationships that persist. The LLM is one component of its cognition, not
the substrate — most ticks resolve on the engines alone, without inference.

- **40+ cognitive engines** on a deterministic tick clock — regulation, perception,
  affect, memory consolidation, planning, metacognition, social cognition
- **A learning agency pipeline** — actions are *found in the situation*, enacted,
  and proceduralised into skills the mind owns
- **PMA (Persistent Mind Artifact)** — distill a mind, kill the process, restore
  it: identity and relationships survive
- **Deterministic and provable** — same seed + same inputs = the same mind, byte
  for byte; its records are hash-chained and anchored outside the operator, and
  `will verify --replay` re-derives what it did
- **Four ways in** — TypeScript SDK · a persistent mind in Claude Desktop via MCP ·
  MCP tools as its abilities · an HTTP sidecar (`will serve`) for any language

Try a mind in 60 seconds, **no API key** (deterministic mock executive — zero cost):

```bash
git clone https://github.com/mindot-labs/will && cd will
bun install
bun run examples/hello-will.ts
```

Companions that reach out first · NPCs that remember what you did three sessions
ago · assistants that notice before you ask. If your product needs *presence*
rather than answers, it needs a mind that keeps running when nobody is talking
to it.

### Mindot Cloud — minds, hosted

Durable, metered, always-on Wills — snapshots and recovery, realtime streams,
and Studio, a console that lets you look inside their minds — at
[**mindot.io**](https://mindot.io). **The engine stays open; housing minds is
the business.**

---

## For operations

Infrastructure that makes a business's operational reality deterministic,
reversible and auditable, so autonomous agents — and the people above them —
can safely run it. Enterprise-grade is the quality bar, not the customer size.

- **Ripplix, by Mindot** — the agentic backbone. Its foundation (AB) records
  every change as an event, answers blast-radius queries over what depends on
  what, and corrects by compensation, never by overwrite. Its authority layer
  (CA) stands between a mind and the business: every decision and outcome on
  the record.
- **VLX — Verifiable Ledger eXecution** — the log of record beneath it:
  append-only, hash-chained, verifiable by anyone without trusting the
  operator. Ripplix writes business events to it; Will anchors its decisions
  to it.
- **[Cosense, by Mindot](https://github.com/co-sense)** — the operable system: an
  enterprise resource system on the AID kernel, run by Mindot on Mindot Cloud.

Ripplix, VLX and Cosense are in build, and their repositories are private.

---

*Naming: the company is **Mindot**. The entity you create is a **Will**. The
engine is `@mindot/will`.*
