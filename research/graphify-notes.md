# Graphify Notes

## Upstream

Repository: https://github.com/safishamsi/graphify.git

Package: `graphifyy`

CLI command: `graphify`

## Project Use

Graphify should become the durable context layer for Business Pressure Test V2.

The first useful corpus is:

- `README.md`
- `AGENTS.md`
- `docs/`
- `research/`
- future source files under `src/`

## Expected Outputs

```text
graphify-out/
├── graph.html
├── GRAPH_REPORT.md
└── graph.json
```

## Operating Rule

Use Graphify as the map, not as a replacement for repo truth.

When a graph exists, future agents should read `graphify-out/GRAPH_REPORT.md` before broad exploration and then verify current files directly before editing.

## Current Status

Graphify is installed locally.

This repo does not yet have `graphify-out/`.

Do not claim graph coverage exists until the graph is generated.
