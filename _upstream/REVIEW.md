# Upstream Review Checklist

Everything under `_upstream/` is quarantined: it does not load or run until adopted.
To adopt a file, `git mv` it back to its original path (drop the `_upstream/` prefix) in its own commit,
then update its status here.

**Status:** `unreviewed` | `adopt` (as-is) | `adapt` (modified) | `reject`

Folders are listed in review order: code that executes first, then prompts, then non-loaded material.

## hooks (5)

| File | Status | Notes |
|---|---|---|
| `hooks/hooks.json` | unreviewed | |
| `hooks/memory-persistence/pre-compact.sh` | unreviewed | |
| `hooks/memory-persistence/session-end.sh` | unreviewed | |
| `hooks/memory-persistence/session-start.sh` | unreviewed | |
| `hooks/strategic-compact/suggest-compact.sh` | unreviewed | |

## scripts (8)

| File | Status | Notes |
|---|---|---|
| `scripts/hooks/evaluate-session.js` | unreviewed | |
| `scripts/hooks/pre-compact.js` | unreviewed | |
| `scripts/hooks/session-end.js` | unreviewed | |
| `scripts/hooks/session-start.js` | unreviewed | |
| `scripts/hooks/suggest-compact.js` | unreviewed | |
| `scripts/lib/package-manager.js` | unreviewed | |
| `scripts/lib/utils.js` | unreviewed | |
| `scripts/setup-package-manager.js` | unreviewed | |

## tests (4)

| File | Status | Notes |
|---|---|---|
| `tests/hooks/hooks.test.js` | unreviewed | |
| `tests/lib/package-manager.test.js` | unreviewed | |
| `tests/lib/utils.test.js` | unreviewed | |
| `tests/run-all.js` | unreviewed | |

## mcp-configs (1)

| File | Status | Notes |
|---|---|---|
| `mcp-configs/mcp-servers.json` | unreviewed | |

## agents (9)

| File | Status | Notes |
|---|---|---|
| `agents/architect.md` | unreviewed | |
| `agents/build-error-resolver.md` | unreviewed | |
| `agents/code-reviewer.md` | unreviewed | |
| `agents/doc-updater.md` | unreviewed | |
| `agents/e2e-runner.md` | unreviewed | |
| `agents/planner.md` | unreviewed | |
| `agents/refactor-cleaner.md` | unreviewed | |
| `agents/security-reviewer.md` | unreviewed | |
| `agents/tdd-guide.md` | unreviewed | |

## commands (15)

| File | Status | Notes |
|---|---|---|
| `commands/build-fix.md` | unreviewed | |
| `commands/checkpoint.md` | unreviewed | |
| `commands/code-review.md` | unreviewed | |
| `commands/e2e.md` | unreviewed | |
| `commands/eval.md` | unreviewed | |
| `commands/learn.md` | unreviewed | |
| `commands/orchestrate.md` | unreviewed | |
| `commands/plan.md` | unreviewed | |
| `commands/refactor-clean.md` | unreviewed | |
| `commands/setup-pm.md` | unreviewed | |
| `commands/tdd.md` | unreviewed | |
| `commands/test-coverage.md` | unreviewed | |
| `commands/update-codemaps.md` | unreviewed | |
| `commands/update-docs.md` | unreviewed | |
| `commands/verify.md` | unreviewed | |

## skills (14)

| File | Status | Notes |
|---|---|---|
| `skills/backend-patterns/SKILL.md` | unreviewed | |
| `skills/clickhouse-io/SKILL.md` | unreviewed | |
| `skills/coding-standards/SKILL.md` | unreviewed | |
| `skills/continuous-learning/SKILL.md` | unreviewed | |
| `skills/continuous-learning/config.json` | unreviewed | |
| `skills/continuous-learning/evaluate-session.sh` | unreviewed | |
| `skills/eval-harness/SKILL.md` | unreviewed | |
| `skills/frontend-patterns/SKILL.md` | unreviewed | |
| `skills/project-guidelines-example/SKILL.md` | unreviewed | |
| `skills/security-review/SKILL.md` | unreviewed | |
| `skills/strategic-compact/SKILL.md` | unreviewed | |
| `skills/strategic-compact/suggest-compact.sh` | unreviewed | |
| `skills/tdd-workflow/SKILL.md` | unreviewed | |
| `skills/verification-loop/SKILL.md` | unreviewed | |

## rules (8)

| File | Status | Notes |
|---|---|---|
| `rules/agents.md` | unreviewed | |
| `rules/coding-style.md` | unreviewed | |
| `rules/git-workflow.md` | unreviewed | |
| `rules/hooks.md` | unreviewed | |
| `rules/patterns.md` | unreviewed | |
| `rules/performance.md` | unreviewed | |
| `rules/security.md` | unreviewed | |
| `rules/testing.md` | unreviewed | |

## contexts (3)

| File | Status | Notes |
|---|---|---|
| `contexts/dev.md` | unreviewed | |
| `contexts/research.md` | unreviewed | |
| `contexts/review.md` | unreviewed | |

## examples (6)

| File | Status | Notes |
|---|---|---|
| `examples/CLAUDE.md` | unreviewed | |
| `examples/sessions/2026-01-17-debugging-memory.tmp` | unreviewed | |
| `examples/sessions/2026-01-19-refactor-api.tmp` | unreviewed | |
| `examples/sessions/2026-01-20-feature-auth.tmp` | unreviewed | |
| `examples/statusline.json` | unreviewed | |
| `examples/user-CLAUDE.md` | unreviewed | |

## plugins (1)

| File | Status | Notes |
|---|---|---|
| `plugins/README.md` | unreviewed | |

## .claude (1)

| File | Status | Notes |
|---|---|---|
| `.claude/package-manager.json` | unreviewed | |

