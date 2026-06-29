# Workflow

Status: Living document

Operational workflow for long-running Product Intelligence Sprint projects. Methodology lives in [methodology.md](methodology.md); rules live in [principles.md](principles.md).

---

## Project lifecycle

```text
Queue → Open → Research sessions → Synthesize → Pause or deepen → Cross-company synthesis
```

Projects are never truly "closed" — they pause when marginal learning drops, and reopen when new evidence or questions appear.

---

## 1. Queue

Add the company or theme to [backlog/backlog.md](../backlog/backlog.md) with a short rationale. Do not create a company folder until work is scheduled.

---

## 2. Open a company sprint

1. Create `companies/<company-slug>/` (lowercase, hyphenated slug)
2. Create matching `artifacts/<company-slug>/` with a `README.md` index
3. Copy templates into the company folder:

| Template | Destination |
|----------|-------------|
| [company-brief.md](../templates/company-brief.md) | `brief.md` |
| [evidence-register.md](../templates/evidence-register.md) | `evidence-register.md` |
| [hypothesis-register.md](../templates/hypothesis-register.md) | `hypothesis-register.md` |
| [opportunity-register.md](../templates/opportunity-register.md) | `opportunity-register.md` |

4. Create `companies/<company-slug>/sessions/`
5. Set brief status to `active` and record intent

Update backlog tables: move row from **Queued** to **In progress**.

---

## 3. Research session

A session is a bounded unit of work — typically one sitting or one focused theme.

1. Copy [session-template.md](../templates/session-template.md) to `sessions/YYYY-MM-DD-<topic>.md`
2. State session intent at the top
3. Gather sources into `artifacts/<company-slug>/`; index in artifact README
4. Add evidence rows before writing interpretive prose
5. Update hypothesis and opportunity registers when interpretations change
6. End with: what changed, what is uncertain, recommended next session

Commit at session end when possible. Small commits preserve continuity better than batch dumps.

---

## 4. Synthesize

After each session (or when evidence clusters):

- Update `brief.md` sections — link to evidence and hypothesis IDs
- Do not duplicate register tables in the brief; summarize and point
- Move resolved open questions to changelog or strike with date and reason
- File cross-company patterns in [research/synthesis/](../research/synthesis/)

---

## 5. Pause

When pausing:

- Set brief status to `paused`
- List explicit **next actions** in the brief and last session
- Move incomplete themes to open questions or backlog
- Update backlog **In progress** row or move to **Parked** with reason

Never delete partial work. Mark sections `draft` or `stub`.

---

## 6. Reopen

When resuming:

- Set brief status to `active`
- Add a dated resume note at the top of `brief.md`
- Read: brief → hypothesis register (open items) → last session → artifact index
- Open a new session file; do not append indefinitely to old sessions

---

## 7. Prototype gate

Prototypes are downstream of research. See [ai-collaboration.md](ai-collaboration.md#prototype-gate).

An opportunity moves from `exploratory` to `ready` only when:

- Evidence register covers market, customers, and workflow friction
- At least one opportunity row cites specific evidence and hypothesis IDs
- Open questions for the prototype are documented

---

## Folder reference

```text
product-intelligence-sprint/
├── docs/                 # Operating system (this document set)
├── templates/            # Scaffolds — copy, do not edit in place
├── backlog/              # Queue and status
├── companies/
│   └── <company-slug>/
│       ├── brief.md
│       ├── evidence-register.md
│       ├── hypothesis-register.md
│       ├── opportunity-register.md
│       └── sessions/
├── artifacts/
│   └── <company-slug>/
└── research/
    └── synthesis/        # Cross-company themes
```

---

## Related documents

| Document | Role |
|----------|------|
| [getting-started.md](getting-started.md) | Condensed quick start |
| [merge-policy.md](merge-policy.md) | PR and auto-merge |
| [companies/README.md](../companies/README.md) | Company folder conventions |
