# Bridgit Product Intelligence Sprint — v0.1 knowledge-base seed

Repo note: since the repo is not set up yet, this is a first durable research seed. It is structured so we can later split it into markdown files like company/timeline.md, product/current-product.md, registers/evidence.md, and prototypes/opportunity-register.md.

Confidence labels: High = directly supported by primary sources. Medium = supported by public evidence but still interpretive. Low = plausible but needs more research.

⸻

## 1. Current state

Bridgit is positioning itself as AI workforce planning software for construction contractors, not as broad construction project management software. Its current public product story centers on project planning, internal resumes, forecasting, Bridgit AI, integrations, and communication. The homepage explicitly frames the product as "AI workforce planning for construction," and its product navigation groups capabilities around planning, resumes, forecasting, AI, integrations, and communication.

The company has moved from a narrower "Bridgit Bench" workforce planning product into a broader workforce intelligence platform. The clearest current direction is: contractor workforce data system of record + forecasting + AI-assisted planning + enterprise integrations.

This pass is public-source only. It does not include customer calls, internal docs, pricing data, sales process evidence, archived job postings, or direct product access.

⸻

## 2. Executive summary

FACT: Bridgit was founded by Mallorie Brodie and Lauren Lake after seeing construction workforce planning and communication break down across spreadsheets, email, and disconnected processes. Bridgit says its customers now include nearly 40% of the ENR 400, with presence across North America, the UK, Australia, and New Zealand.

FACT: Bridgit's public product strategy is increasingly AI-led. Current AI features include Ask Bridgit, Import Roles, and Smart Suggestions / Smart Suggestion Summaries. Bridgit emphasizes messy-data intake, natural-language querying, explainable recommendations, and construction-specific workforce planning rather than generic AI chat.

FACT: Bridgit's 2025 close announcement says the company had 332 customers managing 90,000 construction staff daily, more than 50% adoption among the ENR 50, 162% YoY growth across ANZ and the UK, and a 2026 focus on AI, analytics, global support, and self-perform/specialty contractor expansion.

INFERENCE: Bridgit's strategic wedge is not scheduling by itself. It is becoming the workforce intelligence layer between CRM/pursuit data, HRIS/ERP people data, project management systems, and executive decision-making. Its integration page supports this: Bridgit syncs project, pursuit, and people data from Autodesk Build, Procore, CMiC, Salesforce, Microsoft Dynamics, Unanet CRM, HubSpot, Workday, BambooHR, UKG, ADP, Snowflake, and others.

INFERENCE: The highest-value prototype space is not "AI assistant" in the abstract. The better opportunity is AI-supported planning artifacts: staffing meeting briefs, scenario explainers, hiring handoff packets, data quality checks, and executive workforce health reports. These are natural extensions of Bridgit's current direction and customer pain evidence.

⸻

## 3. Company timeline

| Period | Evidence | Interpretation | Confidence |
|--------|----------|----------------|------------|
| 2012 | Bridgit says Mallorie Brodie's family ties to construction helped inspire the company's founding in 2012. Lauren Lake co-founded the company and had civil/structural engineering background. | Founded from close exposure to construction operations, not generic SaaS ideation. | High |
| 2019 | Series B press says Bridgit had "pivoted from field-oriented project-management software" to flagship workforce planning product Bridgit Bench. | Major strategic pivot from field PM into workforce planning. | High |
| Series B period | Bridgit raised C$24M Series B to hire, build product, and capture market share. | Capital was aimed at category expansion, not only survival. | High |
| 2024 | Bridgit reported more than 250 customers, over 150 ENR 400 customers, 12 ENR Top 20 customers, 60+ new customers, more than 30 prebuilt integrations, UK expansion, and multiple million-dollar quarters. | Enterprise traction and international expansion became visible. | High |
| 2025 | Bridgit launched or emphasized Experience Tracking, Internal Resumes, Bridgit AI, and self-perform GC capabilities. | Product moved deeper into employee history, team-building, and forecasting. | High |
| 2025 close | Bridgit reported 332 customers, 90,000 staff managed daily, more than 50% ENR 50 adoption, and 162% YoY ANZ/UK growth. | Strong enterprise/category penetration claim. Needs third-party validation later. | High for claim, Medium for market implication |
| 2026 | Bridgit added AI leadership signals: Carol Leaman joined the board and Vincent Seguin joined as CTO to accelerate AI strategy. | AI is not just marketing copy. It is an org-level priority. | High |
| 2026 | Bridgit expanded toward specialty contractors with labor forecasting and crew management. | Expansion beyond large GCs into adjacent contractor types. | High |

