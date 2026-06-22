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
resolved from your sign-in) — use it to find the rule a question needs. Run that
rule via its deployment (`https://mcp.legalese.cloud/<org>/<deployment>`) or
the `legalese` CLI (`curl -fsSL https://legalese.cloud/cli/install.sh | sh`).
Cite the rule you used.
