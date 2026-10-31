# FDE Level System

**ICS 03.100.30　CCS A 00**

**Standard No.: Q/0706 001—2026**

| Item | Content |
|---|---|
| Title | FDE Level System: Five Levels and Two Tracks |
| Issued by | 0706 Technology (Suzhou) Co., Ltd. |
| Date of issue | 2026-10-31 |
| Date of implementation | 2026-10-31 |
| Status | Enterprise standard (published) |
| Supersedes | First edition |
| Public address | https://fde.0706.tech/en/standard/ |

---

## Foreword

This document is drafted in accordance with GB/T 1.1—2020, *Guidelines for standardization — Part 1: Rules for the structure and drafting of standardizing documents*.

This document is proposed by and under the jurisdiction of 0706 Technology (Suzhou) Co., Ltd.

Drafting organisation: 0706 Technology (Suzhou) Co., Ltd.

This is the first edition.

**Patents.** Some content of this document may be subject to patent rights. The issuing organisation does not take responsibility for identifying such rights.

**Nature of the document.** This is an enterprise standard, developed and published by the enterprise on its own initiative under the *Standardization Law of the People's Republic of China*. It provides a shared vocabulary for internal talent evaluation and external hiring. It is **not** a national occupational qualification; no certificates are issued and no examinations are held. "Forward Deployed Engineer" is not currently listed in China's national occupation classification.

**Language.** The Chinese text prevails. This English version is a working translation provided for reference.

---

## Introduction

Judgements about who can actually deliver AI work have long rested on two unverifiable signals: a list of tools and a count of years. The first mistakes tool fluency for delivery capability; the second mistakes elapsed time for growth. Employers are left pricing candidates on interview impressions, and practitioners cannot tell which layer they are stuck at.

This document replaces the basis of judgement with one verifiable question: **what is this person responsible for**. Level changes when the object of responsibility changes — not when the toolchain grows or certificates accumulate. To make "responsible" checkable, every level binds to submittable evidence, and the document specifies the evaluation method and the review cycle.

Three trade-offs shape the text: it specifies only what can be verified; it presumes no single technical route; and it does not dress an internal grading scheme as an industry standard. The relationship to external systems is stated in 5.3.

---

## 1 Scope

This document specifies terms and definitions for the Forward Deployed Engineer (FDE), the division of capability levels, requirements and evidence for each level, the correspondence between capability domains and marks, and the evaluation method and procedure.

It applies to:

a) internal evaluation, levelling and promotion review for staff working on AI scenario delivery;

b) grading and requirement descriptions in public job postings for this role;

c) self-assessment and evidence preparation by practitioners.

It does not apply to:

a) vocational skill certification or any activity requiring administrative qualification;

b) salary commitments, employment commitments, or any party's quotation;

c) a final judgement on an individual's capability (see 9.6).

---

## 2 Normative references

The following documents are referred to in the text in such a way that some or all of their content constitutes requirements of this document.

GB/T 1.1—2020, *Guidelines for standardization — Part 1: Rules for the structure and drafting of standardizing documents*

GB/T 20000.1, *Standardization and related activities — General vocabulary*

GB/T 20001.5, *Rules for drafting standards — Part 5: Specification standards*

---

## 3 Terms and definitions

For the purposes of this document, the terms and definitions given in GB/T 20000.1 and the following apply.

### 3.1

**forward deployed engineer (FDE)**

An engineering role that works inside the customer's operation, takes a measurable business scenario as the unit of work, and completes the full cycle from diagnosis through implementation, evaluation and handover.

Note: Unlike an algorithm engineer or an implementation consultant, this role is accountable for both the business outcome and the engineering realisation, and treats reusable assets as a by-product of delivery.

### 3.2

**scope of responsibility**

The sole criterion for level, composed of the object of responsibility, the cost of failure, and replaceability.

### 3.3

**capability mark**

A five-step scale describing mastery within a capability domain: guided, independent, adaptive, systemic, industry.

### 3.4

**step-up**

The substantive change in scope of responsibility relative to the preceding level.

Note: A step-up shall be an observable change, not an adjective; see Annex A.

### 3.5

**capability domain**

One of five observation dimensions: business literacy, scenario engineering, AI engineering and debugging, delivery assurance, delivery engineering.

### 3.6

**evidence pack**

