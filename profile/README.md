<p align="center">
  <img src="https://raw.githubusercontent.com/canonhq/canon/main/docs-site/public/logo.svg" alt="Canon" width="80" />
</p>

<h1 align="center">Canon</h1>

<p align="center">
  <strong>Spec-driven development, automated.</strong><br/>
  Write structured specs in markdown — AI agents handle PR reviews, ticket sync, and code verification.
</p>

<p align="center">
  <a href="https://pypi.org/project/canonhq/"><img src="https://img.shields.io/pypi/v/canonhq?color=blue" alt="PyPI"></a>
  <a href="https://github.com/canonhq/canon/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-BSL_1.1-blue" alt="License"></a>
  <a href="https://canonhq.co/docs"><img src="https://img.shields.io/badge/docs-canonhq.co-green" alt="Docs"></a>
</p>

---

Documentation drifts the moment it's written. Specs live in Notion or Confluence, disconnected from the code they describe. Nobody knows if what shipped actually matches what was planned.

Canon fixes this by treating specs as **living programs** — structured markdown that AI agents continuously verify against your codebase.

<p align="center">
  <img src="https://raw.githubusercontent.com/canonhq/canon/main/static/screenshots/spec-detail.png" alt="Canon spec view" width="720" />
</p>

### What Canon Does

- **Spec-Aware PR Reviews** — AI analyzes diffs against relevant specs, flags coverage gaps
- **Bidirectional Ticket Sync** — Spec sections become Jira, Linear, or GitHub Issues. Close a ticket and the spec updates.
- **Code-Aware Verification** — Verifies acceptance criteria are actually implemented, not just that a ticket was closed
- **Coverage Dashboard** — Track spec completion across your org by repo, team, and status
- **CLI & MCP Server** — `canon` CLI for local workflows. MCP server integrates with Claude Code, Cursor, and Windsurf.

### Choose Your Path

| Path | Best for |
|------|----------|
| **[GitHub App](https://canonhq.co/docs/getting-started/installation.html)** | Teams wanting full automation — PR analysis, ticket sync, coverage dashboard |
| **[CLI](https://canonhq.co/docs/reference/cli.html)** | Individual developers — `canon setup`, `status`, `verify`, `sync`, `plan` |
| **[MCP Server](https://canonhq.co/docs/getting-started/installation.html#mcp-server)** | AI-assisted development — spec context in Claude Code, Cursor, Windsurf |
| **[Self-Hosted](https://canonhq.co/docs/guides/self-hosting.html)** | Full control — deploy on your own K8s cluster |

### Quick Start

```bash
pip install canonhq
canon setup
```

### Links

[Documentation](https://canonhq.co/docs/) · [Quick Start](https://canonhq.co/docs/getting-started/quickstart.html) · [Writing Specs](https://canonhq.co/docs/guides/writing-specs.html) · [Spec Format](https://canonhq.co/docs/reference/spec-format.html) · [Contributing](https://github.com/canonhq/canon/blob/main/CONTRIBUTING.md)
