# Hi, I'm Gabor

I build autonomous orchestration tools for AI-assisted software development. My focus: making Claude Code agents work reliably in parallel — with structure, quality gates, and measurable results.

**Website:** [setcode.dev](https://setcode.dev) | **Personal:** [gabor.setcode.dev](https://gabor.setcode.dev)

---

## What I'm working on

[**SET (Ship Exactly This)**](https://github.com/tatargabor/set-core) — Autonomous multi-agent orchestration for Claude Code.

Give it a spec, get merged features. Six pillars: **SPECIFY, DECOMPOSE, EXECUTE, SUPERVISE, VERIFY, LEARN.** Parallel agents in git worktrees, 7 quality gates, self-healing sentinel supervisor, deterministic output.

```
spec.md ──► digest ──► decompose ──► parallel agents ──► verify ──► merge ──► done
```

**1,500+ commits · 134K LOC · 100+ E2E runs · 376 capability specs**

Works on greenfield apps, brownfield codebases, and isolated units alike. SET itself is built with SET — every spec, every commit, through the same pipeline.

### The ecosystem

| Repository | What it does |
|---|---|
| [**set-core**](https://github.com/tatargabor/set-core) | Core orchestration engine — sentinel, quality gates, worktrees, memory, web dashboard |
| [set-voice-agent-delivery](https://github.com/tatargabor/set-voice-agent-delivery) | Voice agent — Soniox STT + Google TTS for spec-driven customer interaction |

Built-in modules: **Web** (Next.js, Prisma, Playwright) ships with set-core. Custom project types (fintech, healthcare, etc.) can be added as plugins.

---

### What I believe

Systems like SET can do the work of a full development team — given proper specifications and well-developed project types. This is the present, not the future.

Don't blame the model for underspecification. 90% of "AI failures" are gaps we left empty. SET exists to enforce structure (OpenSpec), verify output (quality gates), and recover from failures (sentinel + issue pipeline).

---

*Built and used in production by [ITLine Kft.](https://itline.hu) · [gabor@setcode.dev](mailto:gabor@setcode.dev)*
