# Companies

One folder per company — a long-running research project, not a one-off document.

## Convention

```text
companies/
  <company-slug>/
    brief.md                    # narrative synthesis (from templates/company-brief.md)
    evidence-register.md        # facts and observations
    hypothesis-register.md      # testable claims
    opportunity-register.md     # grounded product opportunities
    sessions/
      YYYY-MM-DD-<topic>.md     # per-session logs
```

Pair each company folder with `artifacts/<company-slug>/` for source material.

Do not start a company folder until a sprint is queued or in progress. See [docs/workflow.md](../docs/workflow.md).

## Status values

| Status | Meaning |
|--------|---------|
| `draft` | Scaffold only — not yet actively researched |
| `active` | Ongoing sessions and synthesis |
| `paused` | Intentionally stopped with next actions documented |
| `archived` | No current intent to resume; retained for reference |
