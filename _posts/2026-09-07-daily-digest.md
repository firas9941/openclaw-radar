---
layout: post
title: "Ecosystem Digest — 2026-09-07"
date: 2026-09-07 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-09-07
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 389,058 | 6 | 5 | 10 | 0 |
| **hermesagent** | 242,587 | 7 | 0 | 0 | 0 |
| **ZeroClaw** | 32,737 | 10 | 3 | 8 | 0 |
| **IronClaw** | 12,607 | 0 | 0 | 0 | 0 |
| **Moltis** | 2,847 | 0 | 0 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 389,058 · **Open issues:** 6,241 · **Last push:** <1h ago

### ✅ Merged PRs
- [#140531](https://github.com/openclaw/openclaw/pull/140531) fix(discord): reject numeric application ID pasted as bot token during setup
- [#140558](https://github.com/openclaw/openclaw/pull/140558) fix: identify workers behind slow session-write warnings
- [#140504](https://github.com/openclaw/openclaw/pull/140504) docs(plugins): split the manifest reference by domain
- [#140596](https://github.com/openclaw/openclaw/pull/140596) refactor(plugin-sdk): simplify approval forwarding mode resolution
- [#140592](https://github.com/openclaw/openclaw/pull/140592) refactor(ai): share Responses function-tool assembly
- [#140581](https://github.com/openclaw/openclaw/pull/140581) refactor: streamline skills JSON output
- [#140235](https://github.com/openclaw/openclaw/pull/140235) fix(cli): reject blank numeric options across inference and scans
- [#140300](https://github.com/openclaw/openclaw/pull/140300) fix: show complete skill instructions in Workshop comparisons
- [#140571](https://github.com/openclaw/openclaw/pull/140571) fix(tests): isolate macOS package-manager PATH fixtures
- [#140458](https://github.com/openclaw/openclaw/pull/140458) fix(infra): start source workers outside the package directory

### 🐛 New Issues
- [#140632](https://github.com/openclaw/openclaw/issues/140632) [Bug]: Concurrent SQLite and Discord built proofs can collide on a gateway port `bug` `maintainer` `P2` 💬1
- [#140631](https://github.com/openclaw/openclaw/issues/140631) PowerShell exec host: CLIXML errors with stderr merged into Select-Object on fresh runspaces `P2` `clawsweeper:needs-info` `issue-rating: 🦐 gold shrimp` `impact:ux-friction` 💬1
- [#140627](https://github.com/openclaw/openclaw/issues/140627) Trusted official external channels lose gateway binding for delegated session control `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-security-review` `clawsweeper:source-repro` `impact:security` `issue-rating: 🦞 diamond lobster` 💬1
- [#140623](https://github.com/openclaw/openclaw/issues/140623) [Bug]: QA confidence impact annotations shift report columns `maintainer` `P3` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1
- [#140620](https://github.com/openclaw/openclaw/issues/140620) [Bug] In-place upgrade 2026.7.1-2 -> 2026.9.2: session-transcript reconciliation imports 27/~1500 sessions then stalls; pre-upgrade sessions unfindable via sessions_search `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `impact:session-state` `P0` `issue-rating: 🦪 silver shellfish` `impact:ux-release-blocker` 💬1
- [#140611](https://github.com/openclaw/openclaw/issues/140611) Retire the unused route-only CLI plugin preload policy `maintainer` `P3` `clawsweeper:no-new-fix-pr` `clawsweeper:linked-pr-open` `issue-rating: 🌊 off-meta tidepool` 💬1

### 🔒 Closed Issues
- [#140416](https://github.com/openclaw/openclaw/issues/140416) CLI: bare '--import tsx' in resolveRuntimeWorkerArgv breaks every worker spawn outside a package-root cwd
- [#140590](https://github.com/openclaw/openclaw/issues/140590) Consolidate duplicate Responses function-tool assembly
- [#140356](https://github.com/openclaw/openclaw/issues/140356) [Bug]: Successful /reset retains the previous task’s durable progress card
- [#140595](https://github.com/openclaw/openclaw/issues/140595) Bundled catalog lookups rebuild collections and import hosted download services
- [#136200](https://github.com/openclaw/openclaw/issues/136200) [Bug]: Feishu quoted merged-forward messages expose only placeholder text

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 242,587 · **Open issues:** 40,399 · **Last push:** <1h ago

### 🐛 New Issues
- [#104689](https://github.com/NousResearch/hermes-agent/issues/104689) [Bug]: Windows desktop updater reports success after antivirus interruption leaves runtime/build incomplete `type/bug` `comp/cli` `P2` `sweeper:risk-compatibility` `sweeper:risk-platform-windows` `comp/desktop` `platform/windows` `bug` `area/install-update`
- [#104679](https://github.com/NousResearch/hermes-agent/issues/104679) [Blocker][Dashboard] hermes dashboard is no longer able to chat - zero feedback and errors in terminal `type/bug` `P2` `needs-repro` `comp/dashboard`
- [#104678](https://github.com/NousResearch/hermes-agent/issues/104678) Anthropic Pro/Max subscription-exhaustion latches failure_reason=billing with no expiry; cached error replayed after quota window resets until manual `hermes auth reset` `type/bug` `comp/agent` `provider/anthropic` `area/auth` `P2` `sweeper:risk-security-boundary` 💬1
- [#104675](https://github.com/NousResearch/hermes-agent/issues/104675) Feature: Visible UI indicator for running subagents / background tasks (Desktop + TUI) `type/feature` `comp/tui` `tool/delegate` `P3` `comp/desktop`
- [#104674](https://github.com/NousResearch/hermes-agent/issues/104674) Expose the iteration budget to the model: a one-time pre-exhaustion warning `type/feature` `comp/agent` `area/config` `P3`
- [#104671](https://github.com/NousResearch/hermes-agent/issues/104671) [Bug][CLI]: background completion backlog creates one full agent turn per stale/dead process `type/bug` `comp/cli` `comp/tools` `P2` 💬1
- [#104666](https://github.com/NousResearch/hermes-agent/issues/104666) codex_app_server never starts on Windows with an npm-installed Codex (subprocess ignores PATHEXT) `type/bug` `duplicate` `comp/agent` `provider/openai` `P2` `sweeper:risk-platform-windows` `platform/windows` 💬1

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,737 · **Open issues:** 788 · **Last push:** 6h ago

### ✅ Merged PRs
- [#10650](https://github.com/zeroclaw-labs/zeroclaw/pull/10650) ci(channels/matrix): execute every Matrix lib test, not one module
- [#10651](https://github.com/zeroclaw-labs/zeroclaw/pull/10651) fix(providers): warm compatible connections through models endpoint
- [#10639](https://github.com/zeroclaw-labs/zeroclaw/pull/10639) docs(channels): document the WeCom (WeChat Work) channel
- [#10658](https://github.com/zeroclaw-labs/zeroclaw/pull/10658) fix(plugins): reject expired dial budgets
- [#10657](https://github.com/zeroclaw-labs/zeroclaw/pull/10657) test(plugins): escape fixture config paths
- [#10370](https://github.com/zeroclaw-labs/zeroclaw/pull/10370) fix(providers): harden Copilot credential cache
- [#10491](https://github.com/zeroclaw-labs/zeroclaw/pull/10491) fix(plugins): read the machine's trust store for plugin HTTPS
- [#10350](https://github.com/zeroclaw-labs/zeroclaw/pull/10350) ci(tests): measure affected Windows tests on pull requests

### 🐛 New Issues
- [#10670](https://github.com/zeroclaw-labs/zeroclaw/issues/10670) [Bug]: heartbeat.target rejects a channel instance composite key (<type>.<alias>)
- [#10667](https://github.com/zeroclaw-labs/zeroclaw/issues/10667) [Bug]: ZeroCode can duplicate a streamed response when prompt completion precedes TurnComplete `bug` `priority:p2` `risk:medium` `zerocode` `channel:acp`
- [#10665](https://github.com/zeroclaw-labs/zeroclaw/issues/10665) [Feature]: Make ZeroCode's per-pane session limit configurable `enhancement` `config` `priority:p3` `risk:medium` `zerocode`
- [#10663](https://github.com/zeroclaw-labs/zeroclaw/issues/10663) [Feature]: configurable 1-hour prompt-cache TTL for Anthropic cache markers (native and passthrough) `enhancement` `config` `provider` `provider:anthropic` `provider:compatible` `priority:p2` `risk:high`
- [#10662](https://github.com/zeroclaw-labs/zeroclaw/issues/10662) [Bug]: OAuth system-prefix cache marker is below Anthropic's cache minimum and consumes one of the four breakpoint slots `bug` `provider` `provider:anthropic` `priority:p2` `follow-up` `risk:high`
- [#10660](https://github.com/zeroclaw-labs/zeroclaw/issues/10660) [SANITIZED — possible injection attempt] `enhancement` `provider` `provider:anthropic` `provider:compatible` `priority:p2` `status:in-progress` `follow-up` `risk:high`
- [#10659](https://github.com/zeroclaw-labs/zeroclaw/issues/10659) [Bug]: Budget-exceeded Code turn loses visible progress after session restore `bug` `runtime` `priority:p1` `follow-up` `zerocode` `risk:high` `channel:acp`
- [#10645](https://github.com/zeroclaw-labs/zeroclaw/issues/10645) fix(runtime): thread cost-tracking context into delegated sub-loops `bug` `agent` `config` `runtime` `tool` `tool:delegate` `domain:architecture` `priority:p1` `status:accepted` `follow-up` `risk:high` 💬1
- [#10644](https://github.com/zeroclaw-labs/zeroclaw/issues/10644) fix(runtime): bind background delegate results to an owner principal `bug` `agent` `runtime` `tool` `tool:delegate` `domain:security` `domain:architecture` `priority:p1` `status:accepted` `follow-up` `risk:high` 💬2
- [#10635](https://github.com/zeroclaw-labs/zeroclaw/issues/10635) [Bug]: Runtime profile cost limit does not reflect effective global daily budget `bug` `config` `runtime` `domain:security` `priority:p1` `status:accepted` `risk:high` 💬1

### 🔒 Closed Issues
- [#9575](https://github.com/zeroclaw-labs/zeroclaw/issues/9575) [Feature]: Warm OpenAI-compatible connections through /models instead of /chat/completions
- [#10572](https://github.com/zeroclaw-labs/zeroclaw/issues/10572) [Task]: Document the WeCom (WeChat Work) channel
- [#9653](https://github.com/zeroclaw-labs/zeroclaw/issues/9653) [Bug]: plugin wasi:http trusts only the bundled webpki roots and never reads the OS trust store, unlike provider requests since #6528

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,607 · **Open issues:** 1,513 · **Last push:** 5h ago

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,847 · **Open issues:** 88 · **Last push:** 4d ago

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- ⚫ [#139026](https://github.com/openclaw/openclaw/issues/139026) Internal runtime-context block (<<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>>) leaks visibly into Telegram on stalled/partial-turn replies — 💬1 · 1d ago
- ⚫ [#139028](https://github.com/openclaw/openclaw/issues/139028) [SANITIZED — possible injection attempt] — 💬1 · 1d ago
- 🟢 [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬2 · 5d ago
- 🟢 [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 7d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 9d ago
- ⚫ [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬5 · 13d ago
- ⚫ [#98062](https://github.com/openclaw/openclaw/issues/98062) [Bug]: iOS app fails to connect over Tailscale CGNAT (100.x.x.x) — wss:// required but WebSocket upgrade silently dropped — 💬4 · 25d ago
- ⚫ [#93031](https://github.com/openclaw/openclaw/issues/93031) [Bug] v2026.6.6 cron migration: jobs migrated from jobs.json have blank agent_id — scheduler silently skips them — 💬3 · 28d ago
- ⚫ [#93139](https://github.com/openclaw/openclaw/issues/93139) Bug: write tool and exec heredocs insert literal \n instead of newlines in string content — 💬11 · 31d ago
- ⚫ [#99305](https://github.com/openclaw/openclaw/issues/99305) [Bug]: Bedrock provider — claude-sonnet-5 prompt caching broken (cache-control blocks not attached, zero cache hits) — 💬4 · 33d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

_No new official content detected in the last 24h._

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 5 new
- [My RULE of Thumb of choosing a models](https://reddit.com/r/LocalLLaMA/comments/1w5zdx4/my_rule_of_thumb_of_choosing_a_models/) ↑1053
- [8 uncensored Qwen 3.8 27B variants, one base, 167 GPU hours - Abliterlitics](https://reddit.com/r/LocalLLaMA/comments/1w8vx6w/8_uncensored_qwen_38_27b_variants_one_base_167/) ↑438
- [New Benchmark: The Struggle Bench](https://reddit.com/r/LocalLLaMA/comments/1w9dlf1/new_benchmark_the_struggle_bench/) ↑84
- [2x R9700, 64 GB DDR5 is an absolute beast machine with vLLM Radiance / R9V and Qwen 3.8 27b and Flash next](https://reddit.com/r/LocalLLaMA/comments/1w92x3j/2x_r9700_64_gb_ddr5_is_an_absolute_beast_machine/) ↑68
- [Coding benchmarks that are quickly showcasing deep capability](https://reddit.com/r/LocalLLaMA/comments/1w8us6t/coding_benchmarks_that_are_quickly_showcasing/) ↑59

### r/singularity — top 2 new
- [Hate to admit it, but the last month or so, particularly Jacobian conjecture breakthrough => Huggingface incident, have convinced me the AI safety nerds (that I thought were just luddite alarmists) we](https://reddit.com/r/singularity/comments/1w96hyl/hate_to_admit_it_but_the_last_month_or_so/) ↑1033
- [What are your thoughts? I still believe AGI is a long way off.](https://reddit.com/r/singularity/comments/1w9ag49/what_are_your_thoughts_i_still_believe_agi_is_a/) ↑605

---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