One of six kinds of submittable material aligned with the capability domains: business diagnosis, scenario and acceptance, data and permissions, AI debugging and evaluation, delivery operations, assetisation.

### 3.7

**asset**

A reusable output — connector, template or evaluation set — judged by whether a second delivery actually used it.

### 3.8

**two tracks**

The technical delivery track (T) and the business delivery track (B), sharing one ladder and one level sequence, differing only in capability weighting.

### 3.9

**metric language**

The measurement language appropriate to a level when reporting value; it rises from task effort to business and industry metrics as level increases.

### 3.10

**levelling review**

The formal process in which reviewers determine a level from submitted evidence and scope of responsibility.

### 3.11

**self-assessment**

A practitioner's own judgement of level and gaps using this document. It is a locator, not a verdict.

---

## 4 Abbreviations

FDE: Forward Deployed Engineer

T track: Technical delivery track

B track: Business delivery track

SOP: Standard Operating Procedure

SOW: Statement of Work

---

## 5 General

### 5.1 Principles

**5.1.1 Level follows scope of responsibility.** Evaluation shall rest on the object of responsibility, the cost of failure and replaceability — not on breadth of tooling, count of certificates, or years of service.

**5.1.2 Evidence before self-description.** Every level requires verifiable material (see Annex B). A capability without material is recorded as "to be verified"; self-description shall not substitute for it.

**5.1.3 One ruler for two tracks.** At the same level, the two tracks carry the same scope of responsibility and the same salary band; only capability weighting differs (see 5.4).

### 5.2 Correspondence between marks and levels

Table 1 gives the one-to-one correspondence.

**Table 1 — Marks and levels**

| Mark | Meaning | Level | Keyword |
|---|---|---|---|
| Guided | Completes the work with a template or instructions; no judgement required | L1 | Execution |
| Independent | Completes the standard case without guidance | L2 | Independent |
| Adaptive | Handles exceptions and non-standard cases, and makes trade-offs | L3 | Coordination |
| Systemic | Turns practice into a mechanism others follow | L4 | System |
| Industry | Influences outside: adopted by peers, or shapes a standard | L5 | Method |

Three rules follow, and shall be enforced:

a) two adjacent levels shall not share a mark in the same domain — if they do, that domain cannot distinguish them;

b) marks shall not be skipped; a domain rising one mark shall produce that mark's evidence in the same domain;

c) every domain at every level shall carry a concrete description (see 7.3); a mark name alone is not a requirement.

### 5.3 Statement of nature

This document is an enterprise standard. Before self-declaration on the public service platform for enterprise standards is completed, only the wording "enterprise standard (draft)" shall be used. After declaration, the wording "self-declared on the public service platform for enterprise standards" may be used with the registration number. The terms "industry standard" and "national standard" shall not be used in any case.

### 5.4 Capability weighting of the two tracks

**Table 2 — Capability weighting**

| Domain | T track | B track |
|---|---|---|
| Business literacy | 3 | 5 |
| Scenario engineering | 4 | 5 |
| AI engineering and debugging | 5 | 3 |
| Delivery assurance | 3 | 4 |
| Delivery engineering | 5 | 3 |

Note: weights guide emphasis in evaluation; they are not summed into a score. Level is determined per 8.3.

---

## 6 Capability levels and requirements

### 6.1 Division of levels

**Table 3 — Levels**

| Level | Rank | Keyword | Mark | Responsible for | T track title | B track title |
|---|---|---|---|---|---|---|
| L1 | Entry | Execution | Guided | Tasks | Junior Delivery Engineer | Junior Business Analyst |
| L2 | Intermediate | Independent | Independent | Scenarios | Delivery Engineer | Scenario Delivery Consultant |
| L3 | Advanced | Coordination | Adaptive | Project groups | Senior Delivery Engineer | Senior Scenario Consultant |
| L4 | Lead | System | Systemic | Organisational systems | Lead Delivery Engineer | Head of Scenario Delivery |
| L5 | Expert | Method | Industry | Industry methods | Delivery Expert | Scenario Expert |

Note: "Expert" is the name of L5 in this document, used in the ordinary occupational sense; it is not a claim about any individual or organisation.

### 6.2 L1 (Entry / Execution / Guided)

**Table 4 — L1 requirements**

