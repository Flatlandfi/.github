<div align="center">
  <img src="https://flatlandfi.com/brand/mcp-icon-256.png" width="72" alt="Flatland" /><br /><br />
  <strong>Financial reasoning infrastructure for AI agents.</strong>
</div>

---

Flatland is a financial modeling engine that AI agents call via MCP or HTTP. It compiles typed financial models — named drivers, dependency graphs, assertions — into deterministic outputs with cryptographic receipts.

The engine never calls an LLM. It receives a model, computes the result, returns a signed receipt, and discards the inputs. Your models are client-owned files on your machine.

## What the engine does

| Capability | |
|---|---|
| **Typed models** | Named drivers with types, formulas, and assertions — not anonymous cells |
| **Deterministic compilation** | Same inputs, same outputs, every time. No hallucination surface. |
| **Cryptographic receipts** | Every compiled output is signed and client-owned |
| **Scenarios** | Named overrides compiled in parallel; diff any two |
| **Sensitivity analysis** | Rank assumptions by impact on any target driver |
| **Excel export** | Live formulas, rubric-scored output |

## Getting started

```bash
npx flatland-setup
```

One command configures Flatland for Claude Code or Cursor. Get an API key at [flatlandfi.com](https://flatlandfi.com) — first 50 answers free.

## Links

| | |
|---|---|
| Product & docs | [flatlandfi.com](https://flatlandfi.com) |
| MCP server | [smithery.ai/servers/flatlandfi/flatland](https://smithery.ai/servers/flatlandfi/flatland) |
| npm setup package | [npmjs.com/package/flatland-setup](https://www.npmjs.com/package/flatland-setup) |
| MCP source | [flatland-mcp](https://github.com/Flatlandfi/flatland-mcp) |
