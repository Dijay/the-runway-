# The Runway
### A Field Thesis on the Enterprise AI Control Plane

*Dijay Jadiya · Client Partner & Banking Portfolio Lead · Slalom Canada · 2026*

---

> The infrastructure has to exist before the intelligence can scale.

---

## What is this

Most enterprise AI programs in 2026 are operating one layer too high.

Agents are being deployed before orchestration is fully defined. Models are being evaluated with frameworks built for deterministic software. Data platforms are scaling before the governance layer makes them trustworthy enough to run AI on top of. The infrastructure that needs to exist before any of it can scale safely — the AI Control Plane — tends to be the last thing funded and the first constraint felt when programs stall.

This is a familiar cycle. In 2012, shadow IT proliferated faster than cloud governance could catch it. The organizations that built the landing zone first owned the architecture of the next decade. Today a similar dynamic is playing out at a different order of magnitude and a much faster clock. Shadow AI is quietly becoming the new shadow IT. The AI Control Plane is the new cloud landing zone.

**The Runway** is a working field thesis on what the foundational infrastructure actually requires — the orchestration, governance, and trust layers that determine whether autonomous AI can safely take action across an enterprise. It is built from client conversations, not a whiteboard. It is a living document, not a finished one. The market is moving fast and the thinking moves with it.

---

## What is in here

| File | Format | Description |
|------|--------|-------------|
| [The Runway](https://dijay.github.io/the-runway-/) | HTML | The Runway — full designed experience |
| [the-runway.md](./the-runway.md) | Markdown | Plain text version for readability and search |
| [LICENSE.md](./LICENSE.md) | Markdown | CC BY 4.0 — share and adapt with attribution |
---

## The architecture

The Runway covers eight layers of the enterprise agentic AI stack — from the foundational data and compute layer through to the agent experience layer — and identifies the specific gaps most regulated institutions are carrying right now.

The layers that receive the most attention are the ones that are most commonly skipped:

**AI Gateway** — the entry point that governs how models are accessed, authenticated, and rate-limited across the enterprise. Most organizations have models. Few have a governed gateway sitting in front of them.

**Model Registry** — the version control and lineage layer for models in production. Without it, nobody knows which model is running where, on what data, under what governance policy.

**MCP Gateway & Agent Identity** — the Model Context Protocol layer that allows agents to securely authenticate and pull context from enterprise systems on behalf of users. The critical missing piece as autonomous agents move from reasoning to action.

**LLM Evaluation Infrastructure** — the behavioral evaluation layer that replaces traditional deterministic testing. You cannot test a language model the way you test traditional software. You have to evaluate its behavior across a distribution of inputs and contexts.

**Agent Identity & Entitlement** — the IAM layer for non-human agents. An agent acting on behalf of a user is not the same as the user acting. The permissions, the audit trail, and the accountability structure are fundamentally different.

---

## Who this is for

Financial services technology leaders navigating the gap between AI pilots and AI programs at scale.

AI lab and infrastructure teams building the enterprise deployment motion for frontier models.

Engineering leaders responsible for making autonomous AI safe enough to run inside a regulated institution.

Anyone asking why their AI program is moving slower than expected — and suspecting the answer is not the model.

---

## The sequencing argument

The central argument of The Runway is about sequencing, not technology.

Every major technology wave has had a foundational infrastructure moment that preceded the application layer. Cloud had the landing zone. Data had the lakehouse. AI has the Control Plane. The organizations that invest in the infrastructure layer now will have options that the ones who skipped it will not.

Build the runway before you fly the plane.

---

## About the author

Twenty plus years in technology consulting across the Fortune 100 — spanning RBC Capital Markets, Publicis Sapient, IBM, and Slalom — spent finding the layer that has to exist before everything else can work and building it before the market had a name for it.

National payment infrastructure ahead of a regulatory window. ML in production before standard governance models existed. Search intelligence over unstructured data before the category arrived. Today that means architecting the orchestration, governance, and trust layers that determine whether autonomous AI can safely take action across an enterprise.

The fluency required runs three ways: deep enough in architecture to design what needs to be built, commercial enough to build a sustainable market around it, and present enough with teams and clients to earn the trust that gives any of it permission to move.

**LinkedIn:** [linkedin.com/in/dijayjadiya](https://linkedin.com/in/dijayjadiya)

---

## Using this work

This work is published under [Creative Commons Attribution 4.0 International (CC BY 4.0)](./LICENSE.md).

You are free to share and adapt this material for any purpose, including commercial use, as long as you give appropriate credit to the author and indicate if changes were made.

If this thinking is useful to what you are building, a conversation is worth more than a citation. Reach out directly.

---

*The Runway · Dijay Jadiya · Slalom Canada · 2026*
*A living document. Last updated June 2026.*
