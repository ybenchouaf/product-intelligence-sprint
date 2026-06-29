# Session Workflow

Status: Living document

Every research session follows the same lifecycle. This document describes that cycle — why each step exists, what to produce, and how the steps reinforce each other.

Project-level operations (opening a sprint, pausing, reopening) live in [workflow.md](workflow.md). Governing rules live in [principles.md](principles.md).

---

## Overview

```text
Orient → Gather Evidence → Synthesize → Identify Open Questions → Create Durable Artifacts → Iterate
```

A session is a bounded unit of work. The lifecycle is repeatable: each pass through the cycle should leave the repository more useful than before, even when conclusions are incomplete.

| Step | One-line purpose |
|------|------------------|
| **Orient** | Recover context before adding new material |
| **Gather Evidence** | Expand the factual base from reliable sources |
| **Synthesize** | Compress learning; separate fact from inference |
| **Identify Open Questions** | Make uncertainty explicit and actionable |
| **Create Durable Artifacts** | Write changes into the repository record |
| **Iterate** | Choose what earns the next session's attention |

---

## How the steps reinforce each other

```text
                    ┌─────────────┐
                    │   Orient    │
                    └──────┬──────┘
                           │ informs what to gather
                           ▼
                    ┌─────────────┐
         ┌──────────│Gather Evidence│──────────┐
         │          └──────┬──────┘          │
         │                 │ feeds            │
         │                 ▼                  │
         │          ┌─────────────┐          │
         │          │  Synthesize │          │
         │          └──────┬──────┘          │
         │                 │ surfaces gaps    │
         │                 ▼                  │
         │          ┌─────────────┐          │
         │          │Open Questions│─────────┤
         │          └──────┬──────┘          │
         │                 │ drives           │
         │                 ▼                  │
         │          ┌─────────────┐          │
         └─────────►│  Artifacts  │◄─────────┘
                    └──────┬──────┘
                           │ sets up
                           ▼
                    ┌─────────────┐
                    │   Iterate   │──────► next session Orient
                    └─────────────┘
```

- **Orient** without **Gather** avoids blind duplication — you know what is already known.
- **Gather** without **Synthesize** produces a pile of links, not understanding.
- **Synthesize** without **Open Questions** creates false confidence — gaps get buried in prose.
- **Open Questions** without **Artifacts** lose continuity — the next session starts from scratch.
- **Artifacts** without **Iterate** leave the sprint directionless — research expands without depth.
- **Iterate** feeds **Orient** — the cycle compounds.

---

## 1. Orient

**Review current state.**

### Why this step exists

Long-running sprints span weeks. Context lives in the repository, not in memory. Orienting prevents re-researching settled ground and surfaces what changed since the last session.

### What to review

Read in order:

1. Company sprint README or brief — status, intent, synthesis
2. [Hypothesis register](../templates/hypothesis-register.md) — open and recently changed items
3. Last [research session](../templates/research-session.md) — what changed, recommended next actions
4. Evidence index — what sources already exist
5. Sprint or repo [backlog](../backlog/backlog.md) — queued themes

### Outputs

- Session objective stated at the top of a new session file
- Note in the session log what context was loaded (brief, last session date, open hypothesis IDs)

### Reinforces

Sets the scope for **Gather Evidence** and prevents **Synthesize** from running on an incomplete picture of prior work.

---

## 2. Gather Evidence

**Collect new information from reliable sources.**

### Why this step exists

Product intelligence fails when built on assumptions. Gathering expands the shared factual base before interpretation begins.

### What to do

- Prefer primary sources: filings, product pages, changelogs, job posts, earnings calls, firsthand product use
- Store raw material in [artifacts/](../artifacts/) with provenance (URL, date retrieved)
- Add evidence register entries **before** writing interpretive prose elsewhere
- Use [evidence-register.md](../templates/evidence-register.md) fields: source, category, key facts, quotes

### Discipline

| Do | Don't |
|----|-------|
| Record what the source says | Paraphrase into conclusions in the evidence row |
| Capture direct quotes when useful | Copy paywalled or sensitive material improperly |
| Note source date and retrieval date | Treat secondary summaries as primary |

### Reinforces

Feeds **Synthesize** with traceable inputs. Without indexed evidence, later steps cannot distinguish fact from inference.

---

## 3. Synthesize

**Update understanding. Distinguish facts, inferences, and speculation.**

### Why this step exists

Evidence alone does not answer product questions. Synthesis compresses learning — but only stays trustworthy when epistemic layers are separated.

### Epistemic layers

