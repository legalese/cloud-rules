# Legalese Cloud rules — agent skills marketplace

Install your Legalese Cloud account's deployed decision rules as an AI agent
skill. The agent **discovers** the rule a question needs and **runs** it (behind
your permission barrier) instead of reasoning the determination itself.

## Install (Claude Code / claude.ai)

```
/plugin marketplace add legalese/cloud-rules
/plugin install rules@legalese-cloud
```

The plugin registers the account-wide rules MCP server
(`https://mcp.legalese.cloud`, org resolved from your sign-in — no token is
baked in; OAuth runs on first use) plus a skill that primes the model on _when_
to use it.

## Also in this marketplace: write L4

The same marketplace advertises the **L4 authoring plugin** (from
[`legalese/l4-ide`](https://github.com/legalese/l4-ide)) — expert guidance for
formalising legal text as typed, executable, verifiable rules:

```
/plugin install l4-computational-law@legalese-cloud
```

## Other harnesses

Use the L4 VS Code extension's **Install Skills Marketplace** to add the rules to
Cursor, Windsurf, Cline, VS Code (Copilot), or Claude Desktop in one click, or
point any MCP client at `https://mcp.legalese.cloud`.