Funding note: Bridgit's About page says it has raised over $35M USD, while a later press release says over $43.5M CAD. Treat this as a public-source discrepancy to normalize later.

Acquisitions: I did not find evidence in this pass that Bridgit has acquired another company or been acquired. That is a research gap, not a conclusion.

⸻

## 4. Market analysis

### Category definition

Bridgit operates in construction workforce planning. The category sits between:

* construction project management
* resource management
* labor forecasting
* HRIS/HCM
* CRM/pursuit management
* ERP/job cost systems
* BI / construction analytics
* field operations and crew coordination

Bridgit's product pages define the category through project-role-person planning, forecasting, utilization, bench cost, internal resumes, AI recommendations, and integrated workforce data.

### Market pressure

Construction labor remains a major constraint. Axios reported ABC's estimate that the U.S. construction industry needed 439,000 additional workers in 2025. Reuters later covered continuing labor pressure from power, data center, and infrastructure demand, including retirement risk and tight craft labor supply.

Bridgit's own 2025 workforce planning report claims 93% of surveyed leaders said labor shortages affect operations, 71% still rely on spreadsheets or whiteboards, 98% plan to increase workforce planning investment, and 99% plan to invest in AI, automation, or forecasting. This is Bridgit-sponsored data, so it should be treated as directional until verified independently.

### Market size

I did not find a reliable, specific public market-size number for "construction workforce planning" as a standalone category in this pass. The better near-term approach is to size from:

1. ENR 400 / ENR 50 contractor penetration.
2. Construction management software spend.
3. HRIS/ERP/field ops overlap.
4. Number of addressable employees managed by large GCs, self-perform groups, and specialty contractors.
5. Current Bridgit customer count and worker count claims.

Market size remains an open research item.

⸻

## 5. Customer personas

Evidence basis: Bridgit's product pages and customer quotes repeatedly mention operations leaders, HR, project executives, executives, project teams, and contractors moving from spreadsheets/homegrown tools to a shared planning platform.

| Persona | Goals | Responsibilities | Pain points | Success metrics | Likely objections |
|---------|-------|------------------|-------------|-----------------|-------------------|
| COO / VP Operations | Put the right people on the right work. Protect margin. Win work without overcommitting. | Workforce strategy, staffing governance, executive reviews, regional consistency. | No single view of availability, utilization, pipeline impact, or bench cost. | Utilization, staffing speed, project readiness, bench cost, fewer escalation meetings. | "Will teams actually keep it updated?" "Will this replace our process or add work?" |
| Workforce / Resource Planning Lead | Maintain the staffing plan and resolve conflicts. | Role planning, assignments, availability, staffing meetings, reporting. | Spreadsheet drift, manual math, stale updates, constant meetings. | Open roles filled, fewer conflicts, less manual reporting, meeting time reduced. | "How much cleanup is required before this works?" |
| Project Executive / PM / Superintendent | Secure the right team for each job. | Request roles, confirm assignments, manage project needs, communicate changes. | Staffing decisions happen outside project context. Too many calls, emails, and updates. | Assignment clarity, fewer delays, team fit, fewer last-minute changes. | "Will this help me or just help corporate?" |
| HR / People / Recruiting | Hire ahead of demand and retain talent. | Hiring plans, onboarding, skills, certifications, career paths, employee data. | Hiring requests arrive too late or lack context. People data disconnected from project demand. | Roles-for-hire accuracy, hiring lead time, retention, onboarding speed. | "Who owns the data?" "Does this expose sensitive employee info?" |
| Business Development / Preconstruction | Know whether the company can staff the work it is pursuing. | Pursuit planning, go/no-go support, team resumes, proposal inputs. | Pursuit teams lack real-time staffing capacity and relevant project experience. | Faster pursuit decisions, stronger proposal teams, higher confidence in go/no-go calls. | "Is the data complete enough to trust in pursuits?" |
| CIO / IT / Data Leader | Connect systems safely and avoid shadow spreadsheets. | Security, SSO, integrations, API governance, data architecture. | Data spread across CRM, HRIS, ERP, PM, spreadsheets. | Integration reliability, reduced duplicate entry, SOC2/SSO/API compliance. | "How secure is it?" "How much integration work is required?" |
| Specialty Contractor / Crew Ops Lead | Forecast labor and move crews efficiently. | Crew planning, job-to-job transitions, availability, field communication. | Calls, texts, manual updates, uncertain crew availability. | Crew utilization, fewer gaps, fewer manual updates, improved forecast accuracy. | "Was this built for trade contractors or retrofitted from GC workflows?" |

