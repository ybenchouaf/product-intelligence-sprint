# Prototype Opportunity Register — Bridgit

Living file. v0.1 seed opportunities O001–O010. Status `exploratory` until more evidence links added.

| Field | Value |
|-------|-------|
| **Company slug** | `bridgit` |
| **Last updated** | 2026-06-29 |

## Index

| ID | Opportunity | Target User | Impact | Complexity | Confidence | Status |
|----|-------------|-------------|--------|------------|------------|--------|
| O001 | Staffing Meeting Brief | Ops / Workforce planner | High | Medium | High | exploratory |
| O002 | Scenario Explainer | COO / Ops / BD | High | Medium | High | exploratory |
| O003 | Data Quality Radar | IT / Ops / CS | High | Medium | High | exploratory |
| O004 | Role Import Review Queue | Workforce planner | Medium-high | Low-medium | High | exploratory |
| O005 | Experience-Based Pursuit Team Builder | BD / Precon / Ops | High | Medium | High | exploratory |
| O006 | Ops-to-HR Hiring Handoff | Ops / HR | Medium-high | Low-medium | High | exploratory |
| O007 | Crew Move Planner | Specialty contractor ops | High | Medium | Medium-high | exploratory |
| O008 | Assignment Communication Digest | PMs / field leaders | Medium | Low | High | exploratory |
| O009 | Retention and Career Fit Signals | HR / Ops | Medium | Medium-high | Medium | exploratory |
| O010 | Executive Workforce Health Report | COO / exec team | High | Low-medium | High | strengthened — gate closed |

**Seed recommendation:** Best first prototypes — **O001** (Staffing Meeting Brief) + **O002** (Scenario Explainer).

## Entries

### O001

| Field | Value |
|-------|-------|
| **Confidence** | High |
| **Estimated Impact** | High |
| **Estimated Complexity** | Medium |
| **Status** | exploratory |

#### Opportunity

Staffing Meeting Brief — pre-meeting artifact summarizing open roles, candidates, conflicts, and recommended assignments.

#### Observed Workflow

Pre-meeting review; recurring staffing meetings with heavy Excel prep (E011).

#### Pain Point

Too much Excel prep and meeting time.

#### Evidence

| ID | Relevance |
|----|-----------|
| E011 | Suffolk reduced Excel-heavy meeting |
| E010 | Spreadsheet dependence |

#### Proposed Improvement

Generate brief from existing Bridgit planning data before staffing meetings.

#### Target User

Ops / Workforce planner

#### Notes

Small enough to build; fits product direction; does not require owning full data model. **Inference from seed** — not validated with customers.

---

### O002

| Field | Value |
|-------|-------|
| **Confidence** | High |
| **Estimated Impact** | High |
| **Estimated Complexity** | Medium |
| **Status** | exploratory |

#### Opportunity

Scenario Explainer — natural-language or structured explanation of "what happens if we win this pursuit?"

#### Observed Workflow

Pursuit and capacity review; go/no-go decisions.

#### Pain Point

Hard to understand capacity impact of winning new work.

#### Evidence

| ID | Relevance |
|----|-----------|
| E007 | Forecasting, what-if planning |

#### Proposed Improvement

Extend forecasting into explainable scenario narratives.

#### Target User

COO / Ops / BD

---

*O003–O009: see index and [research-seed-v0.1.md](../research/research-seed-v0.1.md) section 17.*

### O010 — Executive Workforce Health Report

| Field | Value |
|-------|-------|
| **Confidence** | High |
| **Estimated Impact** | High |
| **Estimated Complexity** | Low-medium |
| **Status** | strengthened — **not approved to build** |

#### Opportunity

Executive Workforce Health Report — concise utilization, bench cost, pipeline risk narrative for leadership review.

#### Evidence

| ID | Relevance |
|----|-----------|
| E022 | Dashboard/reporting friction; printable outputs |
| E020, E021 | Excel export / manual narrative behavior (inference) |

#### Why it matters

Supports a lightweight **planning artifact** prototype lane (H009) — but executive reporting workflows are not validated.

#### Gate

**Do not build yet.** Next validation: what executives actually use after data leaves Bridgit.

## Changelog

| Date | Change |
|------|--------|
| 2026-06-28 | Populated O001–O010 from v0.1 seed |
| 2026-06-29 | Session 01: strengthened O010; prototype gate remains closed |
