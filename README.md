# Joshua Garrison

I build business software by directing AI coding agents: Cursor, Claude Code,
Codex, and Grok Bots. I don't hand-write code. I design the data model, the
integrations, and the specs. Then I hand the work to agents, have separate
agents review it, and check the result against tests and CI before it ships.

That sits on 15+ years of enterprise IT: Active Directory and Entra ID, Azure
and Microsoft 365, identity and privileged access, networking and
virtualization, and Viewpoint Vista ERP security and integration.

Since 2014 I've worked in IT at a construction services company with several
operating companies, moving from system administrator to IT director. Since
January 2025 I've led technology innovation there: I design internal
business apps and direct AI agents to build them, and I run AI tool adoption
and training.

## Public projects

- **[Pitbull](https://github.com/jgarrison929/pitbull)**: a construction
  project controls platform (estimate, budget, field progress, cost, change
  orders). There's a [live demo](https://demo.pcserp.app) with no signup. The
  repo includes the `AGENTS.md` and `CLAUDE.md` files the agents work from,
  and a 5.0 rebuild is in progress in `v5/`.
- **[Summit Climb](https://github.com/jgarrison929/summit-climb-public)**: a
  browser climbing game whose global leaderboard is built to resist cheating:
  signed single-use run tokens, server-side score checks, and salted IP
  hashes. [Play it](https://summit-climb-production.up.railway.app).
- **[Boundshot](https://github.com/jgarrison929/boundshot-public)**: a
  browser multiplayer artillery game with a server-authoritative match
  engine and headless-browser end-to-end tests.
  [Play it](https://boundshot-production.up.railway.app).
- **[river-runtime](https://github.com/jgarrison929/river-runtime)**: an
  earlier agent runtime I designed, with tiered memory, an MCP server, and
  sub-agent dispatch. It's no longer active, but it stays up as a reference.

## How I work

I write the spec, break it into tasks, and hand them to agents. A different
agent reviews each change, and every failure an agent makes becomes a new
check for the next run. Changes go through issue-linked pull requests and
GitHub Actions. I've written up
[how I coordinate multiple AI agents](https://gist.github.com/jgarrison929/95b46194c52196724ed485dbc917e9c3)
and [the memory problem](https://gist.github.com/jgarrison929/2e848e7ae79878e0fe254c30e471d12a).
