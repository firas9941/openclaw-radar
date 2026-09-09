---
layout: post
title: "Ecosystem Digest — 2026-09-09"
date: 2026-09-09 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-09-09
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 389,255 | 9 | 5 | 10 | 1 |
| **hermesagent** | 243,469 | 7 | 6 | 6 | 0 |
| **ZeroClaw** | 32,748 | 15 | 0 | 5 | 0 |
| **IronClaw** | 12,608 | 2 | 0 | 0 | 0 |
| **Moltis** | 2,846 | 0 | 0 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 389,255 · **Open issues:** 6,442 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.9.3](https://github.com/openclaw/openclaw/releases/tag/v2026.9.3) — openclaw 2026.9.3

### ✅ Merged PRs
- [#142762](https://github.com/openclaw/openclaw/pull/142762) fix(ci): install Watch Rust toolchain for iOS beta
- [#142752](https://github.com/openclaw/openclaw/pull/142752) fix(android): stabilize remote image decode regression on Linux
- [#142714](https://github.com/openclaw/openclaw/pull/142714) chore(i18n): refresh native locales
- [#142763](https://github.com/openclaw/openclaw/pull/142763) test(ui): wait for applied config before holding refresh
- [#142567](https://github.com/openclaw/openclaw/pull/142567) fix(active-memory): model recall skipped when trigger lookup times out
- [#142729](https://github.com/openclaw/openclaw/pull/142729) docs(plugins): split the Google Meet page by reader job
- [#142735](https://github.com/openclaw/openclaw/pull/142735) ci(labeler): complete the google-meet and plugin reference globs
- [#141315](https://github.com/openclaw/openclaw/pull/141315) fix(voice-call): flush unmatched webhook upgrade rejects before destroy
- [#137192](https://github.com/openclaw/openclaw/pull/137192) fix(ui): localize core configuration labels and help
- [#142623](https://github.com/openclaw/openclaw/pull/142623) feat: show video previews in the chat composer

### 🐛 New Issues
- [#142781](https://github.com/openclaw/openclaw/issues/142781) [Bug]: Auto-selected session account makes claude-cli models report missing-auth and locks the composer
- [#142772](https://github.com/openclaw/openclaw/issues/142772) [Bug]: Slack Agent View “is working” status can remain after a completed turn until the desktop client restarts `bug` `bug:behavior` `P2` `clawsweeper:needs-info` `issue-rating: 🦐 gold shrimp` `impact:ux-friction` 💬1
- [#142770](https://github.com/openclaw/openclaw/issues/142770) 2026.9.3: failed update can leave forward-migrated Workshop state on 9.2 rollback; WebChat ACP binding also lacks conversationId `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `impact:crash-loop` `P0` `issue-rating: 🦞 diamond lobster` `maturity:stable` `impact:ux-release-blocker` 💬2
- [#142769](https://github.com/openclaw/openclaw/issues/142769) [Feature]: Opencode difference between go and zen `enhancement` `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `issue-rating: 🌊 off-meta tidepool` `impact:ux-friction` 💬1
- [#142755](https://github.com/openclaw/openclaw/issues/142755) [Bug]: Feishu workspace tools absent even after removing feishu_chat from manifest AND persisted installed index (follow-up to #140971) `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-security-review` `issue-rating: 🦪 silver shellfish` `impact:other` 💬1
- [#142754](https://github.com/openclaw/openclaw/issues/142754) Runtime context delivered as raw <<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>> text in a synthetic user turn — visible to the agent instead of staying in the structured carrier `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-product-decision` `clawsweeper:needs-security-review` `clawsweeper:needs-live-repro` `impact:session-state` `impact:security` `issue-rating: 🐚 platinum hermit` `impact:ux-friction` 💬1
- [#142753](https://github.com/openclaw/openclaw/issues/142753) [Bug] settled-finalization-fallback text leaks to user-facing delivery channels (e.g. qqbot) `P2` `clawsweeper:needs-info` `issue-rating: 🦐 gold shrimp` `impact:ux-friction` 💬1
- [#142747](https://github.com/openclaw/openclaw/issues/142747) Feature: standalone dictation add-on (universal OpenAI-compatible STT) `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-product-decision` `impact:auth-provider` `issue-rating: 🌊 off-meta tidepool` 💬1
- [#142744](https://github.com/openclaw/openclaw/issues/142744) Update failure: managed-service-handoff-unsafe-recovery (2026.9.3) `clawsweeper:needs-info` `P0` `issue-rating: 🦪 silver shellfish` `impact:ux-release-blocker` 💬1

### 🔒 Closed Issues
- [#142771](https://github.com/openclaw/openclaw/issues/142771) 2026.9.3: failed update can leave forward-migrated Workshop state on 9.2 rollback; WebChat ACP binding also lacks conversationId
- [#142479](https://github.com/openclaw/openclaw/issues/142479) [Bug]: Active Memory skips model recall when optional trigger lookup times out
- [#142758](https://github.com/openclaw/openclaw/issues/142758) Feature request: make skill-collection review limit configurable (currently hardcoded 240 KB / 200 skills)
- [#137190](https://github.com/openclaw/openclaw/issues/137190) [Bug]: Localize schema-derived Control UI field metadata
- [#142592](https://github.com/openclaw/openclaw/issues/142592) Feature: show video frame previews in composer attachments

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 243,469 · **Open issues:** 41,067 · **Last push:** <1h ago

### ✅ Merged PRs
- [#106189](https://github.com/NousResearch/hermes-agent/pull/106189) fix(desktop): allow project creation while browsing all profiles
- [#106185](https://github.com/NousResearch/hermes-agent/pull/106185) MCP OAuth refresh no longer erases the refresh token (#62333)
- [#106175](https://github.com/NousResearch/hermes-agent/pull/106175) fix(desktop): stop false Windows update failures (salvage #105168)
- [#106086](https://github.com/NousResearch/hermes-agent/pull/106086) fix: remove extra guidance from Computer Use tool description
- [#106168](https://github.com/NousResearch/hermes-agent/pull/106168) feat(desktop): default glass to 29% tint on the sidebar
- [#106170](https://github.com/NousResearch/hermes-agent/pull/106170) fix(desktop): keep background reports behind bounded disclosures

### 🐛 New Issues
- [#106205](https://github.com/NousResearch/hermes-agent/issues/106205) [Bug]: Novita 429 "server overload" is classified as rate_limit `type/bug` `comp/agent` `P3` `bug`
- [#106202](https://github.com/NousResearch/hermes-agent/issues/106202) 0.21.1: async delegation completion persists delivery row without running a wake turn (parent never synthesizes) `type/bug` `duplicate` `comp/gateway` `tool/delegate` `P2` `sweeper:risk-message-delivery` 💬3
- [#106201](https://github.com/NousResearch/hermes-agent/issues/106201) [Feature]: Spawn-location config overlay for sessions (beyond AGENTS.md) `type/feature` `comp/cli` `area/config` `P3` `area/profiles`
- [#106195](https://github.com/NousResearch/hermes-agent/issues/106195) kanban promote --force prints "Promoted <id> -> ready" and does not change the status (false success) `type/bug` `comp/cron` `P3` 💬3
- [#106192](https://github.com/NousResearch/hermes-agent/issues/106192) [SANITIZED — possible injection attempt] `type/feature` `P3` `sweeper:risk-automation` 💬2
- [#106184](https://github.com/NousResearch/hermes-agent/issues/106184) [Desktop UI Bug] Model provider list incomplete - only shows 5 of 10 providers `type/bug` `P2` `needs-repro` `comp/desktop` 💬2
- [#106182](https://github.com/NousResearch/hermes-agent/issues/106182) TUI child exits when full config contains YAML timestamps `type/bug` `duplicate` `comp/tui` `area/config` `P2` 💬2

### 🔒 Closed Issues
- [#80952](https://github.com/NousResearch/hermes-agent/issues/80952) Windows: terminal tool blocks ~330s then falls back to WSL bash when hermes-acp is spawned by an ACP client (Buzz)
- [#94430](https://github.com/NousResearch/hermes-agent/issues/94430) [Bug] Desktop: project creation fails for single-profile users while 'All profiles' view is enabled
- [#62333](https://github.com/NousResearch/hermes-agent/issues/62333) [Bug]: OAuth refresh_token erased on every token refresh - MCP servers die ~1h after login
- [#106097](https://github.com/NousResearch/hermes-agent/issues/106097) [Windows] Desktop-driven update always fails post-update verification: verify step runs with cwd=$HERMES_HOME, not the install root
- [#105587](https://github.com/NousResearch/hermes-agent/issues/105587) [Bug]: Windows desktop updater verify_windows_desktop_update false‑positive "The updated Desktop executable is missing"（v0.21.1）
- [#105145](https://github.com/NousResearch/hermes-agent/issues/105145) Windows desktop-driven `hermes update` always reports FAILED (exit 8) after a successful update - post-update verification resolves wrong working directory

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,748 · **Open issues:** 811 · **Last push:** 1h ago

### ✅ Merged PRs
- [#10675](https://github.com/zeroclaw-labs/zeroclaw/pull/10675) fix(ci): make Windows test scoping explicit
- [#10620](https://github.com/zeroclaw-labs/zeroclaw/pull/10620) fix(channels): explain permanently dropped voice messages to the sender
- [#10718](https://github.com/zeroclaw-labs/zeroclaw/pull/10718) feat(cost): attribute ledger records to the chat conversation
- [#10710](https://github.com/zeroclaw-labs/zeroclaw/pull/10710) chore(meta): link the site from the README and crate metadata
- [#10711](https://github.com/zeroclaw-labs/zeroclaw/pull/10711) ci(docs): canonical, hreflang, descriptions, robots.txt and sitemap for the published docs

### 🐛 New Issues
- [#10721](https://github.com/zeroclaw-labs/zeroclaw/issues/10721) [Bug]: knowledge.db_path tilde expansion is a global replace, not a home prefix - knowledge tool silently dropped
- [#10720](https://github.com/zeroclaw-labs/zeroclaw/issues/10720) [Bug]: zerocode v0.8.5: agent responses render twice in the chat pane (display-only; tool call fires once) `bug` `runtime` `priority:p2` `status:in-progress` `risk:medium` `zerocode` 💬1
- [#10715](https://github.com/zeroclaw-labs/zeroclaw/issues/10715) [Feature]: Opt-in passive group context for Telegram group chats `enhancement` `channel` `config` `daemon` `integration` `runtime` `channel:core` `channel:telegram` `priority:p2` `status:in-progress` `risk:medium`
- [#10709](https://github.com/zeroclaw-labs/zeroclaw/issues/10709) [Docs]: Document Astra setup for API-key and Codex subscription providers `docs` `config` `provider` `runtime` `provider:openai` `priority:p2` `risk:low` `type:docs`
- [#10708](https://github.com/zeroclaw-labs/zeroclaw/issues/10708) [Feature]: Support active-response steering on OpenAI Responses WebSockets `enhancement` `agent` `provider` `runtime` `provider:openai` `domain:architecture` `priority:p2` `needs-maintainer-review` `risk:high` 💬1
- [#10707](https://github.com/zeroclaw-labs/zeroclaw/issues/10707) [Feature]: Support bounded programmatic tool calling through OpenAI Responses `enhancement` `agent` `provider` `runtime` `tool` `provider:openai` `domain:security` `domain:architecture` `priority:p2` `needs-maintainer-review` `risk:high` 💬1
- [#10706](https://github.com/zeroclaw-labs/zeroclaw/issues/10706) [Feature]: Preserve opaque reasoning state across OpenAI Responses call paths `enhancement` `agent` `provider` `runtime` `provider:openai` `priority:p2` `needs-maintainer-review` `risk:high`
- [#10705](https://github.com/zeroclaw-labs/zeroclaw/issues/10705) [Feature]: Support max reasoning effort for compatible OpenAI models `enhancement` `config` `provider` `runtime` `provider:openai` `provider:compatible` `priority:p2` `needs-maintainer-review` `risk:medium`
- [#10704](https://github.com/zeroclaw-labs/zeroclaw/issues/10704) [Feature]: Support asynchronous function tools with OpenAI Responses `enhancement` `agent` `provider` `runtime` `tool` `provider:openai` `domain:architecture` `priority:p2` `needs-maintainer-review` `risk:high` 💬1
- [#10702](https://github.com/zeroclaw-labs/zeroclaw/issues/10702) [Bug]: token-budget history trimming stops at the first turn boundary that fits, same hysteresis gap as the message cap `bug` `agent` `runtime` `agent:prompt` `priority:p3` 💬1
- [#10701](https://github.com/zeroclaw-labs/zeroclaw/issues/10701) [Bug]: a user message with an image attachment invalidates the whole history cache prefix, not just the new message `bug` `agent` `provider:compatible` `agent:prompt` `priority:p2` 💬1
- [#10700](https://github.com/zeroclaw-labs/zeroclaw/issues/10700) [Bug]: cost records carry a daemon-lifetime session id, so per-conversation spend cannot be separated `bug` `config` `observability` `priority:p2` 💬2
- [#10674](https://github.com/zeroclaw-labs/zeroclaw/issues/10674) [Bug]: history trimming stops at the cap, so tool-heavy sessions re-trim every few turns and defeat prompt caching `bug` `agent` `config` `provider` `runtime` `provider:anthropic` `provider:compatible` `agent:prompt` `priority:p1` `status:accepted` `risk:high` 💬1
- [#10667](https://github.com/zeroclaw-labs/zeroclaw/issues/10667) [Bug]: ZeroCode can duplicate a streamed response when prompt completion precedes TurnComplete `bug` `priority:p2` `status:in-progress` `risk:medium` `zerocode` `channel:acp` 💬1
- [#10641](https://github.com/zeroclaw-labs/zeroclaw/issues/10641) [Feature] [Web]: Per-field cron schedule input `enhancement` `help wanted` `cron` `priority:p2` `status:accepted` `risk:medium` `web` 💬3

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,608 · **Open issues:** 1,518 · **Last push:** 9h ago

### 🐛 New Issues
- [#8086](https://github.com/nearai/ironclaw/issues/8086) `ironclaw skills list` cannot see skills that the runtime writes
- [#6778](https://github.com/nearai/ironclaw/issues/6778) Hosted-MCP: discovered tool catalogs are published per extension id, not per installation — cross-user metadata exposure on multi-principal servers 💬2

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,846 · **Open issues:** 89 · **Last push:** 6d ago

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- ⚫ [#139026](https://github.com/openclaw/openclaw/issues/139026) Internal runtime-context block (<<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>>) leaks visibly into Telegram on stalled/partial-turn replies — 💬2 · 1d ago
- ⚫ [#139028](https://github.com/openclaw/openclaw/issues/139028) [SANITIZED — possible injection attempt] — 💬1 · 3d ago
- 🟢 [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬2 · 7d ago
- 🟢 [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 9d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 11d ago
- ⚫ [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬5 · 15d ago
- ⚫ [#98062](https://github.com/openclaw/openclaw/issues/98062) [Bug]: iOS app fails to connect over Tailscale CGNAT (100.x.x.x) — wss:// required but WebSocket upgrade silently dropped — 💬4 · 27d ago
- ⚫ [#93031](https://github.com/openclaw/openclaw/issues/93031) [Bug] v2026.6.6 cron migration: jobs migrated from jobs.json have blank agent_id — scheduler silently skips them — 💬3 · 30d ago
- ⚫ [#93139](https://github.com/openclaw/openclaw/issues/93139) Bug: write tool and exec heredocs insert literal \n instead of newlines in string content — 💬11 · 33d ago
- ⚫ [#99305](https://github.com/openclaw/openclaw/issues/99305) [Bug]: Bedrock provider — claude-sonnet-5 prompt caching broken (cache-control blocks not attached, zero cache hits) — 💬4 · 35d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### OpenAI — 21 new
- [[Partners] Quickbooks](https://openai.com/business/partners/quickbooks/) _2026-09-09_
- [[Partners] Stripe](https://openai.com/business/partners/stripe/) _2026-09-09_
- [[Partners] Canva](https://openai.com/business/partners/canva/) _2026-09-09_
- [[Partners] Gusto](https://openai.com/business/partners/gusto/) _2026-09-09_
- [[Partners] Hubspot](https://openai.com/business/partners/hubspot/) _2026-09-09_
- [Gpt Tv](https://openai.com/gpt-tv/) _2026-09-08_
- [[Index] 1Password](https://openai.com/index/1password/) _2026-09-08_
- [[Index] Codex Quantum Computing Experiments](https://openai.com/index/codex-quantum-computing-experiments/) _2026-09-09_
- [[Plugins] Mercury](https://openai.com/business/plugins/mercury/) _2026-09-08_
- [[Plugins] Quickbooks](https://openai.com/business/plugins/quickbooks/) _2026-09-08_
- [[Plugins] Paypal](https://openai.com/business/plugins/paypal/) _2026-09-08_
- [[Plugins] Mercury](https://openai.com/business/plugins/mercury/) _2026-09-08_
- [[Plugins] Honeybook](https://openai.com/business/plugins/honeybook/) _2026-09-08_
- [[Plugins] Wix](https://openai.com/business/plugins/wix/) _2026-09-08_
- [[Plugins] Shopify](https://openai.com/business/plugins/shopify/) _2026-09-08_
- [[Plugins] Docusign](https://openai.com/business/plugins/docusign/) _2026-09-08_
- [[Plugins] Quickbooks](https://openai.com/business/plugins/quickbooks/) _2026-09-08_
- [[Plugins] Paypal](https://openai.com/business/plugins/paypal/) _2026-09-08_
- [[Plugins] Zoominfo](https://openai.com/business/plugins/zoominfo/) _2026-09-08_
- [[Index] Supporting Journalism From Classrooms To Newsrooms](https://openai.com/index/supporting-journalism-from-classrooms-to-newsrooms/) _2026-09-08_
- [[Index] The Work Now Within Reach](https://openai.com/index/the-work-now-within-reach/) _2026-09-08_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 5 new
- [OpenAI alleged of stealing mathematicians work](https://reddit.com/r/LocalLLaMA/comments/1wapjaw/openai_alleged_of_stealing_mathematicians_work/) ↑1018
- [DeepSeek Flash 4.1 is already being tested via API and rolling out.](https://reddit.com/r/LocalLLaMA/comments/1wan3nl/deepseek_flash_41_is_already_being_tested_via_api/) ↑328
- [Qwen/Qwen-Drive-1.0-4B · Hugging Face](https://reddit.com/r/LocalLLaMA/comments/1wauxg9/qwenqwendrive104b_hugging_face/) ↑297
- [GPU guide (GB per dollar, bandwidth)](https://reddit.com/r/LocalLLaMA/comments/1waq7hu/gpu_guide_gb_per_dollar_bandwidth/) ↑150
- [Qwen 3.8 27b with PI agent - pushed to its 3D graphic game limits](https://reddit.com/r/LocalLLaMA/comments/1waz5a0/qwen_38_27b_with_pi_agent_pushed_to_its_3d/) ↑124

### r/singularity — top 5 new
- [GPT-6 Astra: Rickroll in Blender](https://reddit.com/r/singularity/comments/1w9aeyk/gpt6_astra_rickroll_in_blender/) ↑2087
- [A Solution to the Navier-Stokes Millennium Prize Problem](https://reddit.com/r/singularity/comments/1wauqbz/a_solution_to_the_navierstokes_millennium_prize/) ↑1700
- [I only like human-solved secrets of the universe](https://reddit.com/r/singularity/comments/1wazg2q/i_only_like_humansolved_secrets_of_the_universe/) ↑1676
- [Today is a historical moment.](https://reddit.com/r/singularity/comments/1wawkq5/today_is_a_historical_moment/) ↑925
- [Insane times we live in](https://reddit.com/r/singularity/comments/1wb3yc0/insane_times_we_live_in/) ↑529

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [Okay Astra is insane.](https://reddit.com/r/openclaw/comments/1wa53bi/okay_astra_is_insane/) ↑54

### X — @openclaw
- [@Pat_Erichsen
 shares how he's leveraging multiplayer agents in OpenClaw 2.0 to more effectively triage and review pull ](https://x.com/openclaw/status/2097385654808400201) ↑0 🔁0 · recent
- [OpenClaw 2026.9.3 is out 🦞

🛡️ Updates recover cleanly
⚡ Sessions reconnect faster
👀 Watch browser automation live
🔗 Sha](https://x.com/openclaw/status/2097363436028191021) ↑0 🔁0 · recent


### X — @steipete
_No new tweets in the last 7 days._

---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