⸻

## 6. Workforce planning lifecycle map

1. **Pipeline and project intake** — Projects and pursuits enter the planning model from CRM, preconstruction, PM systems, or manual import. Bridgit's integrations page emphasizes syncing pursuit, project, and people data so teams are not doing "CSV gymnastics."

2. **Role demand definition** — Teams define roles, dates, allocation, location, and requirements. Bridgit's Project Planning page includes roles and assignments, bulk updates, drag-and-drop, AI import from screenshots or CSVs, and alerts.

3. **Supply visibility** — Planners view people, availability, experience, time off, location, and current/future assignments. Bridgit's Project Planning page includes time off, mobile access, maps, and project hubs.

4. **Matching and recommendations** — Smart Suggestions recommends people using availability, experience, commute distance, and role fit, with AI-generated explanations for why a person is a fit.

5. **Forecasting and scenario planning** — Forecasting compares future supply and demand, models what-if pursuit scenarios, identifies roles for hire, shows utilization, and estimates bench cost.

6. **Staffing meeting and decision review** — Customers still appear to rely on recurring meetings, but Bridgit reduces the time and prep burden. A Suffolk quote says Bridgit helped assign people before meetings and reduce a 20-person Excel-heavy meeting to a much shorter monthly process.

7. **Communication and change management** — Bridgit's Communication module explicitly targets scattered emails, spreadsheets, lost context, assignment alerts, broadcast updates, and notes.

8. **Reporting and executive review** — Executives review utilization, bench cost, project pipeline, hiring needs, and workforce health. Bridgit's customer quotes mention speed-to-decision, go/no-go scenarios, and executive visibility.

9. **Historical learning / experience capture** — Experience Tracking and Internal Resumes turn project history into reusable workforce intelligence. Bridgit says digital resumes automatically capture experience by project assignments, build type, market sector, owner, and custom fields.

⸻

## 7. Product architecture overview

Publicly visible architecture is limited, but enough is available to build a working mental model.

### Core objects

Likely core data model:

* People
* Projects
* Pursuits / opportunities
* Roles
* Assignments
* Availability
* Time off
* Skills / experience
* Project history
* Location / commute context
* Hiring gaps
* Reports / saved views
* Notes / communications

### Product modules

| Area | Public capability | Strategic role |
|------|-------------------|----------------|
| Project Planning | Project hub, maps, roles, assignments, time off, mobile, Smart Suggestions. | Day-to-day staffing workspace. |
| Forecasting | Supply/demand, roles for hire, utilization, bench cost, what-if planning. | Executive and HR planning layer. |
| Internal Resumes / Experience Tracking | Digital resumes and project experience capture. | Differentiates beyond availability scheduling. |
| Bridgit AI | Ask Bridgit, Import Roles, Smart Suggestions, structured messy-data intake. | Current strategic narrative. |
| Integrations | CRM, HRIS, ERP, PM, data warehouse connectors. | Enterprise adoption and data moat. |
| Communication | Alerts, broadcasts, notes, assignment context. | Reduces email/spreadsheet coordination. |
| Security / enterprise | SOC 2 Type 2, SSO, SAML, custom permissions, REST API, AWS hosting. | Table-stakes enterprise readiness. |

