# Hi, I'm Gabor

I build tools that push Claude Code to its limits — not because it needs fixing, but because I want to see how far it can go.

Most of what I build will probably become native features eventually. That's the point — explore the frontier now, share what works, learn from it either way.

---

## What I'm working on

[**set-core**](https://github.com/tatargabor/set-core) — Autonomous multi-agent orchestration for Claude Code. Hand it a spec, get merged features.

```
spec.md ──► decompose ──► parallel agents ──► merge ──► done
```

Monorepo with plugin modules:

| Path | What it does |
|---|---|
| [**set-core**](https://github.com/tatargabor/set-core) | Core — sentinel, orchestration, worktrees, memory, GUI |
| `modules/web/` | Web project plugin — Next.js, Playwright, Prisma patterns |
| `modules/example/` | Reference plugin — Dungeon Builder domain |
| [set-spec-capture](https://github.com/tatargabor/set-spec-capture) | Chrome extension — capture business specs from existing sites |

Primary focus is web development, but the core tooling works on any codebase. External plugins can extend the framework for any domain.

---

*Built and used in production by [ITLine Kft.](https://itline.hu)*