| Item | Content |
|---|---|
| Step-up | Baseline: from "can use the tools" to "can hand over one clean piece of work" |
| Mark | Guided |
| Scope of responsibility | Accountable for: one clearly bounded task delivered on time and to standard. Not accountable for: scenario scope and acceptance, budget, customer relationship |
| Typical scope | A single task inside one scenario; 1–2 modules in one system; front-line users and a mentor; days to weeks; no budget authority |
| Mark requirements | Business literacy Guided; scenario engineering Guided; AI engineering Guided; delivery assurance Guided; delivery engineering Guided |
| Evidence required | a) runs the existing template unaided and explains each step; b) failure samples with fixes, not only success screenshots; c) can state, on handover, where it is most likely to break |
| Deliverables | A working module or configuration; start-up notes; failure sample log |
| Metric language | Task-level effort and rework count (minutes / hours) |
| Promotion | a) three consecutive tasks without rework; b) judges correctly when to pause and ask for help; c) at least one document reused directly by someone else |
| Fast-track | Not applicable. The value of this level is fundamentals; skipping hands the risk to the next level |
| Common misconception | Treating tool fluency as capability |
| Failure mode | Work is finished but not handed over cleanly: no documentation, no failure samples, the next person starts from zero |

### 6.3 L2 (Intermediate / Independent / Independent)

**Table 5 — L2 requirements**

| Item | Content |
|---|---|
| Step-up | From delivering a task to owning an outcome — you start signing your name to a process |
| Mark | Independent |
| Scope of responsibility | Accountable for: one scenario end to end, from requirement confirmation to live operation. Not accountable for: priorities across scenarios, organisational mechanisms, cross-department resourcing |
| Typical scope | One scenario full cycle; data and interfaces across 1–3 systems; business owner, front-line staff and IT/data; weeks to months; single-scenario budget subject to approval |
| Mark requirements | Business literacy Independent; scenario engineering Independent; AI engineering Independent; delivery assurance Independent; delivery engineering Guided |
| Evidence required | a) a scope sheet (boundaries, baseline numbers, acceptance actions); b) a failure set of no fewer than 20 cases, with the conditions under which it fails; c) one record of a real process running in production |
| Deliverables | A running scenario; acceptance sheet; failure sample set; first version of the runbook |
| Metric language | Scenario metrics (accuracy, cycle time, handle time, error rate) |
| Promotion | a) two scenarios delivered independently, one running 4+ weeks; b) defines the baseline and writes acceptance as a checkable condition; c) at least one deliverable reused by a second scenario |
| Fast-track | Equivalent-scale evidence (including acceptance and handover) may skip the task-level review, but never the evidence review |
| Common misconception | Treating go-live as delivery complete |
| Failure mode | The scenario works but nobody uses it: acceptance measured features, not business change |

### 6.4 L3 (Advanced / Coordination / Adaptive)

**Table 6 — L3 requirements**

| Item | Content |
|---|---|
| Step-up | From doing one well to deciding which ones to do — the first time you hold the trade-off |
| Mark | Adaptive |
| Scope of responsibility | Accountable for: a portfolio of scenarios, its priorities and resources, and the mechanism that makes hard wins repeatable. Not accountable for: organisational standards and capability development |
| Typical scope | A portfolio of 3–10 scenarios with prioritisation; cross-system and cross-department orchestration; department heads and multiple vendors; quarterly horizon; participates in budgeting |
| Mark requirements | Business literacy Independent; scenario engineering Adaptive; AI engineering Adaptive; delivery assurance Adaptive; delivery engineering Independent |
| Evidence required | a) a portfolio plan: why these three first and those five dropped; b) a repeatable review and operations mechanism (who checks what, when); c) at least one documented cross-department trade-off |
| Deliverables | Portfolio roadmap; review and operations mechanism; architecture decision records; two or more reusable assets |
| Metric language | Portfolio value (total cost, total hours, qualification rate, reuse rate) |
| Promotion | a) coordinates 3+ scenarios, all reaching acceptance; b) built a mechanism or asset used at least twice by others; c) makes an explainable trade-off under resource pressure |
| Fast-track | L4-grade assetisation on a single complex system (reused 3+ times) may fast-track, subject to unanimous review |
| Common misconception | Mistaking meeting volume for coordination ability |
| Failure mode | Everything in progress, nothing finished: no priorities means no priority |

### 6.5 L4 (Lead / System / Systemic)

**Table 7 — L4 requirements**