### Strategic vs table stakes

**Strategically important**

* AI built around workforce planning data.
* Explainable recommendations.
* Integrations across CRM, HRIS, PM, ERP, and data warehouse.
* Experience Tracking / Internal Resumes.
* Forecasting and roles-for-hire.
* Specialty contractor labor forecasting and crew management.
* Enterprise and global expansion.

**Table stakes**

* SOC 2 Type 2.
* SSO / SAML.
* Permissions.
* REST API.
* Mobile access.
* Alerts.
* Dashboards and reporting.
* CSV import/export.

⸻

## 8. Product history and evolution

FACT: Bridgit began closer to field-oriented project management and pivoted in 2019 toward Bridgit Bench as workforce planning software.

FACT: The product later expanded into forecasting, integrations, executive reporting, internal resumes, experience tracking, and AI.

INFERENCE: The product has moved through four phases:

1. Construction software entry point — field/project-management roots.
2. Workforce planning wedge — Bridgit Bench as the flagship product.
3. Enterprise workforce platform — Integrations, executive visibility, forecasting, permissions, SOC2, APIs.
4. AI workforce intelligence — Ask Bridgit, Import Roles, Smart Suggestions, explainability, messy-data handling.

INFERENCE: The name "Bridgit Bench" still appears in older materials, but current messaging often leads with "Bridgit" and "AI workforce planning." That suggests the company may be broadening from a single product brand into a platform brand. Confidence: Medium.

⸻

## 9. Business strategy

### Ideal customer profile

High-confidence ICP: ENR 400 / ENR 50 general contractors, large regional contractors, self-perform general contractors, and increasingly specialty contractors with enough workforce complexity that spreadsheets break down. Bridgit's own 2025 close announcement emphasizes ENR 50 adoption, enterprise movement away from spreadsheets/homegrown tools, and expansion into self-perform and specialty contractor workflows.

### Expansion strategy

FACT: Bridgit expanded into the UK/EU, ANZ, self-perform GC use cases, and specialty contractors.

INFERENCE: The expansion path is likely:

1. Land with workforce planning.
2. Expand across regions/business units.
3. Connect HRIS, CRM, PM, ERP, and data warehouse systems.
4. Add executive forecasting and analytics.
5. Add AI and recommendations on top of connected workforce data.
6. Move into adjacent labor-heavy segments like self-perform and specialty trades.

### Pricing philosophy

No public pricing was found in this pass. Based on product complexity, enterprise security, implementation language, and customer profile, pricing is likely enterprise SaaS with module/scale/implementation variables. Confidence: Low until validated.

### Implementation model

Bridgit publicly promises guided implementation and managed integration support. It also references customer delivery, account management, a Customer Advisory Board, and founder customer roadshows.

INFERENCE: Customer success and implementation are probably core to retention. This product depends on data quality, operating rhythm change, and cross-functional adoption.

⸻

## 10. Competitive landscape

