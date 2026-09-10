---
layout: post
title: "Ecosystem Digest — 2026-09-10"
date: 2026-09-10 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-09-10
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 389,316 | 9 | 1 | 10 | 0 |
| **hermesagent** | 243,882 | 6 | 4 | 10 | 0 |
| **ZeroClaw** | 32,754 | 14 | 3 | 1 | 0 |
| **IronClaw** | 12,612 | 1 | 0 | 0 | 0 |
| **Moltis** | 2,849 | 0 | 0 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 389,316 · **Open issues:** 6,562 · **Last push:** <1h ago

### ✅ Merged PRs
- [#143606](https://github.com/openclaw/openclaw/pull/143606) fix: release heartbeat test databases before removing fixtures
- [#142782](https://github.com/openclaw/openclaw/pull/142782) feat(ui): unify plugin discovery and installation
- [#142713](https://github.com/openclaw/openclaw/pull/142713) feat(ui): unify installed plugin detail tabs
- [#142711](https://github.com/openclaw/openclaw/pull/142711) feat(plugins): enrich package categories from ClawHub
- [#142710](https://github.com/openclaw/openclaw/pull/142710) feat(plugins): define package-owned categories
- [#142624](https://github.com/openclaw/openclaw/pull/142624) fix(ui): clarify plugin setup states and icons
- [#138755](https://github.com/openclaw/openclaw/pull/138755) feat(control-ui): unify bundled and ClawHub plugin discovery
- [#137886](https://github.com/openclaw/openclaw/pull/137886) feat(ui): install ClawHub plugins from Control UI
- [#137856](https://github.com/openclaw/openclaw/pull/137856) codex/claw 719 local plugin federation
- [#137846](https://github.com/openclaw/openclaw/pull/137846) codex/claw 720 plugin detail pages

### 🐛 New Issues
- [#143614](https://github.com/openclaw/openclaw/issues/143614) [Feature]: Feishu — first-class plugin.approval support (card-first via typed interactions, text fallback)
- [#143612](https://github.com/openclaw/openclaw/issues/143612) [Bug]: 9.2's builtin `dashboard` command unregisters the Telegram Mini App launcher
- [#143609](https://github.com/openclaw/openclaw/issues/143609) macOS LaunchAgent service-env does not refresh durable env changes on gateway restart 💬1
- [#143608](https://github.com/openclaw/openclaw/issues/143608) Issue on docs `P3` 💬1
- [#143607](https://github.com/openclaw/openclaw/issues/143607) [Feature]: type in chat while an existing session loads `enhancement` `maintainer` `P3` `issue-rating: 🌊 off-meta tidepool` `impact:ux-friction` 💬1
- [#143604](https://github.com/openclaw/openclaw/issues/143604) [Feature]: Complete keyboard navigation for the chat position rail `enhancement` `maintainer` `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:linked-pr-open` `issue-rating: 🌊 off-meta tidepool` `impact:ux-friction` 💬1
- [#143596](https://github.com/openclaw/openclaw/issues/143596) Placed repository session falls back to Gateway-local execution when Codex node approval expires (misclassified as auth 401) `clawsweeper:no-new-fix-pr` `clawsweeper:needs-security-review` `clawsweeper:source-repro` `impact:security` `impact:auth-provider` `P0` `issue-rating: 🦞 diamond lobster` 💬1
- [#143593](https://github.com/openclaw/openclaw/issues/143593) Doctor media migration leaves canonical archives inconsistent with exported files `maintainer` `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:source-repro` `clawsweeper:linked-pr-open` `impact:session-state` `issue-rating: 🦞 diamond lobster` 💬1
- [#143584](https://github.com/openclaw/openclaw/issues/143584) Plugin-wide plugin-state cap is enforced with a namespace-scoped eviction, so a full store can never self-heal (memory-core wedged fleet-wide for 24 days) `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `impact:session-state` `issue-rating: 🦞 diamond lobster` 💬1

### 🔒 Closed Issues
- [#143173](https://github.com/openclaw/openclaw/issues/143173) Legacy auth-profiles.json presence blocks ALL provider auth for an agent, not just the affected provider

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 243,882 · **Open issues:** 41,291 · **Last push:** <1h ago

### ✅ Merged PRs
- [#104767](https://github.com/NousResearch/hermes-agent/pull/104767) fix(relay): accept a provision response that issues no secret (lockstep with gateway-gateway#223)
- [#107035](https://github.com/NousResearch/hermes-agent/pull/107035) test(gateway): make 7 macOS-failing gateway tests host-honest
- [#107018](https://github.com/NousResearch/hermes-agent/pull/107018) fix(dashboard-auth): offer every configured provider in native sign-in
- [#107014](https://github.com/NousResearch/hermes-agent/pull/107014) fix(desktop): exclude expired Windows trust roots with real-certificate coverage
- [#107022](https://github.com/NousResearch/hermes-agent/pull/107022) fmt(js): `npm run fix` auto-fix
- [#107007](https://github.com/NousResearch/hermes-agent/pull/107007) feat(desktop): show more recent sessions in project grouping
- [#107005](https://github.com/NousResearch/hermes-agent/pull/107005) fix(desktop): keep artifact links at the bottom of the status stack
- [#107004](https://github.com/NousResearch/hermes-agent/pull/107004) fix(desktop): keep settings search opaque under Glass
- [#106986](https://github.com/NousResearch/hermes-agent/pull/106986) fix(desktop): wait for session discovery without discarding queued prompts
- [#106992](https://github.com/NousResearch/hermes-agent/pull/106992) fix(desktop): collapse composer status groups except todos

### 🐛 New Issues
- [#107029](https://github.com/NousResearch/hermes-agent/issues/107029) Gateway SIGKILL: _kill_process_group_posix killpg()s the gateway pgid on Darwin (follow-on to #97296) `type/bug` `comp/gateway` `tool/terminal` `backend/local` `P2`
- [#107028](https://github.com/NousResearch/hermes-agent/issues/107028) [Bug]: Codex app-server still retires TUI turns via 90s post-tool watchdog after update (fresh capture) `type/bug` `comp/agent` `provider/openai` `P2` `codex` `sweeper:risk-session-state` 💬1
- [#107016](https://github.com/NousResearch/hermes-agent/issues/107016) Desktop: generic New session opened in Bot workspace is hidden and becomes undiscoverable `type/bug` `duplicate` `P2` `sweeper:risk-session-state` `comp/desktop` `area/sessions` 💬3
- [#107012](https://github.com/NousResearch/hermes-agent/issues/107012) [SANITIZED — possible injection attempt] `type/feature` `comp/cli` `area/config` `P3`
- [#107002](https://github.com/NousResearch/hermes-agent/issues/107002) Bug: Windows: hermes update completes successfully, but gateway relaunch verification fails (#48820) `type/bug` `comp/cli` `P2` `sweeper:risk-platform-windows` `platform/windows` `area/install-update`
- [#107000](https://github.com/NousResearch/hermes-agent/issues/107000) [Bug]: Windows desktop transcript flickers/re-renders on every keystroke — regression between v0.21.0 and v0.21.1 `type/bug` `P2` `comp/desktop` `platform/windows` `bug`

### 🔒 Closed Issues
- [#107026](https://github.com/NousResearch/hermes-agent/issues/107026) [Bug]: Windows Dashoard
- [#60414](https://github.com/NousResearch/hermes-agent/issues/60414) [Feature]: (Desktop) Background Image Config
- [#105532](https://github.com/NousResearch/hermes-agent/issues/105532) Windows Desktop: expired system roots cause CERT_HAS_EXPIRED for valid remote gateways
- [#106184](https://github.com/NousResearch/hermes-agent/issues/106184) [Desktop UI Bug] Model provider list incomplete - only shows 5 of 10 providers

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,754 · **Open issues:** 822 · **Last push:** 15h ago

### ✅ Merged PRs
- [#9739](https://github.com/zeroclaw-labs/zeroclaw/pull/9739) feat(zerocode): multi-session panes with agent sidebar and sidebar-launched quickstart

### 🐛 New Issues
- [#10736](https://github.com/zeroclaw-labs/zeroclaw/issues/10736) [Bug]: Pre-output stream failure skips advertised non-streaming fallback `bug`
- [#10734](https://github.com/zeroclaw-labs/zeroclaw/issues/10734) [Bug]: process_line stack overflow on constrained Windows thread stack (Advisory Windows nextest)
- [#10731](https://github.com/zeroclaw-labs/zeroclaw/issues/10731) [Bug]: `zeroclaw service logs` prints nothing on macOS, Windows and OpenRC when the daemon is healthy
- [#10728](https://github.com/zeroclaw-labs/zeroclaw/issues/10728) ci: npm audit failed — 2026-09-09 `dependencies` `security` `risk:high`
- [#10725](https://github.com/zeroclaw-labs/zeroclaw/issues/10725) [Feature]: Render structured tool inputs readably in ZeroCode `enhancement`
- [#10723](https://github.com/zeroclaw-labs/zeroclaw/issues/10723) [Bug]: cached-input zero fallback suppresses pricing-unavailable warnings without an input rate `bug` `agent` `config` `observability` `runtime` `priority:p2` `risk:medium` `cli`
- [#10721](https://github.com/zeroclaw-labs/zeroclaw/issues/10721) [Bug]: knowledge.db_path tilde expansion is a global replace, not a home prefix - knowledge tool silently dropped `bug` `config` `memory` `runtime` `tool` `memory:backend` `priority:p2` `risk:medium` 💬1
- [#10720](https://github.com/zeroclaw-labs/zeroclaw/issues/10720) [Bug]: zerocode v0.8.5: agent responses render twice in the chat pane (display-only; tool call fires once) `bug` `runtime` `priority:p2` `status:in-progress` `risk:medium` `zerocode` 💬1
- [#10715](https://github.com/zeroclaw-labs/zeroclaw/issues/10715) [Feature]: Opt-in passive group context for Telegram group chats `enhancement` `channel` `config` `daemon` `integration` `runtime` `channel:core` `channel:telegram` `priority:p2` `status:in-progress` `risk:medium`
- [#10706](https://github.com/zeroclaw-labs/zeroclaw/issues/10706) [Feature]: Preserve opaque reasoning state across OpenAI Responses call paths `enhancement` `agent` `provider` `runtime` `provider:openai` `priority:p2` `status:accepted` `risk:high` 💬1
- [#10705](https://github.com/zeroclaw-labs/zeroclaw/issues/10705) [Feature]: Support max reasoning effort for compatible OpenAI models `enhancement` `config` `provider` `runtime` `provider:openai` `provider:compatible` `priority:p2` `risk:medium`
- [#10699](https://github.com/zeroclaw-labs/zeroclaw/issues/10699) [Bug]: cost ledger prices cache writes at the plain input rate, understating every cache miss by the write premium `bug` `config` `provider:anthropic` `provider:compatible` `priority:p2` 💬1
- [#10697](https://github.com/zeroclaw-labs/zeroclaw/issues/10697) [Bug]: ZeroCode ACP transcript drops assistant text emitted before a tool call; only post-last-tool text renders as the reply `bug` `runtime` `tool` `priority:p1` `follow-up` `zerocode` `risk:high` `channel:acp` 💬1
- [#10690](https://github.com/zeroclaw-labs/zeroclaw/issues/10690) [Bug]: Integrations page "Configure" link slugifies the provider display name instead of using the family key (Z.AI -> /config/providers.models/z-ai, path_not_found) `bug` `config` `gateway` `integration` `provider` `runtime` `priority:p2` `status:accepted` `risk:medium` `web` 💬2

### 🔒 Closed Issues
- [#9731](https://github.com/zeroclaw-labs/zeroclaw/issues/9731) zerocode: move Quickstart from the mode bar into the sidebar
- [#9730](https://github.com/zeroclaw-labs/zeroclaw/issues/9730) zerocode: agent sidebar with status dots, add-picker, and click-to-switch
- [#9729](https://github.com/zeroclaw-labs/zeroclaw/issues/9729) zerocode: track multiple concurrent live sessions per chat pane

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,612 · **Open issues:** 1,519 · **Last push:** 10h ago

### 🐛 New Issues
- [#8091](https://github.com/nearai/ironclaw/issues/8091) bug(webchat-v2): Enter sends the message while confirming IME composition

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,849 · **Open issues:** 89 · **Last push:** 7d ago

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- ⚫ [#139026](https://github.com/openclaw/openclaw/issues/139026) Internal runtime-context block (<<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>>) leaks visibly into Telegram on stalled/partial-turn replies — 💬2 · 2d ago
- ⚫ [#139028](https://github.com/openclaw/openclaw/issues/139028) [SANITIZED — possible injection attempt] — 💬1 · 4d ago
- 🟢 [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬2 · 8d ago
- 🟢 [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 10d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 12d ago
- ⚫ [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬5 · 16d ago
- ⚫ [#98062](https://github.com/openclaw/openclaw/issues/98062) [Bug]: iOS app fails to connect over Tailscale CGNAT (100.x.x.x) — wss:// required but WebSocket upgrade silently dropped — 💬4 · 28d ago
- ⚫ [#93031](https://github.com/openclaw/openclaw/issues/93031) [Bug] v2026.6.6 cron migration: jobs migrated from jobs.json have blank agent_id — scheduler silently skips them — 💬3 · 31d ago
- ⚫ [#93139](https://github.com/openclaw/openclaw/issues/93139) Bug: write tool and exec heredocs insert literal \n instead of newlines in string content — 💬11 · 34d ago
- ⚫ [#99305](https://github.com/openclaw/openclaw/issues/99305) [Bug]: Bedrock provider — claude-sonnet-5 prompt caching broken (cache-control blocks not attached, zero cache hits) — 💬4 · 36d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### Anthropic — 1 new
- [[Research] Alignment Assessment Cybersecurity Incidents](https://www.anthropic.com/research/alignment-assessment-cybersecurity-incidents) _2026-09-10_

### OpenAI — 8 new
- [[Partners] Quantiphi](https://openai.com/business/partners/quantiphi/) _2026-09-10_
- [[Business] Model](https://openai.com/business/model/) _2026-09-10_
- [[Partners] Sdg Group](https://openai.com/business/partners/sdg-group/) _2026-09-10_
- [[Index] Growing Atv Big Air Tour](https://openai.com/index/growing-atv-big-air-tour/) _2026-09-09_
- [[Index] Two Blind Brothers](https://openai.com/index/two-blind-brothers/) _2026-09-09_
- [[Index] Accelerating Antibiotic Discovery](https://openai.com/index/accelerating-antibiotic-discovery/) _2026-09-09_
- [[Index] Paul Christiano Joins Openai Foundation Board](https://openai.com/index/paul-christiano-joins-openai-foundation-board/) _2026-09-09_
- [[Index] Ai Policy Window](https://openai.com/index/ai-policy-window/) _2026-09-09_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 5 new
- [Deepseek Has Soft Retired Deepseek V4 Pro](https://reddit.com/r/LocalLLaMA/comments/1wbfrut/deepseek_has_soft_retired_deepseek_v4_pro/) ↑1113
- [Why the hell is LM Studio making LM Studio so difficult to download?](https://reddit.com/r/LocalLLaMA/comments/1wble79/why_the_hell_is_lm_studio_making_lm_studio_so/) ↑475
- [Apple A20 Pro debuts with 7-core GPU, 32-core Neural Engine and 50% more memory bandwidth (~115 GB/s)](https://reddit.com/r/LocalLLaMA/comments/1wc0ekw/apple_a20_pro_debuts_with_7core_gpu_32core_neural/) ↑244
- [Mention if a "new model" is a finetune](https://reddit.com/r/LocalLLaMA/comments/1wbpf6i/mention_if_a_new_model_is_a_finetune/) ↑167
- [Don't let FOMO win if you're interested in local llm from a hobby/learning aspect](https://reddit.com/r/LocalLLaMA/comments/1wbufx5/dont_let_fomo_win_if_youre_interested_in_local/) ↑166

### r/singularity — top 5 new
- [Proposal to make the Navier-Stokes vortex the new subreddit image](https://reddit.com/r/singularity/comments/1wbej1p/proposal_to_make_the_navierstokes_vortex_the_new/) ↑2878
- [We are at the dawn of a new era](https://reddit.com/r/singularity/comments/1wbmva1/we_are_at_the_dawn_of_a_new_era/) ↑1662
- [Summarizing the current discourse regarding Navier stokes on both pro and anti-AI online spaces.](https://reddit.com/r/singularity/comments/1wbphuo/summarizing_the_current_discourse_regarding/) ↑1441
- [The insanity of 10.000 agents running](https://reddit.com/r/singularity/comments/1wbx0o5/the_insanity_of_10000_agents_running/) ↑1166
- [Deepseek v4.1 Flash reaches 98% of Astra’s score at 1.4% of cost on OpenDesign Arena](https://reddit.com/r/singularity/comments/1wbmy11/deepseek_v41_flash_reaches_98_of_astras_score_at/) ↑696

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw
_No new posts since the last digest. Most recent:_
- [My OpenClaw Saved Us From a Power Outage](https://reddit.com/r/openclaw/comments/1vn2kj0/my_openclaw_saved_us_from_a_power_outage/) ↑346

### X — @openclaw
- [OpenClaw Dashboards


@hrudolph
, 
@Pat_Erichsen
 and 
@jjjhenriksen
 demo personal and team dashboards, then show how t](https://x.com/openclaw/status/2097836892016558577) ↑0 🔁0 · recent
- [Tomorrow on the OpenClaw podcast: live Q&A + demos of the latest features with 
@hrudolph
 and 
@Pat_Erichsen
 🦞

Learn ](https://x.com/openclaw/status/2097529398127993133) ↑0 🔁0 · recent


### X — @steipete
- [This is brilliant.](https://x.com/steipete/status/2097830230899769349) ↑0 🔁0 · recent
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