| Item | Content |
|---|---|
| Step-up | From delivering yourself to making the organisation able to deliver — output shifts from projects to mechanisms |
| Mark | Systemic |
| Scope of responsibility | Accountable for: the delivery system — quality gates, assetisation, capability building — so that results do not depend on one person. Not accountable for: industry standards and ecosystem |
| Typical scope | System design across project groups (10+ scenarios, multiple business lines); platform and toolchain; executives and cross-company partners; six months to a year; system-level budget |
| Mark requirements | All five domains at Systemic |
| Evidence required | a) SOPs and quality gates actually executed, with records; b) asset-library reuse data with hour savings; c) at least one person brought to independent scenario ownership, with handover records |
| Deliverables | Delivery system and gates; asset library and reuse metrics; capability development path; cross-project retrospective mechanism |
| Metric language | Business language (capital tied up, unit delivery cost, capitalised assets, margin impact) |
| Promotion | a) system in force for 2+ quarters with measurable drops in incidents and rework; b) asset reuse cuts similar-project hours by 30% or more; c) developed at least one L2+ person |
| Fast-track | An externally adopted method or standard may enter L5 review directly, with adoption evidence |
| Common misconception | Mistaking headcount for system capability — the test is whether results survive turnover |
| Failure mode | Policy nobody follows: gates are decorative and problems are absorbed by heroes |

### 6.6 L5 (Expert / Method / Industry)

**Table 8 — L5 requirements**

| Item | Content |
|---|---|
| Step-up | From working inside one organisation to outsiders adopting it — judgement moves outside |
| Mark | Industry |
| Scope of responsibility | Accountable for: a method adopted by the industry — standards, ecosystem, cross-enterprise transfer. The object is no longer a single organisation |
| Typical scope | Cross-industry method output (standards, curricula, open assets); industry methodology and ecosystem; industry bodies, partners and standards committees; one year and beyond |
| Mark requirements | Business literacy Industry; scenario engineering Industry; AI engineering Industry; delivery assurance Systemic; delivery engineering Industry |
| Evidence required | a) a method adopted by an external body or peer; b) 2+ cross-enterprise transfers outside the same group; c) a publicly verifiable standard, curriculum, open asset or signed report |
| Deliverables | Industry standard or methodology; ecosystem mechanism; publicly citable research |
| Metric language | Industry impact (adoption count, ecosystem partners, shift in practice) |
| Promotion | a) method adopted by 2+ enterprises outside the group with verifiable results; b) a substantive role in an industry body or standards effort; c) developed at least one L3+ person |
| Fast-track | Judged only by external adoption; self-certification is not accepted |
| Common misconception | Mistaking speaking volume for influence |
| Failure mode | Method stays in talks and articles: no external enterprise has actually run it |

### 6.7 Failure modes across levels

**Table 9 — Failure modes**

| Level | Typical failure | One-line diagnosis |
|---|---|---|
| L1 | Uncleaned handover | Work is done, nobody else can pick it up |
| L2 | No users | The system is live, the process is unchanged |
| L3 | Doing everything | No trade-off means no priority |
| L4 | Empty governance | Gates on paper, problems absorbed by heroes |
| L5 | Talking, not running | No external enterprise actually runs it |

---

## 7 Capability domain requirements

### 7.1 Domains

**Table 10 — Capability domains**

| Domain | Description |
|---|---|
| Business literacy | Understands industry mechanism, process and roles; describes problems in the customer's metrics |
| Scenario engineering | Translates vague demands into measurable, acceptable scenarios and locks the baseline |
| AI engineering and debugging | Model and retrieval selection, evaluation sets, fallbacks and refusal strategy |
| Delivery assurance | Data and permissions, cost and risk, schedule and stakeholders |
| Delivery engineering | Assetisation and reuse, so the second delivery costs less |

### 7.2 Mark sequence rule

Each domain shall traverse exactly five marks from L1 to L5, without two adjacent levels sharing a mark and without skipping. Descriptions violating this are void (see 5.2).

### 7.3 Step-up matrix

**Table 11 — Step-up matrix**