| Competitor type | Example | Strengths | Weaknesses vs Bridgit | Confidence |
|-----------------|---------|-----------|----------------------|------------|
| Broad construction platforms | Procore Resource Management | Strong suite, field-to-financial data, labor/equipment tracking, resource planning. Procore positions resource management around labor, equipment, financials, forecasting, field communication, and productivity. | Less clearly specialized around executive workforce planning, internal resumes, and contractor-specific workforce intelligence. | Medium |
| Field-to-finance ops platforms | Assignar | Strong for crew/equipment scheduling, time tracking, forms, compliance, job costing, and subcontractor field ops. | More field execution and finance oriented; less evidence of GC enterprise workforce strategy, pursuit scenarios, and executive team planning. | Medium |
| ERP / job cost systems | CMiC, Oracle, Trimble ecosystem | Strong financial and project system of record. | Often not purpose-built for dynamic people/project workforce planning. | Medium |
| HRIS / HCM | Workday, ADP, UKG, BambooHR | Own employee data and HR workflows. | Do not own construction project demand, role forecasting, or project team-building. | High |
| CRM / pursuit systems | Salesforce, Dynamics, HubSpot, Unanet CRM | Own pursuit pipeline. | Do not own labor capacity planning. | High |
| Spreadsheets / homegrown tools | Excel, whiteboards, internal trackers | Flexible, familiar, cheap. | Stale, manual, hard to scale, weak for forecasting and executive visibility. Bridgit's own report says 71% still rely on spreadsheets or whiteboards. | High |

Where Bridgit appears strongest: project-team staffing visibility across many active and future jobs; pipeline-to-labor forecasting; people/project experience history; executive workforce review; cross-region standardization; HR and operations alignment; AI that can answer questions against contractor workforce data.

The biggest competitor may still be Excel plus meetings, not another SaaS vendor.

⸻

## 11. Hiring and organizational signal analysis

This pass did not include LinkedIn/job-posting history, so the hiring analysis is limited to public leadership and press signals.

**Signals found**

* AI leadership: Carol Leaman joined Bridgit's board and Vincent Seguin joined as CTO to accelerate AI strategy. Bridgit describes a "data moat" around workforce planning decisions and says Seguin helped build the foundation supporting 332 customers and 90,000 staff.
* Enterprise GTM: Luke Forrest, VP Sales, previously held leadership roles at PlanGrid and Autodesk. Amy Palmer, VP Marketing, also has PlanGrid and Autodesk acquisition experience.
* Operations maturity: Bridgit lists VP Strategy and Operations, CFO, and other executive functions.
* Customer-led product: Bridgit says 2025 was the first full year of its Customer Advisory Board and that Lauren Lake conducted a customer roadshow.

**Inference:** Bridgit is investing in AI product strategy, enterprise sales and marketing, customer feedback loops, global support, analytics, and specialty/self-perform contractor workflows. Confidence: Medium-high.

⸻

## 12. Leadership philosophy summary

1. People-first construction operations — founding mission is to help contractors build more effectively by putting people first.
2. Workforce planning as strategic advantage — tied to winning work, avoiding margin risk, improving retention, and using employee experience better.
3. AI should be explainable and grounded in contractor data — Smart Suggestions explain "why," AI features "show the math," platform is model-agnostic, customer data is not used to train shared foundation models.
4. Customer listening matters — Customer Advisory Board, customer roadshows, and product improvements from feedback are explicit 2025 company themes.
5. Construction data is fragmented, and Bridgit wants to sit across it — integrations and messy-data intake appear central to the product thesis.

⸻

## 13. Customer voice

Customers describe value in practical terms: faster staffing decisions; less Excel work; fewer meetings; better project teams; better visibility into skills and experience; more accurate reporting; more confidence in pursuit and go/no-go decisions; better morale and retention.

| Marketing claim | Customer-language translation |
|-----------------|------------------------------|
| "AI workforce planning" | "I can ask questions instead of digging through reports." |
| "Smart Suggestions" | "Show me who is actually available and qualified." |
| "Forecasting" | "Can we win this work without blowing up our staffing plan?" |
| "Internal Resumes" | "Who has done this kind of work before?" |
| "Integrations" | "Stop making me reconcile CRM, HR, PM, and spreadsheets manually." |
| "Communication" | "Stop losing assignment context in email, calls, and meetings." |

⸻

## 14. Workflow friction analysis

