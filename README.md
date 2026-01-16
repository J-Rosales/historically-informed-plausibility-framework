# historically-informed-plausibility-framework

A setting-agnostic framework for producing and auditing **historically-informed narrative plausibility**.

This repository provides:
- a **constitution** (structural guardrails)
- **policy models** (e.g., belief regimes)
- **validators** (plausibility checklists and failure modes)
- **templates** for corpus documents, cultures, timelines, and periodization
- optional **lenses** (reusable modifiers, e.g., species-level constraints)

It intentionally contains **no setting-specific history**.
A world-specific repository (e.g., a particular setting’s corpus, timeline, cultures, calendar) should import or mirror these documents and apply them to its own data.

## Layout
- `constitution/` — narrative plausibility guardrails
- `validators/` — reusable plausibility audits and structural checks
- `templates/` — document skeletons
- `lenses/` — optional reusable constraint modules
- `AGENT_MODE_CONTRACT.md` — operational contract for an assisting agent
- `BELIEF_REGIME_MODEL.md` — policy for modeling belief systems outside diegetic text