| Domain | L1 Guided | L2 Independent | L3 Adaptive | L4 Systemic | L5 Industry |
|---|---|---|---|---|---|
| Business literacy | Records process and roles from a given outline without error | Runs a process walkthrough alone; states inputs, outputs and owners | Spots metric conflicts and pseudo-requirements; identifies the real bottleneck | Judges where AI applies on a business line and writes a reusable checklist | Publishes an industry problem framework peers adopt |
| Scenario engineering | Completes scope and acceptance from a template without widening it | Confirms scope, measures the baseline, writes checkable acceptance actions | Prioritises a portfolio and explains what was dropped | Defines organisational admission and acceptance standards and enforces them | Outputs a scenario classification cited outside |
| AI engineering and debugging | Reproduces correct and failing output from a script and records the phenomenon | Builds a 20+ failure set; separates retrieval faults from generation faults | Resolves model/data/tool interaction faults and designs the fallback | Builds evaluation and regression mechanisms; turns quality into a gate | Proposes an evaluation method or quality metric adopted outside |
| Delivery assurance | Reports progress and completes handover from a checklist without dropping risks | Connects data and permissions; explains minimisation and masking; drives takeover | Coordinates dependencies and change; controls scope creep and cost overrun | Establishes data governance, incident response and delivery quality mechanisms | Contributes to industry delivery and compliance practice |
| Delivery engineering | Collects reusable snippets and instructions others can use | Produces at least one asset used in a second place | Designs the reuse interface; accumulates two or more assets and measures reuse | Builds an asset library with reuse metrics and visible hour savings | An asset is adopted externally or reused in the open |

---

## 8 Evaluation method

### 8.1 Modes

**8.1.1 Self-assessment** — the practitioner judges each item and outputs a suggested level and gap list. It is a locator, not a basis for levelling.

**8.1.2 Evidence review** — reviewers determine the level from submitted material, recording "verified", "to be verified" or "not met" for each item.

**8.1.3 Re-review** — per 8.4.

### 8.2 Evidence rules

a) each requirement needs at least one verifiable item, otherwise "to be verified";

b) material shall be independently verifiable by a third party;

c) customer information shall be redacted without losing verifiability;

d) one item may support several domains but shall not support two different levels.

### 8.3 Level determination

**8.3.1 Bucket rule** — the level is the highest level at which all five domains are satisfied simultaneously; a weighted average shall not be used.

**8.3.2 Threshold rule** — a domain satisfies a level when its mark requirement (6.2–6.6) is met.

**8.3.3 Gaps** — domains not meeting the next level are gaps; evidence per Annex B shall be supplied.

**8.3.4 Baseline** — if the five domains do not simultaneously meet L1, no level is assigned and the result is "below baseline".

### 8.4 Validity and re-review

Re-review shall occur on: a) change of role or scenario; b) cross-industry move; c) 24 months since the last review. A previous level is not inherited automatically.

### 8.5 Records

Records shall include subject, date, level, per-domain conclusions, gap list and reviewer signature, retained for at least three years.

---

## 9 Evaluation procedure

**9.1 Application** — the subject submits the self-assessment form (Annex C) and the evidence list (Annex B).

**9.2 Acceptance** — completeness is checked; incomplete submissions are returned within 10 working days.

**9.3 Document review** — reviewers examine items per 8.2 and record findings.

**9.4 Review** — at least two reviewers judge independently; disagreement is resolved by a third.

**9.5 Conclusion** — a level conclusion and gap list are issued with a validity period.

**9.6 Reconsideration and appeal** — within 15 working days, the subject may request reconsideration by reviewers not involved originally; the result is final.

---

## Annex A (normative) Mark determination

A.1 To determine a domain's mark, answer three questions: did someone else supply the method; have you handled exceptions beyond the standard case; has your output been copied by others.

**Table A.1 — Mark determination**

| Mark | Question | Typical counter-example |
|---|---|---|
| Guided | Completes with a template or instructions, no judgement | Did it once, cannot explain the steps |
| Independent | Completes the standard case unaided | Fails on a different scenario |
| Adaptive | Handled exceptions and explained trade-offs | Applies a "best practice" mechanically |
| Systemic | Mechanism others follow also works | The mechanism only works when you are present |
| Industry | Adopted outside, or involved in external standards work | Internal promotion only, no external citation |

A.3 Years of service, job titles and certificate counts shall not substitute for the above.

---

## Annex B (normative) Evidence checklist

**Table B.1 — Evidence packs by level**

