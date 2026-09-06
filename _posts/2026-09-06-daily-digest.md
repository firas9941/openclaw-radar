---
layout: post
title: "Ecosystem Digest — 2026-09-06"
date: 2026-09-06 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-09-06
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 388,980 | 4 | 2 | 10 | 1 |
| **hermesagent** | 242,041 | 8 | 2 | 4 | 0 |
| **ZeroClaw** | 32,734 | 10 | 4 | 10 | 1 |
| **IronClaw** | 12,606 | 1 | 0 | 0 | 0 |
| **Moltis** | 2,847 | 0 | 0 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 388,980 · **Open issues:** 6,282 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.9.2](https://github.com/openclaw/openclaw/releases/tag/v2026.9.2) — openclaw 2026.9.2

### ✅ Merged PRs
- [#139491](https://github.com/openclaw/openclaw/pull/139491) fix(cron): preserve current-session delivery intent
- [#139612](https://github.com/openclaw/openclaw/pull/139612) fix: prevent browser profile permission hangs in Doctor
- [#139531](https://github.com/openclaw/openclaw/pull/139531) fix(agents): retain storage-failure retry and credential coverage
- [#139512](https://github.com/openclaw/openclaw/pull/139512) fix(cli): keep note text with Windows and Unicode line endings
- [#139607](https://github.com/openclaw/openclaw/pull/139607) fix(agents): keep isolated completion config and credentials together
- [#139357](https://github.com/openclaw/openclaw/pull/139357) fix(models): retain compatible catalogs after refresh failures
- [#139392](https://github.com/openclaw/openclaw/pull/139392) fix: avoid slow declaration builds during source-server updates
- [#139439](https://github.com/openclaw/openclaw/pull/139439) fix(gateway): record a transcript notice when a run fails before replying
- [#138177](https://github.com/openclaw/openclaw/pull/138177) fix(build): exclude private QA matrix from release bundles
- [#139581](https://github.com/openclaw/openclaw/pull/139581) refactor(ios): reuse shared integer conversion

### 🐛 New Issues
- [#139609](https://github.com/openclaw/openclaw/issues/139609) Session resolution decodes unrelated saved prompts `maintainer` `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:source-repro` `clawsweeper:linked-pr-open` `issue-rating: 🦞 diamond lobster` `impact:other` 💬1
- [#139603](https://github.com/openclaw/openclaw/issues/139603) Control UI: allow replacing an unusable Home session with a healthy session `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:needs-info` `impact:session-state` `issue-rating: 🦪 silver shellfish` `impact:ux-friction` 💬1
- [#139599](https://github.com/openclaw/openclaw/issues/139599) [SANITIZED — possible injection attempt] `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `impact:message-loss` `issue-rating: 🦞 diamond lobster` 💬1
- [#139594](https://github.com/openclaw/openclaw/issues/139594) [Bug]: Agent avatar no longer rendered on assistant messages in Control UI chat (regression in 2026.9.2) `bug` `regression` `P3` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1

### 🔒 Closed Issues
- [#139488](https://github.com/openclaw/openclaw/issues/139488) [Bug]: Dashboard current-session automations falsely fail delivery with an unrelated channel configured
- [#139619](https://github.com/openclaw/openclaw/issues/139619) Cron jobs with scheduledToolPolicy mode "trusted" are invisible to automations list/get/update for every scoped caller

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 242,041 · **Open issues:** 40,070 · **Last push:** 2h ago

### ✅ Merged PRs
- [#103943](https://github.com/NousResearch/hermes-agent/pull/103943) MCP servers named like a built-in toolset no longer vanish from the model (salvage #19793)
- [#103856](https://github.com/NousResearch/hermes-agent/pull/103856) fix(bot-mode): match scoped bot selection in reset guard
- [#103821](https://github.com/NousResearch/hermes-agent/pull/103821) feat(skills): Reddit and RSS feeds readable without a browser; multi-platform research sweeps
- [#103884](https://github.com/NousResearch/hermes-agent/pull/103884) Mid-turn user message no longer waits behind a foreground terminal command (yields it to background)

### 🐛 New Issues
- [#103987](https://github.com/NousResearch/hermes-agent/issues/103987) vision_analyze não processa imagens no Hermes Desktop (Windows 11) `type/bug` `tool/vision` `P2` `needs-repro` `comp/desktop` `platform/windows`
- [#103985](https://github.com/NousResearch/hermes-agent/issues/103985) [Bug]: Desktop — Hide from sidebar on a worktree lane is a silent no-op (live worktree re-add defeats the dismissal) `type/bug` `P3` `comp/desktop` 💬1
- [#103979](https://github.com/NousResearch/hermes-agent/issues/103979) Feishu/Lark: pinned lark-oapi==1.6.8 connects but receives no websocket event pushes (needs >= 1.7.3) `type/bug` `comp/gateway` `comp/plugins` `platform/feishu` `P3` `dependencies` `sweeper:risk-message-delivery`
- [#103978](https://github.com/NousResearch/hermes-agent/issues/103978) Claude Code OAuth auto-discovery logs the Claude CLI out (single-use refresh token) and conflicts with Anthropic's Consumer ToS — please add an opt-out `type/bug` `comp/agent` `provider/anthropic` `area/auth` `area/config` `P2` 💬1
- [#103974](https://github.com/NousResearch/hermes-agent/issues/103974) [Security] Kanban worker identity is env-presence, not lineage: grandchild `hermes chat` / worker shells become full workers — proposal: HERMES_KANBAN_OWNER_PID + scrub-by-default + CLI parity `type/bug` `comp/agent` `comp/cli` `comp/cron` `P3` `sweeper:risk-session-state`
- [#103973](https://github.com/NousResearch/hermes-agent/issues/103973) [Bug]: browser_exec crashes with UnicodeDecodeError on non-ASCII code under CJK-locale Windows (stdin path, cp936) — missing encoding='utf-8' on the exec call `type/bug` `duplicate` `tool/browser` `P3` `sweeper:risk-platform-windows` `platform/windows` 💬1
- [#103969](https://github.com/NousResearch/hermes-agent/issues/103969) Incomplete tool-call payloads: non-streaming path hard-stops where streaming retries, and valid-JSON-but-incomplete-code reaches the kernel `type/bug` `comp/agent` `tool/code-exec` `P2` 💬1
- [#103956](https://github.com/NousResearch/hermes-agent/issues/103956) [Bug]: Telegram LaunchAgent maintenance: Astra repeatedly refuses reload while Sol executes and verifies it `type/bug` `comp/agent` `tool/terminal` `platform/telegram` `provider/openai` `P3` `needs-repro`

### 🔒 Closed Issues
- [#30563](https://github.com/NousResearch/hermes-agent/issues/30563) MCP server name can silently collide with a native toolset; native wins with no warning
- [#103931](https://github.com/NousResearch/hermes-agent/issues/103931) Remote computer_use: drive cua-driver on a different machine over the network

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,734 · **Open issues:** 783 · **Last push:** 5h ago

### 🚀 New Releases
- [v0.8.5](https://github.com/zeroclaw-labs/zeroclaw/releases/tag/v0.8.5) — v0.8.5

### ✅ Merged PRs
- [#10088](https://github.com/zeroclaw-labs/zeroclaw/pull/10088) fix(multimodal): preserve attached images after source removal
- [#10376](https://github.com/zeroclaw-labs/zeroclaw/pull/10376) test(channels): guard production registration drift
- [#10631](https://github.com/zeroclaw-labs/zeroclaw/pull/10631) docs(mcp): add Parallel Search configuration example
- [#10628](https://github.com/zeroclaw-labs/zeroclaw/pull/10628) fix(tts): surface providers dropped for a missing api_key
- [#10348](https://github.com/zeroclaw-labs/zeroclaw/pull/10348) ci(codeql): align init and analyze on v4
- [#10420](https://github.com/zeroclaw-labs/zeroclaw/pull/10420) fix(skill): enforce release holds before squash merge
- [#9867](https://github.com/zeroclaw-labs/zeroclaw/pull/9867) ci(labels): automate PR size labels
- [#9726](https://github.com/zeroclaw-labs/zeroclaw/pull/9726) fix(runtime): make TaskRecord the single background lifecycle owner
- [#10624](https://github.com/zeroclaw-labs/zeroclaw/pull/10624) test(channels/matrix): prove the configured route reaches the routed STT provider
- [#10375](https://github.com/zeroclaw-labs/zeroclaw/pull/10375) fix(gateway): generate dashboard status contract

### 🐛 New Issues
- [#10647](https://github.com/zeroclaw-labs/zeroclaw/issues/10647) fix(hooks): mint per-attempt identities for nested SOP retries `bug` `agent` `runtime` `tool` `domain:security` `domain:architecture` `priority:p2` `channel:webhook` `tool:sop` `status:accepted` `follow-up` `risk:medium`
- [#10645](https://github.com/zeroclaw-labs/zeroclaw/issues/10645) fix(runtime): thread cost-tracking context into delegated sub-loops `bug` `agent` `config` `runtime` `tool` `tool:delegate` `domain:architecture` `priority:p1` `status:accepted` `follow-up` `risk:high`
- [#10644](https://github.com/zeroclaw-labs/zeroclaw/issues/10644) fix(runtime): bind background delegate results to an owner principal `bug` `agent` `runtime` `tool` `tool:delegate` `domain:security` `domain:architecture` `priority:p1` `status:accepted` `follow-up` `risk:high`
- [#10643](https://github.com/zeroclaw-labs/zeroclaw/issues/10643) fix(runtime): fail-closed approval enforcement for bounded child loop tools `bug` `agent` `config` `runtime` `tool` `tool:delegate` `security:policy` `domain:security` `domain:architecture` `priority:p1` `needs-maintainer-review` `status:accepted` `risk:high`
- [#10641](https://github.com/zeroclaw-labs/zeroclaw/issues/10641) [Feature] [Web]: Per-field cron schedule input `enhancement` `help wanted` `cron` `priority:p2` `status:accepted` `risk:medium` `web` 💬2
- [#10635](https://github.com/zeroclaw-labs/zeroclaw/issues/10635) [Bug]: Runtime profile cost limit does not reflect effective global daily budget `bug` `config` `runtime` `domain:security` `priority:p1` `status:accepted` `risk:high`
- [#10634](https://github.com/zeroclaw-labs/zeroclaw/issues/10634) [Feature]: Recover network-interrupted provider turns without replaying side effects `enhancement` `agent` `provider` `runtime` `provider:reliable` `domain:architecture` `priority:p2` `needs-maintainer-review` `zerocode` `risk:high` `channel:acp`
- [#10626](https://github.com/zeroclaw-labs/zeroclaw/issues/10626) TTS synthesizes text verbatim: Markdown and emoji are spoken aloud `bug` `channel` `provider` `channel:core` `priority:p2` `status:accepted` `risk:medium` 💬1
- [#10625](https://github.com/zeroclaw-labs/zeroclaw/issues/10625) Internal `[media attachment]` placeholder is delivered to users when a non-vision model is in use `bug` `channel` `provider` `runtime` `channel:core` `channel:matrix` `priority:p2` `status:accepted` `risk:medium` 💬2
- [#10619](https://github.com/zeroclaw-labs/zeroclaw/issues/10619) [Feature]: Anthropic prompt-cache passthrough for OpenAI-compatible providers (cache_control through translating gateways) `enhancement` `config` `provider` `provider:anthropic` `provider:compatible` `priority:p1` `status:in-progress` `risk:high` 💬1

### 🔒 Closed Issues
- [#10045](https://github.com/zeroclaw-labs/zeroclaw/issues/10045) [Bug]: Persisted image markers can retain temporary source paths and repeatedly warn
- [#10361](https://github.com/zeroclaw-labs/zeroclaw/issues/10361) [Task]: Add drift tests for channel production registration
- [#9593](https://github.com/zeroclaw-labs/zeroclaw/issues/9593) refactor(runtime): make TaskRecord the single lifecycle owner for background delegation
- [#7910](https://github.com/zeroclaw-labs/zeroclaw/issues/7910) Add Windows runtime test coverage for the self-update swap/rollback/sidecar paths

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,606 · **Open issues:** 1,511 · **Last push:** 23h ago

### 🐛 New Issues
- [#8074](https://github.com/nearai/ironclaw/issues/8074) Paired user's rejected action in a not-connected shared channel gets the pairing notice copy instead of channel-not-connected copy `bug` 💬1

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,847 · **Open issues:** 86 · **Last push:** 3d ago

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- ⚫ [#139026](https://github.com/openclaw/openclaw/issues/139026) Internal runtime-context block (<<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>>) leaks visibly into Telegram on stalled/partial-turn replies — 💬1 · 14h ago
- ⚫ [#139028](https://github.com/openclaw/openclaw/issues/139028) [SANITIZED — possible injection attempt] — 💬1 · 15h ago
- 🟢 [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬2 · 4d ago
- 🟢 [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 6d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 8d ago
- ⚫ [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬5 · 12d ago
- ⚫ [#98062](https://github.com/openclaw/openclaw/issues/98062) [Bug]: iOS app fails to connect over Tailscale CGNAT (100.x.x.x) — wss:// required but WebSocket upgrade silently dropped — 💬4 · 24d ago
- ⚫ [#93031](https://github.com/openclaw/openclaw/issues/93031) [Bug] v2026.6.6 cron migration: jobs migrated from jobs.json have blank agent_id — scheduler silently skips them — 💬3 · 27d ago
- ⚫ [#93139](https://github.com/openclaw/openclaw/issues/93139) Bug: write tool and exec heredocs insert literal \n instead of newlines in string content — 💬11 · 30d ago
- ⚫ [#99305](https://github.com/openclaw/openclaw/issues/99305) [Bug]: Bedrock provider — claude-sonnet-5 prompt caching broken (cache-control blocks not attached, zero cache hits) — 💬4 · 32d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

_No new official content detected in the last 24h._

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 5 new
- [AA Update! Here's how the Frontier ranks.](https://reddit.com/r/LocalLLaMA/comments/1w7y261/aa_update_heres_how_the_frontier_ranks/) ↑409
- [Qwen3.8-27B beat the Wikipedia game in 6 clicks.](https://reddit.com/r/LocalLLaMA/comments/1w7q92n/qwen3827b_beat_the_wikipedia_game_in_6_clicks/) ↑385
- [I've found myself using Local LLM's like 3D printers.](https://reddit.com/r/LocalLLaMA/comments/1w7thwv/ive_found_myself_using_local_llms_like_3d_printers/) ↑281
- [AA Update! Here's how the small models score.](https://reddit.com/r/LocalLLaMA/comments/1w7y3sa/aa_update_heres_how_the_small_models_score/) ↑245
- [The gap has closed, open source will win](https://reddit.com/r/LocalLLaMA/comments/1w825pc/the_gap_has_closed_open_source_will_win/) ↑167

### r/singularity — top 5 new
- [AGI achieved](https://reddit.com/r/singularity/comments/1w7z3f6/agi_achieved/) ↑2295
- [GPT-6-Astra Draws an Portrait in Canva](https://reddit.com/r/singularity/comments/1w7xe37/gpt6astra_draws_an_portrait_in_canva/) ↑1387
- [AI can do it all](https://reddit.com/r/singularity/comments/1w7xi2i/ai_can_do_it_all/) ↑855
- [GPT-6 Astra Has Beaten Portal, Becoming the First Model to Achieve This.](https://reddit.com/r/singularity/comments/1w8g7d0/gpt6_astra_has_beaten_portal_becoming_the_first/) ↑848
- [Are all the graphs just gonna look like this now?](https://reddit.com/r/singularity/comments/1w82zm5/are_all_the_graphs_just_gonna_look_like_this_now/) ↑741

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [OpenClaw v2026.9.2 🦞  | Reliability and performance improvements, GPT-6 Astra, and Muse Spark 1.3](https://reddit.com/r/openclaw/comments/1w8ejge/openclaw_v202692_reliability_and_performance/) ↑17
- [a dream-based memory consolidation engine for executive assistant agents](https://reddit.com/r/openclaw/comments/1w8fbf1/a_dreambased_memory_consolidation_engine_for/) ↑2

### X — @openclaw
- [OpenClaw v2026.9.2 is out 🦞

🔄 Restarts pick up where they left off
⚡ Long chats move faster
🧠 GPT-6 Astra joins the cre](https://x.com/openclaw/status/2096367438443262091) ↑0 🔁0 · recent


### X — @steipete
- [Can’t remember last time we had such a large jump in capabilities.](https://x.com/steipete/status/2096403459579015374) ↑0 🔁0 · recent
- [One step closer in building the harness I wanna use. The one thing that’s not yet there are cloud sessions, goal is seco](https://x.com/steipete/status/2096400749869830325) ↑0 🔁0 · recent
- [this one weird trick to make compaction and long running goals way better.](https://x.com/steipete/status/2096208734666309999) ↑0 🔁0 · recent
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