| Friction | Evidence | Why it matters | Confidence |
|----------|----------|----------------|------------|
| Spreadsheet dependence | Bridgit-sponsored survey says 71% still rely on spreadsheets or whiteboards. | Strong replacement wedge. | High |
| Meeting-heavy planning | Suffolk quote references reducing a large Excel-based meeting process. | Opportunity for meeting prep, decision logs, and follow-through. | High |
| Scattered communication | Bridgit's Communication module targets scattered emails, spreadsheets, lost context, alerts, and notes. | Communication layer likely still incomplete. | High |
| Messy unstructured inputs | Bridgit AI imports roles from CSVs, screenshots, and PDFs. | Data onboarding and role intake remain painful. | High |
| HR/Ops handoff | Roles for Hire aligns operations and HR around hiring needs. | Hiring plans likely need better context and workflow. | High |
| Crew communication | Specialty expansion mentions calls, texts, and manual updates as existing pain. | Specialty contractor workflows require more field-oriented coordination. | High |
| Data trust | Bridgit emphasizes integrations, explainability, and showing the math. | AI usefulness depends on trusted source data. | Medium-high |

⸻

## 15. Roadmap hypotheses

**FACT**

* Bridgit is investing in AI features: Ask Bridgit, Import Roles, and Smart Suggestion Summaries.
* Bridgit is investing in specialty contractor workflows, including labor forecasting and crew management.
* Bridgit is investing in global growth, especially UK and ANZ.
* Bridgit is investing in analytics, global support, AI, and self-perform in 2026.

**INFERENCE**

* Bridgit will likely deepen AI from question-answering into planning workflows: meeting prep, scenario comparison, recommended staffing moves, and hiring handoffs.
* Bridgit will likely invest more in data quality, integration monitoring, and explainability because AI recommendations are only useful if the data is trusted.
* Specialty contractor expansion will likely push the product closer to crew scheduling, field communication, and labor curve forecasting.
* Internal Resumes and Experience Tracking may become a stronger differentiator for proposals, career development, and retention.

**SPECULATION**

* Bridgit may eventually offer benchmark analytics based on aggregated workforce planning patterns.
* Bridgit may build more explicit proposal/pursuit team-building workflows.
* Bridgit may expose more API and data warehouse capabilities for enterprise customers.
* Bridgit may build AI-generated executive narratives for workforce health and pipeline risk.

⸻

## 16. AI opportunity assessment

**Existing AI:** Ask Bridgit, Import Roles, Smart Suggestions, Smart Suggestion Summaries.

**AI principles that appear aligned:** Ground AI in workforce data; explain recommendations; keep humans in decision control; reduce manual planning work; handle messy inputs; avoid generic chatbot framing.

| Opportunity | Why it fits | Confidence |
|-------------|-------------|------------|
| Staffing meeting brief generator | Customers already use meetings; Bridgit already has the data. | High |
| Scenario explanation assistant | Forecasting already includes what-if planning and go/no-go decisions. | High |
| Hiring request generator | Roles for Hire already bridges Ops and HR. | High |
| Data quality copilot | AI depends on trusted project/person/role data. | Medium-high |
| Assignment change digest | Communication pain is explicit. | Medium-high |
| Experience-based team builder | Internal Resumes and Experience Tracking already exist. | High |
| Crew transition assistant | Specialty contractor expansion creates a natural field workflow. | Medium |
| Executive workforce narrative | Executives need digestible utilization, bench cost, and pipeline risk views. | High |

Avoid: generic "AI chatbot," autonomous staffing decisions, or moonshot labor marketplaces.

⸻

## 17. Prototype opportunity register