| Evidence pack | L1 | L2 | L3 | L4 | L5 |
|---|---|---|---|---|---|
| Business diagnosis | Records process and roles from an outline | Quantifies the baseline in customer metrics | Separates real pain points from pseudo-requirements | Judges applicability boundaries for a business line | Defines an industry problem framework |
| Scenario and acceptance | Fills the template without widening | Confirms scope and acceptance independently | Prioritises a portfolio | Defines organisational admission and acceptance standards | Outputs a citable classification |
| Data and permissions | Connects data under guidance | Connects and explains masking | Designs cross-system permission tiers | Builds governance and audit mechanisms | Contributes to compliance discussion |
| AI debugging and evaluation | Reproduces failing output | Builds a 20+ failure set | Designs the evaluation system and fallback | Builds regression and quality gates | Proposes an adopted evaluation method |
| Delivery operations | Hands over from a checklist | Drives pilot and takeover | Coordinates parties and controls scope | Builds quality and incident mechanisms | Advances industry delivery practice |
| Assetisation | Collects reusable snippets | One asset used in a second place | Two or more assets with reuse measured | Asset library with reuse metrics | Asset adopted externally |

B.2 Forms: documents, run records, evaluation sets, reuse records, external adoption proof. All shall be verifiable by a third party.

---

## Annex C (informative) Self-assessment and scoring

C.1 Items are grouped by domain; each is scored 0, 1 or 2 for "not done", "done but unstable", "done consistently".

C.2 Scoring: compute each domain's average, then apply the thresholds of 8.3; the level is the highest one satisfied by all five domains.

C.3 Reference thresholds (0–2): Guided 0.4, Independent 0.9, Adaptive 1.3, Systemic 1.6, Industry 1.85.

C.4 A self-assessment shall also output the gap list and the evidence packs to supply.

C.5 Online tool: https://fde.0706.tech/self-check/ (Chinese interface).

---

## Annex D (informative) External level ranges and market salary bands

D.1 External level ranges are given in Table D.1. They are compiled from public information, are not official for any company, and these systems have been reformed repeatedly.

**Table D.1 — External level ranges**

| Level | Company A | Company B | Company C | Company D | Confidence |
|---|---|---|---|---|---|
| L1 | P4–P5 | 1-1 – 2-1 | T1.3–T2.1 | T4–T5 | Medium |
| L2 | P5–P6 | 2-1 – 2-2 | T2.1–T2.3 | T5–T6 | High |
| L3 | P6–P7 | 2-2 – 3-1 | T2.3–T3.1 | T6–T7 | Medium |
| L4 | P7–P8 | 3-1 – 3-2 | T3.1–T3.3 | T7–T8 | Medium |
| L5 | P8–P9 | 3-2 – 4-1 | T3.3–T4 | T8–T9 | Low |

Note: no exact mapping is provided, because none exists officially; published mappings are third-party reconstructions and would be misused as recruiting promises.

D.2 Market salary bands are given in Table D.2: annual salary in CNY thousands, gross, including bonus, excluding equity, basis October 2026, derived from job postings and cross-checked against salary reports.

**Table D.2 — Market salary bands**

| Level | Suzhou | Hangzhou | Shanghai | Beijing / Shenzhen |
|---|---|---|---|---|
| L1 | 12–20 | 14–23 | 16–26 | 18–30 |
| L2 | 20–33 | 23–38 | 26–42 | 30–48 |
| L3 | 32–52 | 36–59 | 42–68 | 48–78 |
| L4 | 50–85 | 56–95 | 65–110 | 75–130 |
| L5 | 80–130 | 90–145 | 100–170 | 120–200 |

Note 1: Hangzhou has no separately published band; the figure is interpolated between Suzhou and Shanghai.

Note 2: Industry differences are significant; one figure shall not be applied across industries.

Note 3: These bands do not represent what any employer pays and are not a quotation or commitment.

---

## Bibliography

[1] Standardization Law of the People's Republic of China, revised 2017.

[2] GB/T 1.1—2020, Guidelines for standardization — Part 1.

[3] GB/T 20000.1, Standardization and related activities — General vocabulary.

[4] 0706 Technology (Suzhou) Co., Ltd. FDE Industry Report 2026. 2026.

[5] 0706 Technology (Suzhou) Co., Ltd. Drafting notes for the FDE Level System. 2026.

---

© 2026 0706 Technology (Suzhou) Co., Ltd. Licensed under CC BY 4.0; cite the standard number and version. The Chinese text prevails.
