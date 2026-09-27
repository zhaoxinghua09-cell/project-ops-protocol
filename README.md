# project-ops-protocol
## 许可说明 · License Notice

> **本仓库使用自定义许可，不是 MIT / Apache-2.0**。平台显示为 `Other`（NOASSERTION），
> 属识别算法的正常结果，**不代表本仓库处于无许可状态**。

- **权利状态**：全部内容保留所有权利（All Rights Reserved）。未经书面许可，
  不得复制、改编、再分发、公开传播或用于衍生作品。
- **可否引用**：可以。允许在**注明出处**的前提下引用与学术、公共讨论；
  引用时请同时标注仓库名、原文链接 `https://github.com/zhaoxinghua09-cell/project-ops-protocol`
  与权利人「赵兴华 / Steven Zhao·China」。
- **完整条款**：见仓库根目录 [LICENSE](LICENSE)。
- **联系**：zhaoxinghua06@126.com ｜ ORCID 0009-0001-0512-1237
- **品牌状态限定**：MedXpert、SynomosAI、LGD 等为相关项目标识，
  **均未申请实体注册、未申请商标注册**；出现仅作来源标识，
  不构成对法人实体或商标权的任何主张。
- **免责**：本仓库内容不构成法规意见或注册代理服务；关键数据以监管机构最新发布为准。

---


![LGD-powered](https://raw.githubusercontent.com/zhaoxinghua09-cell/lgd-theory/main/assets/badges/powered/lgd-powered-en.svg)
![LGD](https://raw.githubusercontent.com/zhaoxinghua09-cell/lgd-theory/main/assets/badges/lgd-aligned-en.svg)

**A lightweight operating protocol for serious projects that run across multiple AI sessions, agents and one (or more) humans.**

Proven in the field on a long-running multi-session build (100+ documents, 50+ tools, parallel AI sessions) — no lost state, no duplicated work, no collisions.

## What you get

- **Four layers**: Plan (layered battle map + honest watchlist) → Execute (measure first, reuse before rebuild) → Sync (append-only alignment board + milestone heartbeats) → Memory (relay note + handbook-first rules).
- **Seven standard artifacts** with one job each and a write rule (battle map, release ledger, topic ledger, alignment board, relay note, retrospective, handbook).
- **Eight hard rule cards** that prevent the common failure modes (lost context, silent overwrites, duplicated work, secret leakage, publishing too early).
- **LLM-as-judge quality rubric** (5 dimensions, ≥0.80 pass) plus a 30-second self-check for anything that goes public.
- **Day-1 and wrap-up checklists** you can paste into any project.

## Install (as an agent skill)

Copy the `SKILL.md` into your agent's skills directory (e.g. `~/.workbuddy/skills/project-ops-protocol/SKILL.md`, or `.claude/skills/...`), or clone this repo and point your skill loader at the `SKILL.md`.

```bash
git clone https://github.com/zhaoxinghua09-cell/project-ops-protocol
```

## Why it works (credits)

Borrowed, credited and adapted from best practices that are public:

- **Handbook-first / single source of truth** — GitLab's all-remote operating culture.
- **Orchestrator-worker + compressed findings + Memory** — Anthropic's multi-agent research system engineering notes.
- **Judge-gated publishing** — LLM-as-judge evaluation, small-sample early checks.
- **Plain files over heavy memory infra** — Letta's filesystem agents beating specialised memory tools on LoCoMo is a strong hint to start simple.

## License

© 2026 Zhao Xinghua (Steven Zhao) — [CC BY 4.0](LICENSE) · MedXpert × SynomosAI
