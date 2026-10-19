<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/pathrule/.github/main/profile/pathrule-banner-dark.png">
    <img src="https://raw.githubusercontent.com/pathrule/.github/main/profile/pathrule-banner-light.png" alt="Pathrule" width="560">
  </picture>
</p>

<h3 align="center">Your AI forgets. Pathrule remembers.</h3>

<p align="center">
  The open-source knowledge layer for coding agents. Pathrule keeps what your project has learned as memories, rules and skills scoped to paths in your code, and hands Claude Code, Codex, Cursor, GitHub Copilot and Windsurf only what the task in front of them needs.
</p>

<p align="center">
  <a href="https://github.com/pathrule/pathrule"><img alt="Pathrule on GitHub: pathrule/pathrule" src="https://img.shields.io/badge/GitHub-pathrule%2Fpathrule-1f7a4c?style=for-the-badge&logo=github&logoColor=white"></a>
  <a href="https://www.pathrule.io"><img alt="Website: pathrule.io" src="https://img.shields.io/badge/Website-pathrule.io-2f6aa8?style=for-the-badge"></a>
</p>

<p align="center">
  <b>PathruleBench, 2,000 items:</b> 55% lower cost a chain · 2.7× fewer input tokens · 97% of memory probes passed · <a href="https://github.com/pathrule/benchmark">the numbers</a>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/pathrule/.github/main/profile/hero-dark.gif">
    <img src="https://raw.githubusercontent.com/pathrule/.github/main/profile/hero-light.gif" alt="Same request, same agent. On the right, Pathrule&#x27;s hook hands over the three notes filed for apps/web/dashboard before the agent writes a line." width="880">
  </picture>
</p>

<p align="center"><sub><i>Same request, same agent. On the right, Pathrule's hook hands over the three notes filed for <code>apps/web/dashboard</code> before the agent writes a line.</i></sub></p>

## Try it in two commands

```bash
npm i -g @pathrule/cli
pathrule setup --local    # no account: knowledge stays on this machine
```

Restart your agent. From the next session on, it gets the notes for the path it is about to touch, and saves new ones as it works.

## Why not just CLAUDE.md?

A CLAUDE.md file is read whole on every step, so every note your team adds makes every session cost more. Pathrule sends each prompt only what the path and the task need.

<div align="center">

| At 2,000 items of team knowledge | CLAUDE.md | Pathrule |
| :-- | :-: | :-: |
| Cost a chain of 8 sessions | $3.89–$4.21 | **$1.76–$1.89** |
| Input tokens a chain | 11.8–12.5 M | **4.3–4.7 M** |
| Memory probes passed | 89% | **97%** |
| A habit said once, followed later | 78% | **97%** |
| What a failing command taught, kept | 33% | **78%** |

</div>

<sub>Same agent, same prompts, same hidden checks: Claude Code with claude-sonnet-5-5 in Python, Go and TypeScript. Executable tests decide every pass; no model judges. Every chain is public in [pathrule/benchmark](https://github.com/pathrule/benchmark).</sub>

## Repositories

| Repository | What it holds | Licence |
| --- | --- | --- |
| **[pathrule](https://github.com/pathrule/pathrule)** | **Start here.** The open-source foundation: the knowledge store, the MCP server, the hooks, the CLI, the agent integrations, the Local Console and the VS Code extension. | Apache-2.0 |
| [benchmark](https://github.com/pathrule/benchmark) | PathruleBench: the open benchmark for memory in coding agents, with its fixtures, scenarios, hidden checks, harness and every published chain. | Apache-2.0 |
| [signals](https://github.com/pathrule/signals) | A small runtime SDK: your app reports the errors that matter, your agent sees where, and a fix counts only once your next release proves it. | Apache-2.0 |
| [patterns](https://github.com/pathrule/patterns) | Curated, path-scoped knowledge packages: ready-to-use bundles of memories, rules and skills. | Apache-2.0 |

Local mode is free and needs no account. [Pathrule Cloud](https://www.pathrule.io/products/cloud) adds team workspaces, sync, the web console and the Cloud model tier when your team wants them.

## Contributing

Every repository takes pull requests with a [DCO](https://developercertificate.org) sign-off (`git commit -s`). Read the repository's `CONTRIBUTING.md` first. Report a vulnerability privately to **security@pathrule.io** or through GitHub's private vulnerability reporting, never in a public issue.

<p align="center">
  <a href="https://www.pathrule.io">pathrule.io</a> · <a href="https://www.pathrule.io/docs/start/quickstart">Docs</a> · <a href="https://www.pathrule.io/changelog">Changelog</a> · <a href="https://x.com/pathrule_io">@pathrule_io</a> · hello@pathrule.io
</p>
