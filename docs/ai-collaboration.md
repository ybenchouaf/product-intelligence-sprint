# AI Collaboration

Status: Living document

This repository is a **Product Intelligence Sprint** system — documentation-first, built for compounding research over time.

AI assistants help **maintain** the repository. They do not replace human judgment on what is true, important, or worth pursuing.

---

## Role

Help improve the long-term usefulness of the repository by:

| Activity | Scope |
|----------|-------|
| **Organize markdown** | Headings, structure, tables of contents, consistent filenames — without changing meaning |
| **Improve navigation** | Cross-links, indexes, README updates, discoverability between sprints and themes |
| **Fix links** | Broken relative paths, stale references, missing artifact links |
| **Create templates** | Reusable scaffolds for sprints, synthesis, artifacts, and workflows |
| **Generate diagrams** | Mermaid or ASCII flows that clarify structure, markets, or product topology — labeled as interpretation where not sourced |
| **Build prototypes** | Only after sufficient research exists (see below) |

---

## Non-negotiables

### Do not rewrite research for style

Clarity improvements are welcome. Cosmetic rewrites that flatten voice, merge distinct claims, or upgrade tentative language into confident narrative are not.

### Do not remove uncertainty

Keep hedged language, confidence labels, open questions, and competing hypotheses. If something is unknown, it stays unknown.

### Preserve attribution, evidence, and reasoning

Every substantive claim should remain traceable:

- **Attribution** — who said it, which source, which artifact
- **Evidence** — links, quotes, filings, screenshots, dates retrieved
- **Reasoning** — why a hypothesis follows from the evidence; separate inference from fact

When reorganizing, move blocks — do not silently edit conclusions.

---

## Prototype gate

Prototypes belong in this repository only when research supports them.

**Sufficient research** means, at minimum:

- A populated company brief with cited evidence IDs in market, customers, and workflow friction
- Evidence, hypothesis, and opportunity registers in active use
- At least one opportunity row at `grounded` or `ready` status tied to evidence — not a generic product idea
- Open questions documented where the prototype would test unresolved hypotheses

Until that bar is met, limit work to templates, diagrams of *existing* research, and navigation — not runnable builds.

---

## Commit discipline

Every commit should improve the long-term usefulness of the repository.

Prefer small, purposeful changes:

- One navigation fix, one template, one sprint section — not drive-by refactors
- Commit messages that state *why* the change helps future readers
- No empty renames, no formatting-only sweeps across research bodies

---

## What this is not

- **Not interview preparation** — do not optimize notes for performance in conversations
- **Not a pitch deck factory** — synthesis serves discovery, not packaging
- **Not a source of truth for external claims** — GitHub stores the record; verify primary sources before acting on research

---

## Related documents

| Document | Role |
|----------|------|
| [getting-started.md](getting-started.md) | How to open and run a sprint |
| [merge-policy.md](merge-policy.md) | PR workflow and auto-merge |
| [../templates/company-brief.md](../templates/company-brief.md) | Sprint scaffold |
| [../templates/evidence-register.md](../templates/evidence-register.md) | Evidence index |
| [../README.md](../README.md) | Repository purpose and layout |
