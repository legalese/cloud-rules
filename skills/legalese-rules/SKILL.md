---
name: legalese-rules
description: >-
  Find and run an account's deployed legal & policy decision rules on Legalese
  Cloud. Use when a question needs a formal, authoritative determination —
  eligibility, entitlements, deadlines, premiums, compliance, or a contract /
  regulation outcome — that should be computed by a deployed ruleset rather than
  reasoned out by hand.
---

# Legalese Cloud rules

This account's deployed decision rules are authoritative for what they cover.
When a question turns on one — eligibility, entitlements, deadlines, compliance,
a contract or regulation outcome — find the matching rule and run it; don't
reason the determination yourself, and if none matches, say so.

This plugin registers the **rules MCP** (`https://mcp.legalese.cloud`; org
resolved from your sign-in). Do everything through that one server — no
per-deployment or per-org endpoint needed:

- `search_rules` — find the rule(s) a question needs (space-separated keywords,
  matched as OR).
- `get_schema` — get a rule's input/output schema before you call it.
- `evaluate` — run the rule and answer from the authoritative result.

Cite the rule you ran.
