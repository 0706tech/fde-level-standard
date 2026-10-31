# FDE Level Standard (2026 edition)

> **Publisher**: 0706 Technology (Suzhou) Co., Ltd. ｜ **Version**: 2026.1 ｜ **Effective**: 2026-10-31
> **Licence**: CC BY 4.0 ｜ **Status**: public draft, errata welcome
> **Notice**: This is a capability reference, not a national qualification. We issue no certificates and run no examinations. This English text is a working translation; the Chinese version prevails.

## Chapter 0 Summary

Level is decided by **scope of responsibility**, not by technical depth and not by years of service. Five marks map one-to-one onto five levels: Guided → Independent → Adaptive → Systemic → Industry.

| Level | Rank | Keyword | Mark | Responsibility | Technical track | Business track |
|---|---|---|---|---|---|---|
| L1 | Entry | Execution | Guided | Tasks | Junior Delivery Engineer | Junior Business Analyst |
| L2 | Intermediate | Independent | Independent | Scenarios | Delivery Engineer | Scenario Delivery Consultant |
| L3 | Advanced | Coordination | Adaptive | Project groups | Senior Delivery Engineer | Senior Scenario Consultant |
| L4 | Lead | System | Systemic | Organisational systems | Lead Delivery Engineer | Head of Scenario Delivery |
| L5 | Expert | Method | Industry | Industry methods | Delivery Expert | Scenario Expert |

Two tracks share one ladder. Same level means same scope of responsibility and the same salary band width; only the capability weighting differs.

## Chapter 1 Naming and structure

### 1.1 Why level names are ordinary, and keywords are verbs

Level names (Entry, Intermediate, Advanced, Lead, Expert) exist so that an employer can attach them to a job description and a candidate can compare them with what they know from large technology companies. Keywords (Execution, Independent, Coordination, System, Method) answer a different question: what is this person responsible for at this level. Both appear together, as `L3 · Advanced · Coordination`.

### 1.2 Five marks, five levels, one-to-one

| Mark | Meaning | Level | Keyword |
|---|---|---|---|
| Guided | Completes the work with a template or instructions; no judgement required | L1 | Execution |
| Independent | Completes the standard case without guidance | L2 | Independent |
| Adaptive | Handles exceptions and non-standard cases, and makes trade-offs | L3 | Coordination |
| Systemic | Turns practice into a mechanism or standard others follow | L4 | System |
| Industry | Influences outside: adopted by peers, or shapes a standard | L5 | Method |

Three rules follow, and they are enforced by tests in the reference implementation:

1. **No two adjacent levels may share a mark.** If L2 and L3 sit at the same mark in a domain, that domain cannot distinguish the two levels and levelling collapses into impression.
2. **No skipping.** Moving up a mark requires evidence for that mark in that domain; overall seniority does not lift a domain.
3. **Every domain at every level has a concrete description.** The mark name is a scale; only the description can be judged.

## Chapter 2 Design principles

| # | Principle | Content | Why |
|---|---|---|---|
| 1 | Level follows scope of responsibility | Responsibility object (task → scenario → project group → organisational system → industry method), together with cost of failure and replaceability | Judging by skill produces "the strongest technologist is the most senior"; judging by years is disconnected from capability |
| 2 | Evidence over self-description | Each level requires submittable material: scope sheet, failure sample set, runbook, reuse record. Without material, write "to be verified" | Self-description cannot be verified and is systematically inflated. "To be verified" is a legitimate conclusion |
| 3 | Two tracks, one ruler | Technical and business delivery share scope, level and pay bands; only capability weighting differs | A single track systematically overvalues "it was built" and undervalues "it is used", while most failures happen in the latter |

### What this standard is not

| Not | Explanation |
|---|---|
| A national qualification | "Forward Deployed Engineer" is not in China's national occupation classification. No certificates, no examinations |
| A skills examination | No written test, no question bank score. Capability items are observation dimensions; the decision rests on material and scope |
| A salary promise | Salary bands are estimates from public sources. They do not represent what any employer pays, nor a quotation from us |
| A one-off assessment | Levelling expires: change of role, scenario or industry triggers re-review |