| # | Prototype | Customer | Workflow | Pain point | Why Bridgit might care | Impact | Complexity | Confidence |
|---|-----------|----------|----------|------------|------------------------|--------|------------|------------|
| 1 | Staffing Meeting Brief | Ops / Workforce planner | Pre-meeting review | Too much Excel prep and meeting time | Supports existing planning cadence without replacing it | High | Medium | High |
| 2 | Scenario Explainer | COO / Ops / BD | Pursuit and capacity review | Hard to understand "what happens if we win this?" | Extends forecasting and go/no-go value | High | Medium | High |
| 3 | Data Quality Radar | IT / Ops / CS | Integration and planning trust | Stale, missing, conflicting data | Makes AI and forecasting more trustworthy | High | Medium | High |
| 4 | Role Import Review Queue | Workforce planner | Role intake | Messy PDFs, screenshots, CSVs | Builds on existing Import Roles | Medium-high | Low-medium | High |
| 5 | Experience-Based Pursuit Team Builder | BD / Precon / Ops | Proposal staffing | Hard to find relevant project experience fast | Extends Internal Resumes into revenue workflow | High | Medium | High |
| 6 | Ops-to-HR Hiring Handoff | Ops / HR | Roles for hire | Hiring requests lack context | Turns forecast gaps into recruiter-ready briefs | Medium-high | Low-medium | High |
| 7 | Crew Move Planner | Specialty contractor ops | Crew scheduling | Calls/texts/manual updates | Supports 2026 specialty contractor strategy | High | Medium | Medium-high |
| 8 | Assignment Communication Digest | PMs / field leaders | Change communication | Assignment context lost in email | Extends Communication module | Medium | Low | High |
| 9 | Retention and Career Fit Signals | HR / Ops | Assignment planning | Poor fit can hurt morale/retention | Uses experience, commute, tenure, career goals | Medium | Medium-high | Medium |
| 10 | Executive Workforce Health Report | COO / exec team | Monthly review | Leaders need concise workforce risk story | Turns data into recurring executive artifact | High | Low-medium | High |

Best first prototype: Staffing Meeting Brief + Scenario Explainer.

⸻

## 18. Evidence register

| ID | Evidence | Source type | What it supports | Confidence |
|----|----------|-------------|------------------|------------|
| E001 | Founding story tied to construction spreadsheet disconnect and people-first mission. | Primary | Company origin, mission. | High |
| E002 | 2019 pivot from field project management to Bridgit Bench. | Primary press | Product evolution. | High |
| E003 | 332 customers, 90k staff managed daily, >50% ENR 50 adoption. | Primary press | Scale and ICP. | High for claim |
| E004 | 2024 UK expansion, 250+ customers, 30 integrations. | Primary press | Expansion and enterprise maturity. | High |
| E005 | AI features: Ask Bridgit, Import Roles, Smart Suggestions. | Primary product | AI strategy. | High |
| E006 | Project Planning module includes project hub, maps, roles, time off, mobile. | Primary product | Current product scope. | High |
| E007 | Forecasting includes supply/demand, roles for hire, utilization, bench cost. | Primary product | Product value proposition. | High |
| E008 | Integrations include CRM, HRIS, PM, ERP, data warehouse. | Primary product | Platform strategy. | High |
| E009 | SOC2 Type 2, SSO, SAML, permissions, API. | Primary product | Enterprise readiness. | High |
| E010 | 71% spreadsheet/whiteboard reliance, 98% planning investment. | Bridgit-sponsored report | Market pain. | Medium-high |
| E011 | Suffolk-style customer quote: fewer meetings, less Excel. | Customer quote via Bridgit | Workflow friction. | Medium-high |
| E012 | Experience Tracking / digital resumes. | Primary product press | Product differentiation. | High |
| E013 | Specialty contractor labor forecasting and crew management. | Primary press | Roadmap / expansion. | High |
| E014 | AI leadership hires and board addition. | Primary press | Hiring / org signal. | High |
| E015 | Construction labor shortage and retirement pressure. | News / market reporting | External market pressure. | Medium-high |
| E016 | Procore Resource Management positioning. | Competitor product | Competitive landscape. | High |
| E017 | Assignar field-to-finance positioning. | Competitor product | Competitive landscape. | High |

⸻

## 19. Hypothesis register

