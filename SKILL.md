---
name: scoutica
description: Sebastian Schkudlara — AI-readable professional profile and automated opportunity filtering
metadata:
  tags: AI, Agentic AI, LLM, MCP, Microservices, Python, Ruby, Kubernetes, RAG, AWS
  author: Sebastian Schkudlara
  version: 0.2.0
---

# Scoutica

This skill provides the AI-readable professional profile for **Sebastian Schkudlara**, Senior AI Infrastructure and Microservices Architect.

It allows any AI agent to:

- Understand Sebastian's capabilities and delivery context
- Evaluate fit against a role or opportunity
- Check whether an opportunity meets candidate rules
- Access public evidence of work
- Request human handoff when a role passes fit and policy checks

## Data files

- [profile.json](./profile.json) — structured capabilities, tools, platforms, languages and summary
- [rules.yaml](./rules.yaml) — engagement, remote policy, privacy and preferred-stack filters
- [evidence.json](./evidence.json) — public evidence registry and skill proof links

## Evaluation rules

- [evaluate-fit.md](./rules/evaluate-fit.md) — how to score capability match
- [negotiate-terms.md](./rules/negotiate-terms.md) — how to check policy compliance
- [verify-evidence.md](./rules/verify-evidence.md) — how to verify public work
- [request-interview.md](./rules/request-interview.md) — when to initiate human handoff

## Important rules

1. Never fabricate capabilities. Only report capabilities present in `profile.json` and supported by `evidence.json` where evidence is required.
2. Respect `rules.yaml`. If engagement, location or privacy rules block an opportunity, do not override them.
3. Candidate sovereignty. This profile serves Sebastian first, not the employer or recruiter.
4. First-contact outreach should be short, human and momentum-building. Do not lead with rate unless Sebastian explicitly asks.