## Chapter 3 Method: how a level is calculated

**Scope of responsibility** is the product of three factors: what you are responsible for, what happens if it fails, and how replaceable you are.

| Dimension | L1 | L2 | L3 | L4 | L5 |
|---|---|---|---|---|---|
| Responsibility object | Task | Scenario | Project group | Organisational system | Industry method |
| Cost of failure | Rework of a task | One scenario stalls | A portfolio misses its quarter | Delivery capability degrades | Industry method misleads |
| Replaceability | High | Medium | Low within the team | Low within the organisation | Low across the industry |

**The five domains** are business literacy, scenario engineering, AI engineering and debugging, delivery assurance and delivery engineering. The fifth domain is our addition: assetisation is where a forward-deployed engineer differs from an outsourced developer, and folding it into delivery assurance dilutes it.

**The five marks** are the ladder inside each domain. A level is reached only when all five domains reach the mark required by that level. This is the bucket principle: averaging hides the domain that will fail.

## Chapter 4 The five levels

Each level is described by six items — scope of responsibility, typical scope, capability marks, observable evidence, deliverables and metric language — plus a step-up line, promotion criteria, fast-track rules, the most common misconception and the typical failure mode.

The full six-item tables are published on the standard site at `/levels/`, and in the Chinese edition of this document. The step-up line, which is the part people actually use when they argue about a level, is reproduced here:

| Level | Step-up |
|---|---|
| L1 | Baseline: from "can use the tools" to "can hand over one clean piece of work" |
| L2 | From delivering a task to owning an outcome — you start signing your name to a process |
| L3 | From doing one well to deciding which ones to do — the first time you hold the trade-off |
| L4 | From delivering yourself to making the organisation able to deliver — output shifts from projects to mechanisms |
| L5 | From working inside one organisation to outsiders adopting it — judgement moves outside |

### 4.1 The step-up matrix

| Domain | L1 | L2 | L3 | L4 | L5 |
|---|---|---|---|---|---|
| Business literacy | Records process and roles from a given outline | Runs a process walkthrough alone | Separates real pain points from pseudo-requirements | Judges where AI applies on a business line | Publishes an adopted problem framework |
| Scenario engineering | Completes scope and acceptance from a template | Confirms scope, baseline and acceptance | Prioritises a portfolio and explains what was dropped | Defines organisational admission standards | Publishes a cited scenario classification |
| AI engineering and debugging | Reproduces correct and failing output | Builds a 20+ failure set, separates fault classes | Resolves interaction faults and designs fallback | Builds evaluation and regression gates | Publishes an adopted evaluation method |
| Delivery assurance | Reports progress and completes handover | Connects data and permissions, drives pilot | Coordinates dependencies, controls scope creep | Builds governance and incident mechanisms | Contributes to industry practice |
| Delivery engineering | Collects reusable snippets | One asset used in a second place | Reuse interface, two or more assets, measured reuse | Asset library with quantified hour savings | Asset adopted externally |

### 4.2 Six evidence packs

Business diagnosis, scenario and acceptance, data and permissions, AI debugging and evaluation, delivery operations, assetisation. Each pack has a level-specific requirement, listed in the Chinese edition and on the standard site. If a pack is empty, the evidence for that level is incomplete.

## Chapter 5 Two tracks and transfer

| | Technical delivery | Business delivery |
|---|---|---|
| Primary line | Building the system: data access, evaluation, debugging | Defining the scenario: industry literacy, value proof |
| Capability weight | AI engineering 5, delivery engineering 5, others 3 | Business literacy 5, scenario engineering 5, others 3–4 |
| Judged on | Whether it runs and stays running | Whether it should be built, and whether it worked |

Transfer within a level is allowed and requires no re-levelling; it requires the core evidence of the other track. Cross-level transfer follows the normal promotion rules, never automatically.

## Chapter 6 Evaluation

