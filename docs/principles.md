# Principles

Status: Living document

These principles govern every Product Intelligence Sprint. They apply to humans and AI assistants alike.

---

## Evidence over assumptions

Start from what can be verified. Assumptions are allowed — they must be labeled, linked to evidence where possible, and revisitable.

Prefer primary sources: filings, changelogs, product pages, job posts, earnings transcripts, and firsthand product use. Secondary summaries are pointers, not substitutes.

## Separate facts from inferences

| Layer | Definition | How to write it |
|-------|------------|-----------------|
| **Fact** | Verifiable claim with a source | State plainly; cite artifact or URL |
| **Observation** | Something noticed during research | Describe what was seen; avoid premature interpretation |
| **Inference** | Conclusion drawn from facts and observations | Label as inference; list supporting evidence IDs |
| **Hypothesis** | Testable claim about future behavior or strategy | Register in hypothesis-register; note confidence and falsifiers |

Do not upgrade a hypothesis into a fact by rewriting tone. Do not bury an inference inside a bullet that reads like reporting.

## Document uncertainty

Uncertainty is signal, not noise.

- Use confidence labels: `high`, `medium`, `low`, `unknown`
- Keep open questions visible — do not resolve them by omission
- Record competing hypotheses when evidence supports more than one reading
- Note when evidence is stale, indirect, or single-sourced

A sprint with unanswered questions is healthier than a sprint that sounds complete.

## Preserve continuity

Research spans weeks and months. Continuity means the next session can resume without reconstructing context.

- Date every session and significant edit
- Maintain registers (evidence, hypotheses, opportunities) as durable indexes
- Link forward and backward: evidence → hypothesis → opportunity → session notes
- Changelog meaningful shifts in the company brief
- When pausing, leave explicit next actions — not implicit todos

Git history is versioning. Registers and briefs are the working memory.

## Iterative synthesis

Synthesis is not a final report. It is repeated compression of learning as evidence accumulates.

- Synthesize after evidence clusters — not after every source
- Update brief sections when registers change materially
- Cross-company patterns belong in [research/](../research/), linked from company briefs
- Retire or revise hypotheses when contradicted — do not delete the history

Each synthesis pass should make the repository more useful for the *next* decision, not just the current one.

---

## What this system is not

- **Not interview preparation** — optimize for discovery, not performance
- **Not a pitch factory** — packaging is downstream of understanding
- **Not style-first writing** — clarity yes; cosmetic rewrites no

---

## Related documents

| Document | Role |
|----------|------|
| [methodology.md](methodology.md) | How evidence flows through registers and synthesis |
| [workflow.md](workflow.md) | Session rhythm and long-running project operations |
| [ai-collaboration.md](ai-collaboration.md) | Maintainer rules for AI assistants |
