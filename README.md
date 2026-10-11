# Next.js template

Next.js + Claude Code config, ready for a new idea.

- **Skills**: relevant ones from Vercel (`vercel-labs/agent-skills`) and Emil Kowalski (`emilkowalski/skills`), all of Matt Pocock (`mattpocock/skills`), pinned in `skills-lock.json`.
- **Plugins**: impeccable and ponytail, via `.claude/settings.json` (auto-updating marketplaces).
- **MCP**: lazyweb, via `.mcp.json`. Export `LAZYWEB_API_KEY` in your shell.
- **Updates**: Dependabot runs daily and green PRs auto-merge; `Update skills` workflow refreshes skills daily. Both land on `main`.

## Start

1. **Use this template** on GitHub, clone, `pnpm install`.
2. Import the repo in Vercel so `main` deploys to production.
3. Open Claude Code; the first-run block in `AGENTS.md` takes it from there.