Three steps: self-assessment, evidence review, re-review at 30/60/90 days. Self-assessment is a locator, not a verdict; it is systematically optimistic, which is why the review exists. A reviewer asks for material, not opinions, and records "to be verified" where material is missing.

## Chapter 7 Relationship to other systems

| System | Relation |
|---|---|
| National occupation system | No FDE occupation exists. Adjacent new occupations (AI trainer, generative AI application specialist) have their own graded certification; they are a different track |
| Industry FDE capability frameworks | Same core judgement (scope of responsibility) and compatible four-domain structure. This standard adds L5, splits the two tracks, and makes delivery engineering a first-class domain |
| Large technology company levels | No official public mapping exists and these systems have been reformed repeatedly. Our ranges are compiled from public information and marked by confidence |

## Chapter 8 Ranges and bands

### 8.1 Big-tech level ranges

| Level | Alibaba | ByteDance | Tencent | Baidu | Confidence |
|---|---|---|---|---|---|
| L1 | P4–P5 | 1-1 ~ 2-1 | T1.3–T2.1 | T4–T5 | Medium |
| L2 | P5–P6 | 2-1 ~ 2-2 | T2.1–T2.3 | T5–T6 | High |
| L3 | P6–P7 | 2-2 ~ 3-1 | T2.3–T3.1 | T6–T7 | Medium |
| L4 | P7–P8 | 3-1 ~ 3-2 | T3.1–T3.3 | T7–T8 | Medium |
| L5 | P8–P9 | 3-2 ~ 4-1 | T3.3–T4 | T8–T9 | Low |

Why no exact mapping: there is no official public table, published mappings are third-party reconstructions, and an exact claim would become a recruiting promise and a salary-negotiation anchor it cannot support.

### 8.2 Market salary bands

Annual salary in CNY thousands, gross, including bonus, excluding equity. Basis: job postings × 12–15 months, cross-checked against salary reports. These are not percentiles and not what any employer pays.

| Level | Suzhou | Hangzhou | Shanghai | Beijing / Shenzhen |
|---|---|---|---|---|
| L1 | 12–20 | 14–23 | 16–26 | 18–30 |
| L2 | 20–33 | 23–38 | 26–42 | 30–48 |
| L3 | 32–52 | 36–59 | 42–68 | 48–78 |
| L4 | 50–85 | 56–95 | 65–110 | 75–130 |
| L5 | 80–130 | 90–145 | 100–170 | 120–200 |

Hangzhou has no separately published band; the figure is interpolated between Suzhou and Shanghai. Industry differences are significant: the AI skill premium is about +73% in manufacturing, about +118% in consumer goods and about +16% in government. Do not use one number for all industries, and do not treat city differences as evidence of equal work paying differently.

## Chapter 9 Disclaimers and use

1. Not a national qualification. No certificates, no examinations, no accreditation.
2. Big-tech ranges and salary bands are compiled from public information and change with industry reform. They are not a promise of employment or pay.
3. Level is decided by scope of responsibility, not technical depth, and never by years alone.
4. When citing, keep the version number. When adapting, keep the attribution and do not use our name for your derived standard.

## Appendix A Terms

| Term | Definition |
|---|---|
| Scope of responsibility | Responsibility object × cost of failure × replaceability |
| Mark | One of five, mapping one-to-one onto levels |
| Step-up | The concrete change from the previous level |
| Evidence pack | One of six kinds of submittable material |
| Asset | Connector, template or evaluation set, judged by second use |
| Fast-track | Skipping normal promotion, subject to unanimous review |

## Appendix B Evidence material

Scope sheet, baseline table, failure sample set, acceptance sheet, runbook, incident review, reuse record, external adoption proof. Each is a template in the open-source repository.

## Appendix C Data not used

Average salaries of unknown provenance, community leaks, point-value mappings to big-tech levels, and employment-rate claims from training vendors.

---

© 2026 0706 Technology (Suzhou) Co., Ltd. Licensed under CC BY 4.0. The Chinese version prevails.