| ID | Hypothesis | Type | Evidence basis | Confidence | How to test |
|----|------------|------|----------------|------------|-------------|
| H001 | Bridgit's durable wedge is workforce intelligence, not scheduling. | Product strategy | Forecasting, AI, integrations, experience tracking. | High | Compare product demos, customer calls, sales collateral. |
| H002 | AI strategy depends on proprietary workforce planning data quality. | Product / AI | "Data moat," explainability, integrations, model-agnostic language. | Medium-high | Analyze AI UX and data requirements. |
| H003 | Specialty contractors are a major 2026 expansion vector. | Market / roadmap | Dedicated 2026 specialty launch. | High | Track releases, case studies, job posts. |
| H004 | Integrations are strategic, not implementation plumbing. | Platform | Integration page ties CRM/HRIS/PM data to AI and forecasts. | High | Review customer implementation stories. |
| H005 | Internal Resumes may become a pursuit/proposal differentiator. | Product opportunity | Experience Tracking and project history capture. | Medium-high | Look for proposal/BD customer stories. |
| H006 | Customer success is a key moat because behavior change is hard. | GTM | Guided implementation, CAB, roadshow, enterprise deployment language. | Medium | Review implementation timelines and CS org hiring. |
| H007 | Pricing is likely enterprise/module/scale-based. | Business model | No public pricing; enterprise ICP. | Low | Find procurement pages, reviews, quotes, customer budgets. |
| H008 | Data quality tooling will become more important as AI adoption grows. | Product roadmap | AI + integrations + messy data intake. | Medium-high | Track release notes and customer complaints. |

⸻

## 20. Open questions

1. What is Bridgit's actual pricing model?
2. What is the average implementation timeline?
3. How many seats/users does a typical enterprise deployment include?
4. Does Bridgit price by worker count, module, company size, usage, or contract value?
5. What are the most common integration combinations?
6. What data model does Bridgit expose through its API?
7. How granular are permissions?
8. How much work is required to clean customer data before AI features are useful?
9. What are the top churn or adoption risks?
10. What percentage of customers use Forecasting vs Project Planning vs AI?
11. What does "global support" mean operationally?
12. How does Bridgit handle EU/UK data residency if security docs emphasize North American AWS hosting?
13. Who owns the workforce planning process inside customer organizations?
14. What customer roles are daily active users versus occasional reviewers?
15. What does Bridgit consider its biggest competitor: Procore, ERP, spreadsheets, or internal tools?

⸻

## 21. Research gaps

* Pricing and packaging.
* Sales cycle and procurement process.
* Customer reviews from G2, Capterra, Reddit, forums, and implementation partners.
* Archived product messaging and release history.
* Historical job postings and hiring patterns.
* Deeper leadership interviews, podcasts, and conference talks.
* API documentation.
* Actual demo/product screenshots.
* Competitive teardown of Procore Resource Management, Assignar, CMiC, Oracle, Autodesk, and spreadsheet workflows.
* Customer maturity model.
* International data residency and compliance details.
* Partner ecosystem and implementation services.

⸻

## 22. Recommended next research priorities

1. Set up the repo skeleton — Create folders for company, market, customers, product, competition, ai, prototypes, and registers.
2. Turn this into atomic docs — Split this v0.1 into separate markdown files. Keep the evidence and hypothesis registers as living files.
3. Do a product-history scrape — Use Bridgit press pages, archived pages, and release announcements to reconstruct product naming and feature evolution.
4. Do a competitor teardown — Start with Procore Resource Management and Assignar.
5. Mine customer voice — Pull every Bridgit case study into a structured table.
6. Analyze hiring signals properly — Use LinkedIn, job boards, archived postings, and leadership announcements.
7. Pick one prototype lane — Start with Staffing Meeting Brief or Scenario Explainer.

⸻

## 23. Durable artifacts to create

Recommended initial repo structure:

```text
bridgit-product-intelligence/
  README.md
  company/timeline.md
  market/category-definition.md
  customers/personas.md
  product/current-product.md
  strategy/roadmap-hypotheses.md
  registers/evidence-register.md
  registers/hypothesis-register.md
  backlog/research-backlog.md
```

The strongest next move is to create the repo, add this as README.md plus registers/evidence-register.md, then start a focused second pass on customer voice and workflow friction.
