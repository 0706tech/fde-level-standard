# FDE Level Standard (2026 edition)

[中文](./README.md) ｜ **English**

> Five levels, two tracks. Level follows **scope of responsibility**, not technical depth.

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](./LICENSE)
[![Version](https://img.shields.io/badge/version-2026.1-blue)](./standard/versions.json)

- Site: <https://fde.0706.tech/>
- Version: **2026.1** (effective 2026-10-31)
- Maintained by: 0706 Technology (Suzhou) Co., Ltd.

---

## What this is

A capability standard for **Forward Deployed Engineers** — the people who sit inside a customer's process and deliver a working outcome, not a demo. It is written to be used by two audiences at once: employers writing job descriptions, and practitioners judging where they stand.

Five levels, two tracks:

| Level | Rank | Keyword | Mark | Responsible for | Titles (T / B) |
|---|---|---|---|---|---|
| L1 | 初级 | 执行 | guided | 任务 | 初级交付工程师 / 初级业务分析 |
| L2 | 中级 | 独立 | solo | 场景 | 交付工程师 / 场景交付顾问 |
| L3 | 高级 | 统筹 | adaptive | 项目群 | 高级交付工程师 / 高级场景顾问 |
| L4 | 资深 | 体系 | systemic | 组织体系 | 资深交付工程师 / 场景交付负责人 |
| L5 | 专家 | 方法 | industry | 行业方法 | 交付专家 / 场景专家 |

- **Marks** map one-to-one onto levels: Guided → Independent → Adaptive → Systemic → Industry.
- Every domain completes all five marks from L1 to L5. **Two adjacent levels sharing a mark is a defect** — that domain can no longer tell them apart.
- The two tracks share one ruler: same scope of responsibility, same salary band width, different capability weighting.

### Five marks

| key | Name | Meaning |
|---|---|---|
| guided | 依循 | 有模板或指引时能完成，不需要自己判断 |
| solo | 独立 | 没有指引也能独立完成标准情形 |
| adaptive | 应变 | 能处理异常与非标准情形，并做出取舍 |
| systemic | 系统 | 能把做法固化为机制或标准，供他人照做 |
| industry | 行业 | 能影响外部：被同行采纳，或参与标准制定 |

## What this is NOT

- **Not a national qualification.** “Forward Deployed Engineer” is not an occupation in China's national occupation classification. We issue no certificates and run no examinations.
- **Not a skills exam.** There is no written test. Capability items are observation dimensions; levelling rests on submitted material and scope.
- **Not a salary promise.** Salary bands are estimates from public sources, not what any employer pays, and not a quotation from us.
- **Not an official big-tech mapping.** Level ranges are compiled from public information; these systems have been reformed repeatedly.

## Layout

```
standard/     Standard text (Markdown, by year and language) and the version index
schema/       levels.json and JSON Schema (machine-readable)
assets/       Five-level ladder, as a single SVG
examples/     Job description templates and evidence-pack checklists
.github/      Issue templates (correction / proposal / industry adapter)
```

## How to use it

**Employers** — start from `examples/jd-templates/`, then ask for the six evidence packs in interview instead of asking whether someone “knows” something.

**Practitioners** — read `standard/2026/zh-CN/standard.md` (Chinese) and work backwards from the evidence packs.

**Integrators** — depend only on `levels[].id` and `levels[].mark` in `schema/levels.json`; both value sets only grow, so they are safe to hard-code.

## Citation

```bibtex
@misc{fde-level-2026,
  title  = {FDE Level Standard (2026 edition)},
  author = {{0706 Technology (Suzhou) Co., Ltd.}},
  year   = {2026},
  note   = {Version 2026.1},
  url    = {https://fde.0706.tech/}
}
```

## Language note

The Chinese text prevails. This English README is a working translation provided for reference.

## Licence

Text and examples: **CC BY 4.0** (attribution required; commercial use and adaptation allowed). Machine-readable data: **MIT**. Name and mark usage is restricted — see [TRADEMARK.md](./TRADEMARK.md).

## Contributing

See [CONTRIBUTING.md](./CONTRIBUTING.md) and [GOVERNANCE.md](./GOVERNANCE.md). Three issue templates are ready: correction, proposal, industry adapter.
