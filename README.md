# grant-proposal-ai

English | [中文](README.cn.md) · [Research Skillbox](https://github.com/windyvictor/research-skillbox)

A grant and research-proposal writing skill for rationale, research content, technical routes, novelty, feasibility, prior work, expected outcomes, abstracts, and budgets.

## Why this skill

A strong proposal is not a set of polished sections. It is one connected argument: the problem motivates the objectives, the objectives decompose into research tasks, each task has a method and validation route, and the available foundation makes the plan credible.

### What you get

- A question–objective–task–method–evidence map before prose is expanded
- Drafts for the rationale, research content, technical route, novelty, feasibility, abstract, and budget explanation
- A clear distinction between verified prior work and planned future work
- A compliance checklist tied to the actual funder, year, category, and template

**Workflow:** identify the current call → map the research argument → draft the requested section → test internal alignment → list unresolved compliance items.

## Use it for

- Drafting or revising a complete proposal
- Improving one proposal section
- Designing a research plan and validation strategy
- Checking the current call, template, and submission constraints
- Adapting structured prompt patterns to the user's real materials

## Current-call discipline

Formal compliance depends on the funder, year, program category, current template, and institutional process. Numbers found in older books—word limits, budget ratios, project duration, item counts, or title rules—are historical examples until verified against the current call.

## Contents

- `SKILL.md`: task routing and integrity constraints
- `references/current-call-check.md`: call and template verification
- `references/proposal-writing-guide.md`: book-derived writing guidance and prompt patterns
- `references/research-plan-design.md`: question-method-evidence alignment
- `evals/`: behavioral cases

## Core rule

Never invent prior work, publications, data, policy, or results. Planned experiments stay in the future tense. When the current guide is unavailable, deliver a research-argument draft and list the unresolved compliance items.

## Install

```bash
git clone https://github.com/windyvictor/grant-proposal-ai.git
ln -s "$PWD/grant-proposal-ai" ~/.agents/skills/grant-proposal-ai
```

## License

MIT. Referenced books, calls, and official materials retain their original rights.

