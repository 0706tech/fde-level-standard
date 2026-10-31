# FDE 职级标准（2026 版） / FDE Level Standard

> 五级双通道：级别看**责任半径**，不看技术深度。
> Five levels, two tracks: level = **scope of responsibility**, not technical depth.

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](./LICENSE)
[![Version](https://img.shields.io/badge/version-2026.1-blue)](./standard/versions.json)

- 官网 / Site：<https://fde.0706.tech/>
- 版本 / Version：**2026.1**（生效 2026-10-31）
- 维护 / Maintained by：零七零六（苏州）科技有限公司

---

## 这是什么 / What this is

一套面向「前沿部署工程师（Forward Deployed Engineer, FDE）」的能力分级标准，
供**企业招聘**与**从业者自评**共同使用。分五级、双通道：

| 级 | 中文职级 | 关键词 | 档位 | 责任对象 | 岗位名（T / B） |
|---|---|---|---|---|---|
| L1 | 初级 | 执行 | guided | 任务 | 初级交付工程师 / 初级业务分析 |
| L2 | 中级 | 独立 | solo | 场景 | 交付工程师 / 场景交付顾问 |
| L3 | 高级 | 统筹 | adaptive | 项目群 | 高级交付工程师 / 高级场景顾问 |
| L4 | 资深 | 体系 | systemic | 组织体系 | 资深交付工程师 / 场景交付负责人 |
| L5 | 专家 | 方法 | industry | 行业方法 | 交付专家 / 场景专家 |

- **档位**（五档与五级一一对应）：依循 → 独立 → 应变 → 系统 → 行业
- 每域在 L1→L5 上恰好走完五档，**不允许相邻两级同档、也不允许跳档**
- 双通道共用责任刻度：同级别责任半径相同、薪酬区间相同，仅能力权重不同

### 五档定义 / Marks

| key | 名称 | 含义 |
|---|---|---|
| guided | 依循 | 有模板或指引时能完成，不需要自己判断 |
| solo | 独立 | 没有指引也能独立完成标准情形 |
| adaptive | 应变 | 能处理异常与非标准情形，并做出取舍 |
| systemic | 系统 | 能把做法固化为机制或标准，供他人照做 |
| industry | 行业 | 能影响外部：被同行采纳，或参与标准制定 |

## 不是什么 / What this is NOT

- **不是国家职业资格**：截至目前《国家职业分类大典》中没有「前沿部署工程师」这一职业。
- **不发证、不办考试**：本仓不提供任何认证服务。
- **不是薪酬承诺**：仓内薪酬区间为公开信息整理的市场估算，不代表任何雇主实际支付。
- **大厂职级非官方**：对标区间来自公开信息整理，各公司职级近年多次改革。

## 目录 / Layout

```
standard/     标准正文（Markdown，按年份与语言）与版本清单
schema/       机读数据 levels.json 与 JSON Schema（供系统接入）
assets/       五级一图流 SVG
examples/     示例 JD 模板与证据卡清单
.github/      issue 模板（纠错 / 提案 / 行业适配）
```

## 怎么用 / How to use

**企业**：按 `examples/jd-templates/` 里的模板发 JD；面试时按六张证据卡要材料。
**从业者**：读 `standard/2026/zh-CN/standard.md`，对照自己的证据卡找缺口。
**系统接入**：直接拉 `schema/levels.json`，只依赖 `levels[].id` 与 `levels[].mark` 两个字段做映射。

## 引用 / Citation

```bibtex
@misc{fde-level-2026,
  title  = {FDE 职级体系（2026 版）},
  author = {{零七零六（苏州）科技有限公司}},
  year   = {2026},
  note   = {Version 2026.1},
  url    = {https://fde.0706.tech/}
}
```

## 许可 / License

正文与示例：**CC BY 4.0**（署名即可商用、可改编）。机读数据：**MIT**。
名称与标识的使用限制见 [TRADEMARK.md](./TRADEMARK.md)。

## 参与 / Contributing

见 [CONTRIBUTING.md](./CONTRIBUTING.md) 与 [GOVERNANCE.md](./GOVERNANCE.md)。
纠错、提案、行业适配三类 issue 模板已备好。
