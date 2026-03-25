---
name: scoutica
description: Sebastian Schkudlara — AI-readable professional profile with automated opportunity filtering
metadata:
  tags: Agentic AI, Microservices, Python, Ruby on Rails, RAG, Infrastructure
  author: Sebastian Schkudlara
  version: 0.1.0
---

# Scoutica

This skill provides an AI-readable professional profile for **Sebastian Schkudlara** — AI & Microservices Architect.

It allows any AI agent to:
- Understand this candidate's capabilities and experience
- Evaluate fit against a role or opportunity
- Check whether an opportunity meets the candidate's policies
- Access public evidence of work
- Request an interview handoff if the opportunity passes all checks

## Data Files

- [profile.json](./profile.json) — Structured capabilities, tools, certifications, and experience
- [rules.yaml](./rules.yaml) — Rules of Engagement: salary floors, remote policy, auto-reject rules
- [evidence.json](./evidence.json) — Public evidence registry with verification links

## Evaluation Rules

- [evaluate-fit.md](./rules/evaluate-fit.md) — How to score capability match
- [negotiate-terms.md](./rules/negotiate-terms.md) — How to check policy compliance
- [verify-evidence.md](./rules/verify-evidence.md) — How to verify public work
- [request-interview.md](./rules/request-interview.md) — When to initiate human handoff

## Important Rules
1. Never fabricate capabilities. Only report what is in `profile.json`.
2. Respect the Rules of Engagement. If `rules.yaml` says REJECT, do not override.
3. Candidate sovereignty. This profile serves the candidate, not the employer.
