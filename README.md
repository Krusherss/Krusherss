# hey, I'm Max

Two Claude Code sessions open the same file. One saves. The other saves on top of it. Nobody gets a warning. I built a content-hash gate to catch that, then kept finding more gaps. These repos are the tools that came out of it.

## enforcement and safety

**[claude-stale-read-gate](https://github.com/Krusherss/claude-stale-read-gate)** — prevent cross-session file clobbers with a content-hash ledger

**[claude-session-unlock](https://github.com/Krusherss/claude-session-unlock)** — session-scoped popup-unlock tokens for Claude Code hook gates

**[claude-decaying-flags](https://github.com/Krusherss/claude-decaying-flags)** — TTL-based disable flags that expire instead of persisting forever

**[claude-context-guard](https://github.com/Krusherss/claude-context-guard)** — warn before Claude Code silently compacts your context window *(archived — superseded by multi-hook architecture)*

## verification and trust

**[claude-citation-proof](https://github.com/Krusherss/claude-citation-proof)** — verify every web claim with a deeplink, screenshot, and archive

**[consensus-council](https://github.com/Krusherss/consensus-council)** — multi-model voting and debate for decisions that matter

**[acceptance-witness](https://github.com/Krusherss/acceptance-witness)** — OIDC-attested acceptance witness for AI agent task signoff

## writing

**[governing-an-ai-agent](https://github.com/Krusherss/governing-an-ai-agent)** — what I learned letting an AI agent manage its own hooks, gates, and rollback
