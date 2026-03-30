# Brainstormer Consulting

AI consulting company that takes ideas from rough concept to dev-ready deliverables. Built on the [Agent Companies](https://agentcompanies.io) protocol, powered by [brainstormer](https://github.com/auditmos/brainstormer) skills.

## Org Chart

```
CEO / Engagement Lead (brainstorm, lean)
  |-- Discovery Analyst     (ask)
  |-- Product Architect     (blueprint, carve)
  |-- Delivery Manager      (dispatch)
  |-- Lead Engineer         (tdd, ship)
```

## Engagement Pipeline

1. **Discovery** — Structured interviews to pressure-test the idea
2. **Requirements** — PRD formalized and submitted as GitHub issue
3. **Planning** — Tracer-bullet vertical slices saved to `./plans/`
4. **Dispatch** — Dependency-ordered GitHub issues (AFK/HITL classified)
5. **Implementation** — TDD with vertical slices, lint + ship

## Deploy on Paperclip

```bash
npx paperclipai onboard
```

Point it at this repo. Paperclip discovers the company manifest, creates agents, and starts heartbeats.

See [Paperclip docs](https://docs.paperclip.ing) for configuration.

## Solo Mode (Claude Code)

Works without Paperclip — clone and use directly with Claude Code:

```bash
git clone https://github.com/auditmos/brainstormer-co.git
cd brainstormer-co
# Use /brainstorm to start a full engagement
```

## Skills

All skills are sourced from [`auditmos/brainstormer`](https://github.com/auditmos/brainstormer):

| Skill | Purpose |
|-------|---------|
| ask | Discovery interview |
| blueprint | PRD creation |
| carve | Vertical-slice planning |
| dispatch | GitHub issue generation |
| tdd | Test-driven development |
| ship | Lint, commit, push |
| lean | MVP advisor |
| brainstorm | Full workflow orchestration |

## License

MIT
