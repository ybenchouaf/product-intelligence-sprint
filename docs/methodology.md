# Methodology

Status: Living document

This document describes how Product Intelligence Sprint research compounds over time. Read [principles.md](principles.md) first for the governing rules.

---

## Research trace

All durable research should be traceable through this chain:

```text
Source → Evidence → Inference / Hypothesis → Synthesis → Opportunity
```

| Step | Meaning | Where it lives |
|------|---------|----------------|
| **Source** | Raw material — page, filing, screenshot, transcript | [artifacts/](../artifacts/) |
| **Evidence** | Indexed claim or observation tied to a source | `evidence-register.md` per company |
| **Inference / Hypothesis** | Interpreted or predictive claim | Brief sections + `hypothesis-register.md` |
| **Synthesis** | Compressed understanding across evidence | `brief.md`, [research/synthesis/](../research/synthesis/) |
| **Opportunity** | Testable product or workflow idea | `opportunity-register.md` |

The trace is rarely linear. New sources reopen old hypotheses. Opportunities surface friction that sends you back to evidence. Document links at each hop.

---

## Registers

Registers are the spine of long-running projects. They outlive individual sessions.

### Evidence register

Canonical index of facts and observations. Every substantive claim in the brief should trace to an evidence ID or be explicitly marked as inference.

See [templates/evidence-register.md](../templates/evidence-register.md).

### Hypothesis register

Testable claims about strategy, roadmap, customer behavior, or market structure. Each entry lists supporting and contradicting evidence.

See [templates/hypothesis-register.md](../templates/hypothesis-register.md).

### Opportunity register

Product or workflow ideas grounded in evidence and hypotheses. Entries stay dormant until the research bar for prototyping is met.

See [templates/opportunity-register.md](../templates/opportunity-register.md).

---

## Confidence and uncertainty

Use a consistent confidence scale across registers:

| Level | When to use |
|-------|-------------|
| **High** | Multiple independent primary sources agree; recent; directly observed |
| **Medium** | Reasonable source weight; some gaps or indirectness |
| **Low** | Single source, dated material, or heavy interpretation |
| **Unknown** | Insufficient evidence to estimate |

When confidence changes, update the register row and note why in the changelog or session log. Do not silently edit confidence in narrative prose alone.

---

## Synthesis rhythm

Synthesis is iterative, not terminal.

**After adding evidence** — check whether existing hypotheses need revision; add new rows rather than overwriting history.

**After revising hypotheses** — update relevant brief sections; link to hypothesis IDs.

**After identifying friction or gaps** — consider opportunity-register entries; mark speculative items as `exploratory`.

**Across companies** — when the same pattern appears in two or more sprints, draft a short note in [research/synthesis/](../research/synthesis/) and link from each company brief.

---

## Continuity mechanics

Long-running projects fail when context lives only in chat or memory. This system uses:

| Mechanism | Purpose |
|-----------|---------|
| **Company brief** | Stable narrative and section-level synthesis |
| **Registers** | Structured, queryable state |
| **Session logs** | Per-session delta — what changed and why |
| **Changelog** | Brief-level history of structural shifts |
| **Backlog** | Queued companies and themes |

When resuming after a pause, read in order: brief status → open hypotheses → last session → backlog next actions.

---

## Quality bar

Before treating a section of the brief as "done enough to act on":

- [ ] Key claims have evidence IDs or explicit inference labels
- [ ] Hypotheses list falsifiers or what would change your mind
- [ ] Open questions are written down, not implied
- [ ] Artifacts are indexed with provenance (URL, date retrieved)
- [ ] Opportunities cite evidence and hypotheses — not intuition alone

---

## Related documents

| Document | Role |
|----------|------|
| [workflow.md](workflow.md) | Operational steps for opening and running sprints |
| [principles.md](principles.md) | Governing rules |
| [getting-started.md](getting-started.md) | Quick start checklist |
