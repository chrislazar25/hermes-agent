# KANBAN — High-Velocity PR Pipeline

**Repo:** NousResearch/hermes-agent (via fork chrislazar25/hermes-agent)

## Triage / To Review

| Issue | Title | 👍 | Notes |
|-------|-------|----|-------|
| #18021 | SSE response.completed > 128KB (Open WebUI) | 6+1 | P2 gateway. Well-scoped. Has partial truncation on main already. |
| #9549 | Feishu markdown tables not rendering | 7 | P2. Multiple user-provided solutions, no maintainer response. |
| #15290 | Docker permission denied `/opt/data/config.yaml` | 6 | P2. NAS-specific, likely filesystem config issue. |
| #15895 | google-gemini-cli 429 despite healthy `/gquota` | 6 | P3. Root cause found: per-minute TPM/RPM limit. |
| #8270 | HTTP 400 on all OpenRouter models | 5 | P1. Duplicate API keys in .env identified as one root cause. |
| #22908 | Shift+Enter no longer inserts newline | 4 | P2. PR #23921 open but not merged. |
| #39549 | `hermes update` aborts with ValueError | 4 | P2. Half-updated state bug. |
| #7556 | `display.show_reasoning` ignored by API server | 5 | Clear gap, well-scoped, no comments. **CURRENT PICK** |
| #20874 | Mattermost thread-mode replies | 4 | P2 gateway. PR description filed as issue — already has a fix. |

## Skipped

| Issue | Reason |
|-------|--------|
| #5674 | Fixed on main (codex_runtime.py raw event iteration) |
| #5151 | Fixed on main (`_buffer_status`/`_flush_status_buffer` mechanism) |
| #8091 | Fixed on main (commit 8a48c58b) |
| #33439 | Release request — fix on main but unreleased. Not a code fix. |
| #3002 | Low priority setup issue |
| #10967 | Spam |
| #8526 | Terminal color cosmetic, P3 |
| #5732 | Related to #5674, fixed on main |
| #14448 | Vague Docker UX complaint |
| #9572 | P3 niche Copilot ACP adapter issue |
| #37549 | Desktop app flickering, P3 |

## Scoped / To Do

| Issue | Title | 👍 | Scope |
|-------|-------|----|-------|
| **#7556** | `display.show_reasoning` not honored by API server adapter | 5 | Small/Medium — add reasoning extraction + injection in API server chat completions path |

## Awaiting Review

| Issue | PR |
|-------|----|
| **#7556** | [chrislazar25/hermes-agent#1](https://github.com/chrislazar25/hermes-agent/pull/1) — include reasoning_content in API server responses |

## Done

| Issue | Notes |
|-------|-------|
| #7556 | Draft PR created. Fixes `display.show_reasoning` not honored by API server adapter. |

## In Progress (Build)

_None_

## Awaiting Review

_None_

## Done

_None_
