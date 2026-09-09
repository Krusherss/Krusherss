# hey, I'm Max

I run a 450-mechanism AI agent estate — hooks, skills, gates, and scripts — that governs how Claude Code behaves across sessions. Every repo here is a component extracted from that live system, not a weekend project. They run in production daily.

## enforcement and safety

**[claude-stale-read-gate](https://github.com/Krusherss/claude-stale-read-gate)** — prevent cross-session file clobbers with a content-hash ledger

**[claude-session-unlock](https://github.com/Krusherss/claude-session-unlock)** — session-scoped popup-unlock tokens for Claude Code hook gates

**[claude-decaying-flags](https://github.com/Krusherss/claude-decaying-flags)** — TTL-based disable flags that expire instead of persisting forever

**[claude-context-guard](https://github.com/Krusherss/claude-context-guard)** — warn before Claude Code silently compacts your context window *(archived — superseded by multi-hook architecture)*

## verification and trust

**[claude-citation-proof](https://github.com/Krusherss/claude-citation-proof)** — verify every web claim with a deeplink, screenshot, and archive

**[consensus-council](https://github.com/Krusherss/consensus-council)** — multi-model voting and debate for decisions that matter

**[acceptance-witness](https://github.com/Krusherss/acceptance-witness)** — OIDC-attested acceptance witness for AI agent task signoff

## observability

**[drift-detector](https://github.com/Krusherss/drift-detector)** — detect silent behavioral changes in LLM APIs before your users do

**[verdict](https://github.com/Krusherss/verdict)** — LLM prose linter, catch AI-tells before your readers do

## writing

**[governing-an-ai-agent](https://github.com/Krusherss/governing-an-ai-agent)** — lessons and contracts from governing a 450-mechanism AI agent estate
