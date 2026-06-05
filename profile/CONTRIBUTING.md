# Contributing to Solarch

Thanks for the interest. Solarch is in active early-stage development — the API surface, node families, and edge semantics still move week to week — but feedback and contributions are welcome.

## Ways to help

- **File an issue.** Bugs, regressions, surprising UX, accessibility gaps. Reproduction steps + screenshot/gif when possible.
- **Open a discussion.** Feature requests, design feedback, architecture questions, philosophical disagreement with the *Surgical AI* thesis — all fair game.
- **Submit a PR.** Small, focused, single-purpose changes are easiest to review. Larger refactors: open a discussion first to align.

## Local development

The product is split into focused packages under the repo root:

| Path | What |
|---|---|
| `solarch-frontend/` | Vite + React 19 canvas + sketch UI |
| `solarch-backend/` | NestJS + Neo4j graph API (node CRUD, refine pipeline) |
| `web-old/` | Legacy Next.js workspace (being retired) |
| `solarch-frontend/src/motion/` | Remotion compositions for marketing motion videos |
| `assets/` | Rendered marketing gifs (referenced by this README) |

Each package has its own README/AGENTS notes for local setup.

## Working conventions

- **No emojis** in UI, code, or commit messages
- **Sans-serif typography** (Satoshi); mono is JetBrains Mono — never substitute
- **One canonical model.** All mutations go through `lib/project/` ops; no direct state mutation
- **Semantic edges.** New edge kinds must register a marker + color in `edge-style.ts` before use
- **Per-type inspectors.** Each node family ships its own editor; no generic JSON fallback

## Commit style

Conventional commits with short, focused subjects:

```
feat(canvas): add elbow edge mode
fix(refine-graph): orphan DTO repair edge inference
chore: bump remotion to 4.0.468
```

## License

By contributing, you agree your contributions are licensed under the [PolyForm Noncommercial License 1.0.0](./LICENSE) — same as the rest of the project. For commercial licensing inquiries, contact [info@solidea.tech](mailto:info@solidea.tech).
