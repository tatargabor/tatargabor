# Hi, I'm Gabor Tatar

Software engineer building AI-powered development tools at [ITLine Kft.](https://itline.hu)

---

## wt-tools — Autonomous Orchestration for Claude Code

My main project: give it a spec, get merged features. wt-tools turns specification documents into parallel, autonomous Claude Code agents that implement, test, and merge — while you sleep.

### The ecosystem

| Repository | Description |
|------------|-------------|
| [**wt-tools**](https://github.com/tatargabor/wt-tools) | Core — sentinel, orchestration, worktrees, memory, GUI, MCP server |
| [wt-project-base](https://github.com/tatargabor/wt-project-base) | Base project knowledge plugin — common rules for all project types |
| [wt-project-web](https://github.com/tatargabor/wt-project-web) | Web project knowledge plugin — web-specific rules, templates, patterns |
| [wt-spec-capture](https://github.com/tatargabor/wt-spec-capture) | Chrome extension — capture business specs from existing websites |

### How it works

```
spec.md --> sentinel --> orchestrate --> worktrees (parallel) --> merged features
                              |
                 +------------+------------+
                 v            v            v
              Ralph        Memory       Verify
              loops        recall       & merge
```

---

*Built and used in production by [ITLine Kft.](https://itline.hu) and [Zengo Kft.](https://zengo.eu)*
