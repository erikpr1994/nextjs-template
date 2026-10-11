<!-- BEGIN:first-run -->

## First run

This block runs once, on the first session in a repo made from this template.

1. Run `/setup-matt-pocock-skills`.
2. Run `/wayfinder`, then `/impeccable init`, and use them to talk the idea through with the user.

Done when both have finished and the user confirms the idea is captured. Then delete this block, from `BEGIN:first-run` to `END:first-run`, and commit.

<!-- END:first-run -->

<!-- BEGIN:nextjs-agent-rules -->

## This is NOT the Next.js you know

This version has breaking changes — APIs, conventions, and file structure may all differ from your training data. Read the relevant guide in `node_modules/next/dist/docs/` (resolved from this file's directory; in monorepos the `next` package may not be visible from the repo root) before writing any code. Heed deprecation notices.

This block is written and re-added by `next dev` — verify at `node_modules/next/dist/server/lib/generate-agent-files.js`. Removing it from a diff only re-creates the uncommitted change; committing it with your work keeps the tree clean.

<!-- END:nextjs-agent-rules -->
