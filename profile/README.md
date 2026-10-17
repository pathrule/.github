<p align="center">
  <img src="pathrule-banner.png" alt="Pathrule" width="640">
</p>

<h3 align="center">Your AI forgets. Pathrule remembers.</h3>

<p align="center">
  The open-source knowledge layer for coding agents. Pathrule keeps what your project has learned as memories, rules and skills scoped to paths in your code, and gives Claude Code, Codex, Cursor, GitHub Copilot, Windsurf and any MCP client only what the task in front of them needs, before they act.
</p>

<p align="center">
  <a href="https://www.pathrule.io">Website</a> · <a href="https://www.pathrule.io/docs/start/quickstart">Docs</a> · <a href="https://github.com/pathrule/pathrule">Source</a> · <a href="https://github.com/pathrule/benchmark">Benchmark</a> · <a href="https://www.pathrule.io/changelog">Changelog</a>
</p>

```bash
npm i -g @pathrule/cli
pathrule setup --local    # no account, no network, no model: knowledge stays on this machine
```

## Repositories

| Repository | What it holds | Licence |
| --- | --- | --- |
| [pathrule](https://github.com/pathrule/pathrule) | The open-source foundation: the knowledge store, the MCP server, the hooks, the CLI, the agent integrations, the Local Console and the VS Code extension. Published to npm as `@pathrule/*`. | Apache-2.0 |
| [benchmark](https://github.com/pathrule/benchmark) | PathruleBench: a benchmark of memory for coding agents, with its fixtures, scenarios, hidden checks, harness and every published chain. | Apache-2.0 |
| [agent-plugins](https://github.com/pathrule/agent-plugins) | The plugin marketplace for Claude Code and Codex: install Pathrule from inside the agent. | Apache-2.0 |
| [patterns](https://github.com/pathrule/patterns) | Curated, path-scoped knowledge packages: ready-to-use bundles of memories, rules and skills. | Apache-2.0 |
| [homebrew-tap](https://github.com/pathrule/homebrew-tap) | `brew install pathrule/tap/pathrule`: the standalone CLI for macOS and Linux. | Formula only |

Local mode is free, offline and needs no model. [Pathrule Cloud](https://www.pathrule.io/products/cloud) adds team workspaces, sync and the Cloud model tier, and is opt-in.

## Contributing

Every repository takes pull requests with a [DCO](https://developercertificate.org) sign-off (`git commit -s`). Read the repository's `CONTRIBUTING.md` first, and report a vulnerability privately to **security@pathrule.io** or through GitHub's private vulnerability reporting, never in a public issue.

<p align="center">
  <a href="https://www.pathrule.io">pathrule.io</a> · <a href="https://x.com/pathrule_io">@pathrule_io</a> · hello@pathrule.io
</p>
