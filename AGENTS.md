# AGENTS.md

## Graphify

Graphify is the standing context layer for this repo.

Upstream: https://github.com/safishamsi/graphify.git

## Rules

- If `graphify-out/GRAPH_REPORT.md` exists, read it before broad file searches, architecture answers, or multi-file edits.
- If `graphify-out/wiki/index.md` exists, prefer the wiki map before raw file spelunking.
- If no `graphify-out/` directory exists yet, say the graph has not been initialized and use direct repo reads.
- For cross-module questions, prefer:
  - `graphify query "<question>"`
  - `graphify path "<A>" "<B>"`
  - `graphify explain "<concept>"`
- Use Graphify as the context map, then verify current code with direct file reads before editing.
- After meaningful changes in this graphified repo, run or recommend `graphify update .` when safe and useful.

## Current Status

Graphify CLI is installed locally, but this repo does not yet have a generated `graphify-out/` graph.

The foundation docs and research folder should become the first corpus for the project graph.