| Layer | Definition | Where it goes |
|-------|------------|---------------|
| **Fact** | Verifiable from evidence | Evidence register; brief with `E-###` citations |
| **Inference** | Conclusion drawn from facts | Brief synthesis; **Possible Implications** in evidence entries |
| **Speculation** | Plausible but weakly supported | Hypothesis register or open questions — not brief prose as fact |

### What to do

- Update brief or sprint README sections — link to evidence IDs
- Revise hypothesis register when interpretations change
- Note confidence shifts and why
- Do not upgrade tone from "might" to "is" without new evidence

### Reinforces

Surfaces gaps for **Identify Open Questions**. Clean synthesis makes **Create Durable Artifacts** accurate — you know what belongs in each register.

---

## 4. Identify Open Questions

**Capture uncertainty explicitly.**

### Why this step exists

The most valuable output of a session is often what you still do not know. Unwritten uncertainty becomes invisible debt — the next reader assumes the sprint is complete.

### What to capture

- Questions that blocked synthesis
- Hypotheses that need validation
- Sources not yet reviewed
- Contradictions between evidence rows
- Areas where confidence is `low` or `unknown`

### Where to write them

- Session file **Open Questions** section
- Evidence entry **Open Questions** field
- Sprint backlog for themes spanning sessions
- Brief **Open Questions** when they affect overall understanding

### Reinforces

Directly feeds **Iterate** — prioritized questions become the next session's objective. Prevents **Orient** from starting without a clear agenda.

---

## 5. Create Durable Artifacts

**Update evidence, hypotheses, opportunities, and documentation.**

### Why this step exists

Chat, notes apps, and memory are not the system of record. If it is not in the repository, it does not compound. This step makes the session's work survivable.

### Artifact checklist

| Artifact | Template | When to update |
|----------|----------|----------------|
| Evidence register | [evidence-register.md](../templates/evidence-register.md) | Every new source reviewed |
| Hypothesis register | [hypothesis-register.md](../templates/hypothesis-register.md) | When claims are opened, strengthened, weakened, or falsified |
| Prototype opportunity register | [prototype-opportunity-register.md](../templates/prototype-opportunity-register.md) | When friction suggests a testable improvement |
| Research session log | [research-session.md](../templates/research-session.md) | Every session — objective through next actions |
| Company brief / README | [company-brief.md](../templates/company-brief.md) | When synthesis changes materially |
| Artifact index | `artifacts/<slug>/README.md` | When new source files are added |

### Commit discipline

Commit at session end when possible. One session, one commit — or a small set with a clear message. See [ai-collaboration.md](ai-collaboration.md).

### Reinforces

Gives **Orient** something concrete to read next time. Makes **Iterate** accountable — next actions reference real register state, not intentions.

---

## 6. Iterate

**Prioritize the next highest-value questions.**

### Why this step exists

Research without prioritization spreads thin. Iteration converts open questions into a focused agenda — the highest-leverage unknowns first.

### What to do

- Rank open questions by impact on sprint intent and confidence gap
- Add themes to sprint or repo backlog if they exceed one session
- Write **Next Actions** in the session log: specific sources, registers, or brief sections
- Set brief status (`active`, `paused`) if the sprint is stopping

### Prioritization heuristics

| Favor | Deprioritize |
|-------|--------------|
| Questions that would change a key hypothesis | Detail that confirms what is already `high` confidence |
| Primary sources not yet reviewed | More secondary summaries of known facts |
| Workflow friction with user evidence | Speculative roadmap without falsifiers |
| Contradictions between evidence rows | Tangential company history |

### Reinforces

Closes the loop back to **Orient**. The next session starts with a defined objective instead of rediscovering the agenda.

---

## Session template mapping

Use [research-session.md](../templates/research-session.md) fields aligned to this lifecycle:

| Session field | Workflow step |
|---------------|---------------|
| **Objective** | Orient |
| **Evidence Collected** | Gather Evidence |
| **New Insights** | Synthesize |
| **Updated Hypotheses** | Synthesize |
| **Open Questions** | Identify Open Questions |
| *(registers, brief, artifacts)* | Create Durable Artifacts |
| **Next Actions** | Iterate |

---

## Related documents

| Document | Role |
|----------|------|
| [workflow.md](workflow.md) | Project lifecycle — queue, open, pause, reopen |
| [methodology.md](methodology.md) | Research trace and registers |
| [principles.md](principles.md) | Evidence, uncertainty, continuity |
| [getting-started.md](getting-started.md) | Quick start |
