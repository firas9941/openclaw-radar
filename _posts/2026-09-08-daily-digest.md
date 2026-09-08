---
layout: post
title: "Ecosystem Digest — 2026-09-08"
date: 2026-09-08 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-09-08
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 389,150 | 4 | 4 | 10 | 0 |
| **hermesagent** | 243,065 | 6 | 3 | 6 | 1 |
| **ZeroClaw** | 32,740 | 15 | 6 | 8 | 0 |
| **IronClaw** | 12,609 | 1 | 0 | 0 | 0 |
| **Moltis** | 2,847 | 0 | 0 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 389,150 · **Open issues:** 6,322 · **Last push:** <1h ago

### ✅ Merged PRs
- [#141740](https://github.com/openclaw/openclaw/pull/141740) fix(update): identify blocked finalizer child processes
- [#141696](https://github.com/openclaw/openclaw/pull/141696) fix(ui): respect empty thinking choices
- [#141751](https://github.com/openclaw/openclaw/pull/141751) refactor(qa): remove unused script test accessors
- [#141741](https://github.com/openclaw/openclaw/pull/141741) test: skip browser assets in config RPC fixtures
- [#141749](https://github.com/openclaw/openclaw/pull/141749) fix(ui): show the number of displayed Usage sessions
- [#141726](https://github.com/openclaw/openclaw/pull/141726) refactor(web): share HTML tag scanning
- [#140579](https://github.com/openclaw/openclaw/pull/140579) fix(config): preserve authored settings through updates and setup
- [#141562](https://github.com/openclaw/openclaw/pull/141562) fix(update): recover stale runs without stopping healthy gateways
- [#137592](https://github.com/openclaw/openclaw/pull/137592) fix(build): sanitize direct tsdown declarations
- [#125900](https://github.com/openclaw/openclaw/pull/125900) fix(ui): avoid duplicate model auth reads on chat load

### 🐛 New Issues
- [#141765](https://github.com/openclaw/openclaw/issues/141765) [Feature]: Find people through your agent 💬1
- [#141747](https://github.com/openclaw/openclaw/issues/141747) Runtime scaffolding (`<system-reminder>`) injects ~686 tokens/turn into model input with no opt-out `P2` `clawsweeper:needs-info` `impact:session-state` `issue-rating: 🦪 silver shellfish` 💬1
- [#141745](https://github.com/openclaw/openclaw/issues/141745) [Feature]: Query and page automation run history from the CLI `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `issue-rating: 🌊 off-meta tidepool` `impact:ux-friction` 💬1
- [#141743](https://github.com/openclaw/openclaw/issues/141743) Default Ollama path: repeated unknown-tool calls run unbounded; loop detection is off by default and a block resets the two-strike counter `maintainer` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `impact:session-state` `impact:crash-loop` `P0` `issue-rating: 🦞 diamond lobster` `impact:ux-release-blocker` 💬1

### 🔒 Closed Issues
- [#139485](https://github.com/openclaw/openclaw/issues/139485) [Bug]: Managed upgrade leaves gateway offline while finalization remains nonterminal
- [#141709](https://github.com/openclaw/openclaw/issues/141709) Consolidate web_fetch HTML tag scanning without changing extraction
- [#141748](https://github.com/openclaw/openclaw/issues/141748) Usage Sessions card reports matching rows as shown
- [#141753](https://github.com/openclaw/openclaw/issues/141753) config-audit.jsonl stops recording Aug 21; no live audit log resumes after the Sept 5 workspace migration

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 243,065 · **Open issues:** 40,604 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.9.7](https://github.com/NousResearch/hermes-agent/releases/tag/v2026.9.7) — Hermes Agent v0.21.1 (v2026.9.7)

### ✅ Merged PRs
- [#105493](https://github.com/NousResearch/hermes-agent/pull/105493) fix(tui): match the redo chord case-insensitively so Cmd+Shift+Z works on extended-key terminals
- [#90674](https://github.com/NousResearch/hermes-agent/pull/90674) fix(tui): restore Shift+letter case in the composer for extended-key terminals
- [#105448](https://github.com/NousResearch/hermes-agent/pull/105448) test: Desktop deadline checks no longer race CI scheduling
- [#105451](https://github.com/NousResearch/hermes-agent/pull/105451) fmt(js): `npm run fix` auto-fix
- [#105442](https://github.com/NousResearch/hermes-agent/pull/105442) fix: cron and local DMs reach an open Desktop Bot Chat
- [#105374](https://github.com/NousResearch/hermes-agent/pull/105374) chore: release v0.21.1 (2026.9.7)

### 🐛 New Issues
- [#105497](https://github.com/NousResearch/hermes-agent/issues/105497) [Bug] Desktop barge-in transcript can be silently dropped by stale `busy` closure in `submitVoiceTurn`
- [#105484](https://github.com/NousResearch/hermes-agent/issues/105484) [Feature]: env var to silence Qdrant "insecure connection" warning for same-network deployments `type/feature` `comp/plugins` `tool/memory` `P3` 💬1
- [#105483](https://github.com/NousResearch/hermes-agent/issues/105483) [Bug]: Telegram Rich Messages turn literal #89 references into headings `type/bug` `comp/gateway` `platform/telegram` `P2` `sweeper:risk-message-delivery`
- [#105477](https://github.com/NousResearch/hermes-agent/issues/105477) [Bug]: model picker probes /v1/models with an empty key for key_cmd providers — catalog collapses to one model `type/bug` `comp/cli` `area/auth` `area/config` `P2` 💬1
- [#105471](https://github.com/NousResearch/hermes-agent/issues/105471) gateway: _send_with_retry re-sends plain-text fallback after an in-loop timeout (residual after #14061) `type/bug` `comp/gateway` `P2` `sweeper:risk-message-delivery` 💬1
- [#105469](https://github.com/NousResearch/hermes-agent/issues/105469) [Bug]: Desktop — approval.respond fails closed on multi-profile installs because blocking-input events carry the ephemeral ui_session handle `type/bug` `P2` `sweeper:risk-session-state` `comp/desktop` `area/sessions` `area/profiles` 💬1

### 🔒 Closed Issues
- [#90663](https://github.com/NousResearch/hermes-agent/issues/90663) [Bug]: TUI (Ink) lowercases Shift+letter in prompt composer on Ghostty (macOS) — uppercase input is destroyed
- [#92703](https://github.com/NousResearch/hermes-agent/issues/92703) [Bug]: Telegram/Kanban notification traffic pollutes conversation context and degrades long-running sessions
- [#102644](https://github.com/NousResearch/hermes-agent/issues/102644) Compressor lazy path ignores providers.<name>.models.<id>.context_length (/usage shows catalog window)

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,740 · **Open issues:** 809 · **Last push:** 2h ago

### ✅ Merged PRs
- [#10638](https://github.com/zeroclaw-labs/zeroclaw/pull/10638) fix(gateway): seed the boot default from the first entry that has a model
- [#9939](https://github.com/zeroclaw-labs/zeroclaw/pull/9939) fix(cost): surface pricing-unavailable so silent $0 caps can't reassure
- [#10692](https://github.com/zeroclaw-labs/zeroclaw/pull/10692) fix(channels/whatsapp): bind transcription to the owning agent's provider
- [#10415](https://github.com/zeroclaw-labs/zeroclaw/pull/10415) fix(providers): attribute reliable stream errors to served model
- [#10671](https://github.com/zeroclaw-labs/zeroclaw/pull/10671) fix(daemon): accept channel instance composite key in heartbeat.target
- [#10669](https://github.com/zeroclaw-labs/zeroclaw/pull/10669) test(channels/discord): prove STT dispatch selects the agent's provider
- [#10465](https://github.com/zeroclaw-labs/zeroclaw/pull/10465) feat(runtime): enforce compact local prompt budget
- [#10649](https://github.com/zeroclaw-labs/zeroclaw/pull/10649) fix(ci): allow PR size label updates

### 🐛 New Issues
- [#10709](https://github.com/zeroclaw-labs/zeroclaw/issues/10709) [Docs]: Document Astra setup for API-key and Codex subscription providers `docs` `type:docs`
- [#10708](https://github.com/zeroclaw-labs/zeroclaw/issues/10708) [Feature]: Support active-response steering on OpenAI Responses WebSockets `enhancement`
- [#10707](https://github.com/zeroclaw-labs/zeroclaw/issues/10707) [Feature]: Support bounded programmatic tool calling through OpenAI Responses `enhancement`
- [#10706](https://github.com/zeroclaw-labs/zeroclaw/issues/10706) [Feature]: Preserve opaque reasoning state across OpenAI Responses call paths `enhancement`
- [#10705](https://github.com/zeroclaw-labs/zeroclaw/issues/10705) [Feature]: Support max reasoning effort for compatible OpenAI models `enhancement`
- [#10704](https://github.com/zeroclaw-labs/zeroclaw/issues/10704) [Feature]: Support asynchronous function tools with OpenAI Responses `enhancement`
- [#10702](https://github.com/zeroclaw-labs/zeroclaw/issues/10702) [Bug]: token-budget history trimming stops at the first turn boundary that fits, same hysteresis gap as the message cap `bug` `agent` `runtime` `agent:prompt` `priority:p3`
- [#10701](https://github.com/zeroclaw-labs/zeroclaw/issues/10701) [Bug]: a user message with an image attachment invalidates the whole history cache prefix, not just the new message `bug` `agent` `provider:compatible` `agent:prompt` `priority:p2`
- [#10700](https://github.com/zeroclaw-labs/zeroclaw/issues/10700) [Bug]: cost records carry a daemon-lifetime session id, so per-conversation spend cannot be separated `bug` `config` `observability` `priority:p2` 💬1
- [#10699](https://github.com/zeroclaw-labs/zeroclaw/issues/10699) [Bug]: cost ledger prices cache writes at the plain input rate, understating every cache miss by the write premium `bug` `config` `provider:anthropic` `provider:compatible` `priority:p2`
- [#10697](https://github.com/zeroclaw-labs/zeroclaw/issues/10697) [Bug]: ZeroCode ACP transcript drops assistant text emitted before a tool call; only post-last-tool text renders as the reply `bug` `runtime` `tool` `priority:p1` `follow-up` `zerocode` `risk:high` `channel:acp`
- [#10695](https://github.com/zeroclaw-labs/zeroclaw/issues/10695) [Feature]: Refresh ZeroCode sessions changed by another connected client `enhancement` `runtime` `priority:p2` `follow-up` `risk:medium` `zerocode` `channel:acp`
- [#10694](https://github.com/zeroclaw-labs/zeroclaw/issues/10694) [Bug]: PowerShell shell tests intermittently time out on Windows `bug` `ci` `runtime` `tool` `tests` `domain:ci` `priority:p2` `tool:shell` `risk:medium` `type:ci`
- [#10690](https://github.com/zeroclaw-labs/zeroclaw/issues/10690) [Bug]: Integrations page "Configure" link slugifies the provider display name instead of using the family key (Z.AI -> /config/providers.models/z-ai, path_not_found) `bug` `config` `gateway` `integration` `provider` `runtime` `priority:p2` `status:accepted` `risk:medium` `web` 💬1
- [#10689](https://github.com/zeroclaw-labs/zeroclaw/issues/10689) [Bug]: Telegram voice reply silently skipped when the reply starts with `[` (ElevenLabs v3 audio tags) `bug` `channel` `observability` `provider` `channel:core` `channel:telegram` `priority:p2` `status:accepted` `risk:medium` 💬1

### 🔒 Closed Issues
- [#10688](https://github.com/zeroclaw-labs/zeroclaw/issues/10688) [Bug]: WhatsApp Web voice notes are never transcribed: channel is built without the agent's transcription provider
- [#10326](https://github.com/zeroclaw-labs/zeroclaw/issues/10326) [Bug]: Reliable streaming errors report the requested model instead of the served pinned model
- [#10670](https://github.com/zeroclaw-labs/zeroclaw/issues/10670) [Bug]: heartbeat.target rejects a channel instance composite key (<type>.<alias>)
- [#10660](https://github.com/zeroclaw-labs/zeroclaw/issues/10660) [SANITIZED — possible injection attempt]
- [#10693](https://github.com/zeroclaw-labs/zeroclaw/issues/10693) [Bug]: ZeroCode silently ignores Enter submissions while showing Connected
- [#8720](https://github.com/zeroclaw-labs/zeroclaw/issues/8720) [Support]: Disable cachePoint for Bedrock Nova 2 Lite model via config file?

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,609 · **Open issues:** 1,514 · **Last push:** 18h ago

### 🐛 New Issues
- [#8081](https://github.com/nearai/ironclaw/issues/8081) Daily ironclaw failure taxonomy — 2026-09-07

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,847 · **Open issues:** 89 · **Last push:** 5d ago

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- ⚫ [#139026](https://github.com/openclaw/openclaw/issues/139026) Internal runtime-context block (<<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>>) leaks visibly into Telegram on stalled/partial-turn replies — 💬2 · <1h ago
- ⚫ [#139028](https://github.com/openclaw/openclaw/issues/139028) [SANITIZED — possible injection attempt] — 💬1 · 2d ago
- 🟢 [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬2 · 6d ago
- 🟢 [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 8d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 10d ago
- ⚫ [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬5 · 14d ago
- ⚫ [#98062](https://github.com/openclaw/openclaw/issues/98062) [Bug]: iOS app fails to connect over Tailscale CGNAT (100.x.x.x) — wss:// required but WebSocket upgrade silently dropped — 💬4 · 26d ago
- ⚫ [#93031](https://github.com/openclaw/openclaw/issues/93031) [Bug] v2026.6.6 cron migration: jobs migrated from jobs.json have blank agent_id — scheduler silently skips them — 💬3 · 29d ago
- ⚫ [#93139](https://github.com/openclaw/openclaw/issues/93139) Bug: write tool and exec heredocs insert literal \n instead of newlines in string content — 💬11 · 32d ago
- ⚫ [#99305](https://github.com/openclaw/openclaw/issues/99305) [Bug]: Bedrock provider — claude-sonnet-5 prompt caching broken (cache-control blocks not attached, zero cache hits) — 💬4 · 34d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### OpenAI — 1 new
- [[Index] Supporting Independent Journalism In Ukraine](https://openai.com/index/supporting-independent-journalism-in-ukraine/) _2026-09-07_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 5 new
- [Friends Don't Let Friends Use Ollama](https://reddit.com/r/LocalLLaMA/comments/1wa26pn/friends_dont_let_friends_use_ollama/) ↑695
- [I REALLY hope the new gemma 5 family sticks to the "chat model first" philsophy and doesn't fall into the Qwen trap](https://reddit.com/r/LocalLLaMA/comments/1w9ylhh/i_really_hope_the_new_gemma_5_family_sticks_to/) ↑446
- [MiniCPM5-2B Release Day](https://reddit.com/r/LocalLLaMA/comments/1w9skjz/minicpm52b_release_day/) ↑255
- [9 easy steps for llama.cpp, a local model, Freecad (and pi coding agent) to generate solid objects that sound mechanically good and can be also be 3D printed/milled](https://reddit.com/r/LocalLLaMA/comments/1w9r73k/9_easy_steps_for_llamacpp_a_local_model_freecad/) ↑123
- [After over a year of my nights and weekends, the Jenny app is done!](https://reddit.com/r/LocalLLaMA/comments/1w9wvkb/after_over_a_year_of_my_nights_and_weekends_the/) ↑117

### r/singularity — top 2 new
- [An experimental AI-created drug for an incurable lung disease had a surprising effect during trials: it made the body's biological age indicators drop by 6 years, towards a younger state.](https://reddit.com/r/singularity/comments/1wa1a5n/an_experimental_aicreated_drug_for_an_incurable/) ↑661
- [In 1962, one of the fathers of neural networks, Warren McCulloch, is asked if machines could one day care as humans do](https://reddit.com/r/singularity/comments/1wa5yw0/in_1962_one_of_the_fathers_of_neural_networks/) ↑442

---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
