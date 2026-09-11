---
layout: post
title: "Ecosystem Digest — 2026-09-11"
date: 2026-09-11 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-09-11
*Generated 07:49 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 389,407 | 7 | 4 | 10 | 1 |
| **hermesagent** | 244,230 | 8 | 3 | 3 | 0 |
| **ZeroClaw** | 32,762 | 15 | 2 | 5 | 0 |
| **IronClaw** | 12,611 | 1 | 0 | 1 | 0 |
| **Moltis** | 2,851 | 0 | 2 | 3 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 389,407 · **Open issues:** 6,649 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.6.35](https://github.com/openclaw/openclaw/releases/tag/v2026.6.35) — openclaw 2026.6.35

### ✅ Merged PRs
- [#144568](https://github.com/openclaw/openclaw/pull/144568) fix(setup): preserve config edits made during provider preparation
- [#139023](https://github.com/openclaw/openclaw/pull/139023) fix(ui): keep Refresh stable during background session updates
- [#144571](https://github.com/openclaw/openclaw/pull/144571) fix(macos): keep dashboard controls visible in full screen
- [#132454](https://github.com/openclaw/openclaw/pull/132454) feat(ui): show Codex usage beside each login
- [#144563](https://github.com/openclaw/openclaw/pull/144563) refactor(models): share prepared catalog views across model pickers
- [#144543](https://github.com/openclaw/openclaw/pull/144543) fix(agents): honor provider backoff during stale recovery
- [#132453](https://github.com/openclaw/openclaw/pull/132453) feat(codex): expose usage for a saved login
- [#144570](https://github.com/openclaw/openclaw/pull/144570) refactor: remove redundant provider stream smoke test
- [#144524](https://github.com/openclaw/openclaw/pull/144524) fix(auth): keep setup replacements inactive until activation
- [#134815](https://github.com/openclaw/openclaw/pull/134815) feat(reef): allow OpenAI OAuth for guard classification

### 🐛 New Issues
- [#144585](https://github.com/openclaw/openclaw/issues/144585) Backup hardlink aliases of generic SQLite databases can omit uncheckpointed WAL data `maintainer` 💬1
- [#144582](https://github.com/openclaw/openclaw/issues/144582) macOS app: Control UI "New window" / "New tab" always fails with "Allow pop-ups for this site, then try again." `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬2
- [#144581](https://github.com/openclaw/openclaw/issues/144581) Windows: `openclaw update` fails at candidate snapshot with a malformed canary path -> runtime-verification-failed `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `maturity:stable` `impact:ux-friction` 💬2
- [#144561](https://github.com/openclaw/openclaw/issues/144561) Read-only worker paths throw "Prepared synthetic auth is missing for anthropic" when a provider apiKey uses env name ANTHROPIC_AUTH_TOKEN `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `impact:message-loss` `impact:auth-provider` `issue-rating: 🦪 silver shellfish` 💬1
- [#144557](https://github.com/openclaw/openclaw/issues/144557) OAuth audio transcription rejects the trusted-network opt-in `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-product-decision` `clawsweeper:needs-security-review` `clawsweeper:source-repro` `impact:security` `impact:auth-provider` `issue-rating: 🦞 diamond lobster` 💬1
- [#144556](https://github.com/openclaw/openclaw/issues/144556) Codex Telegram photo follow-ups replay older image attachments `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `impact:session-state` `issue-rating: 🦞 diamond lobster` 💬1
- [#144552](https://github.com/openclaw/openclaw/issues/144552) [Bug]: backup create aborts on a valid, non-corrupt third-party SQLite file that fails foreign_key_check `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:needs-security-review` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:other` 💬1

### 🔒 Closed Issues
- [#144424](https://github.com/openclaw/openclaw/issues/144424) Concurrent heartbeat lanes on unrelated dashboard sessions collide, trip real Anthropic 429s, and the retry backoff isn't honored (self-sustaining storm)
- [#144574](https://github.com/openclaw/openclaw/issues/144574) [Bug]: exec with timeoutSeconds=1400 cancelled as a whole run at 924s by the diagnostic stale threshold (reason=stuck_recovery) — bare `sleep` trace for #144514
- [#134667](https://github.com/openclaw/openclaw/issues/134667) feat(reef): allow OpenAI OAuth for guard classification
- [#144526](https://github.com/openclaw/openclaw/issues/144526) Prepare progress-card storage for asynchronous database operations

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 244,230 · **Open issues:** 41,713 · **Last push:** <1h ago

### ✅ Merged PRs
- [#107239](https://github.com/NousResearch/hermes-agent/pull/107239) fix(desktop): hide fixed titlebar clusters on contributed full pages
- [#107609](https://github.com/NousResearch/hermes-agent/pull/107609) fix(gateway): MEDIA: delivery can no longer attach another profile's .env / auth.json / state.db under multiplex
- [#107655](https://github.com/NousResearch/hermes-agent/pull/107655) fix(gateway): secondary-profile send_message, notices and /loop wakeups no longer post through the default bot (salvage #87955)

### 🐛 New Issues
- [#107854](https://github.com/NousResearch/hermes-agent/issues/107854) [Bug][Windows 11 25H2 / build 26200] Real-profile detection false-negative: `_detect_default_windows()` reads a `UserChoice` key the OS no longer updates
- [#107850](https://github.com/NousResearch/hermes-agent/issues/107850) Background Review same-session injection turn doesn't set write_origin — is_background_review() returns False, breaking user-owned skills guards `type/bug` `comp/agent` `tool/skills` `P2` `needs-repro` 💬1
- [#107845](https://github.com/NousResearch/hermes-agent/issues/107845) [Bug]: Desktop login-shell PATH probe is POSIX-only — fish rejects ${PATH}, silently reverting the ~/.local/bin PATH fix (#51249) for fish users `type/bug` `P2` `comp/desktop`
- [#107836](https://github.com/NousResearch/hermes-agent/issues/107836) [SANITIZED — possible injection attempt] `type/feature` `comp/agent` `area/config` `P3`
- [#107830](https://github.com/NousResearch/hermes-agent/issues/107830) [Bug]:Streaming tool calls fail permanently with "expected value at line 1 column 11" when Anthropic emits malformed JSON `type/bug` `comp/agent` `comp/gateway` `provider/anthropic` `P1` `bug` `area/streaming`
- [#107829](https://github.com/NousResearch/hermes-agent/issues/107829) [Bug]: tui_gateway: _response_profile_name raises FileNotFoundError for a deleted profile — ws dispatch crash on session.create `type/bug` `comp/tui` `P2` `comp/desktop` `area/profiles`
- [#107828](https://github.com/NousResearch/hermes-agent/issues/107828) [Bug]: Backend pool scope key ("conn:local::default") passed as a profile name; remote-only profiles force-started locally in a 30s loop `type/bug` `P2` `comp/desktop` `area/profiles`
- [#107827](https://github.com/NousResearch/hermes-agent/issues/107827) [Bug]: Managed SSH update recovery never clears when one scope fails to restore — SSH connection is paused forever (cannot dial, edit, or remove) `type/bug` `P2` `comp/desktop` `area/install-update`

### 🔒 Closed Issues
- [#107838](https://github.com/NousResearch/hermes-agent/issues/107838) Removed by author
- [#102041](https://github.com/NousResearch/hermes-agent/issues/102041) Secret-source values are lost from the multiplex scope after any cron job runs (env-shadowed re-apply), breaking credentials process-wide
- [#84266](https://github.com/NousResearch/hermes-agent/issues/84266) Profile-prefixed platform callbacks can resolve through the default adapter

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,762 · **Open issues:** 845 · **Last push:** <1h ago

### ✅ Merged PRs
- [#10730](https://github.com/zeroclaw-labs/zeroclaw/pull/10730) chore(assets): optimize PR-evidence images via ImgBot lossless compression
- [#9212](https://github.com/zeroclaw-labs/zeroclaw/pull/9212) feat(eval): gate CI on the replay regression suite
- [#8546](https://github.com/zeroclaw-labs/zeroclaw/pull/8546) fix(cli): localize status fragments
- [#10713](https://github.com/zeroclaw-labs/zeroclaw/pull/10713) fix(docs): keep the zoomed diagram accessible inside the dialog
- [#10627](https://github.com/zeroclaw-labs/zeroclaw/pull/10627) fix(channels/matrix): report real duration on outbound voice notes

### 🐛 New Issues
- [#10767](https://github.com/zeroclaw-labs/zeroclaw/issues/10767) ZeroRelay frontdoor: bound self-DoS + unauth amplification before public exposure (follow-up to #10525) `enhancement` `security` `follow-up`
- [#10766](https://github.com/zeroclaw-labs/zeroclaw/issues/10766) ZeroRelay: carry the authenticated principal through the relay path instead of collapsing to shared_operator `enhancement` `security` `domain:security` `follow-up`
- [#10764](https://github.com/zeroclaw-labs/zeroclaw/issues/10764) docs(review): bind generated freshness guidance to live GitHub state
- [#10763](https://github.com/zeroclaw-labs/zeroclaw/issues/10763) fix(release): validate final X announcement weighted length
- [#10762](https://github.com/zeroclaw-labs/zeroclaw/issues/10762) fix(gateway): derive OIDC callback scheme from enabled TLS
- [#10761](https://github.com/zeroclaw-labs/zeroclaw/issues/10761) Harden named plugin TLS materialization before transport activation
- [#10760](https://github.com/zeroclaw-labs/zeroclaw/issues/10760) fix(runtime): bind sensitive tool receipts to their execution results
- [#10759](https://github.com/zeroclaw-labs/zeroclaw/issues/10759) SOP RPC: include the retained failure reason in run detail
- [#10758](https://github.com/zeroclaw-labs/zeroclaw/issues/10758) cron/heartbeat: narrow delivery prompt persistence and send guarantees
- [#10757](https://github.com/zeroclaw-labs/zeroclaw/issues/10757) Distinguish agent-browser availability probe timeouts from missing CLI errors
- [#10756](https://github.com/zeroclaw-labs/zeroclaw/issues/10756) Preserve the agent-shell marker after TUI environment overlays
- [#10755](https://github.com/zeroclaw-labs/zeroclaw/issues/10755) memory: preserve preference provenance when consolidation merges into typed rows
- [#10754](https://github.com/zeroclaw-labs/zeroclaw/issues/10754) memory: distinguish content authorship from transport when classifying preferences
- [#10753](https://github.com/zeroclaw-labs/zeroclaw/issues/10753) [Bug]: session/new overflows a 2 MB stack on Windows; guard test was green on 2026-09-07 and aborts on 2026-09-10 `bug` 💬1
- [#10741](https://github.com/zeroclaw-labs/zeroclaw/issues/10741) [Bug]: ZeroCode silently pauses queued work after a normal-looking completed response `bug`

### 🔒 Closed Issues
- [#10548](https://github.com/zeroclaw-labs/zeroclaw/issues/10548) [Bug]: Preserve Mermaid diagram accessibility inside the zoom dialog
- [#10540](https://github.com/zeroclaw-labs/zeroclaw/issues/10540) [Feature]: Report Web dashboard availability in zeroclaw status

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,611 · **Open issues:** 1,523 · **Last push:** 7h ago

### ✅ Merged PRs
- [#8072](https://github.com/nearai/ironclaw/pull/8072) feat(telegram): register the Bot API command menu at activation

### 🐛 New Issues
- [#8093](https://github.com/nearai/ironclaw/issues/8093) Daily ironclaw failure taxonomy — 2026-09-10

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,851 · **Open issues:** 85 · **Last push:** 19h ago

### ✅ Merged PRs
- [#1252](https://github.com/moltis-org/moltis/pull/1252) docs(docker): document the bind-mount permission fix for fresh deploys
- [#1256](https://github.com/moltis-org/moltis/pull/1256) chore(deps-dev): bump browserslist from 4.28.2 to 4.28.8 in /crates/web/ui in the npm_and_yarn group across 1 directory
- [#1260](https://github.com/moltis-org/moltis/pull/1260) fix(exec): report missing shell accurately

### 🔒 Closed Issues
- [#293](https://github.com/moltis-org/moltis/issues/293) [Bug]: No db file on fresh Docker Compose deployment
- [#279](https://github.com/moltis-org/moltis/issues/279) [Bug]: exec tool reports "working directory does not exist" when sh is not in PATH

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- ⚫ [#139026](https://github.com/openclaw/openclaw/issues/139026) Internal runtime-context block (<<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>>) leaks visibly into Telegram on stalled/partial-turn replies — 💬2 · 3d ago
- ⚫ [#139028](https://github.com/openclaw/openclaw/issues/139028) [SANITIZED — possible injection attempt] — 💬1 · 5d ago
- 🟢 [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬2 · 9d ago
- 🟢 [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 11d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 13d ago
- ⚫ [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬5 · 17d ago
- ⚫ [#98062](https://github.com/openclaw/openclaw/issues/98062) [Bug]: iOS app fails to connect over Tailscale CGNAT (100.x.x.x) — wss:// required but WebSocket upgrade silently dropped — 💬4 · 29d ago
- ⚫ [#93031](https://github.com/openclaw/openclaw/issues/93031) [Bug] v2026.6.6 cron migration: jobs migrated from jobs.json have blank agent_id — scheduler silently skips them — 💬3 · 32d ago
- ⚫ [#93139](https://github.com/openclaw/openclaw/issues/93139) Bug: write tool and exec heredocs insert literal \n instead of newlines in string content — 💬11 · 35d ago
- ⚫ [#99305](https://github.com/openclaw/openclaw/issues/99305) [Bug]: Bedrock provider — claude-sonnet-5 prompt caching broken (cache-control blocks not attached, zero cache hits) — 💬4 · 37d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### Anthropic — 3 new
- [[Research] Intelligence Targeting Conventional Weapons Capabilities](https://www.anthropic.com/research/intelligence-targeting-conventional-weapons-capabilities) _2026-09-10_
- [Threat Intelligence](https://www.anthropic.com/threat-intelligence) _2026-09-10_
- [Threat Intelligence Report September 2026](https://www.anthropic.com/threat-intelligence-report-september-2026) _2026-09-10_

### OpenAI — 7 new
- [[Policies] Financial Services Terms](https://openai.com/policies/financial-services-terms/) _2026-09-11_
- [[Business] Contact Sales Financial Services](https://openai.com/business/contact-sales-financial-services/) _2026-09-10_
- [[Form] Openai For Government](https://openai.com/form/openai-for-government/) _2026-09-10_
- [[Index] Introducing The Agents Api](https://openai.com/index/introducing-the-agents-api/) _2026-09-10_
- [[Index] Using Codex Chatgpt To Search For New Antimicrobials](https://openai.com/index/using-codex-chatgpt-to-search-for-new-antimicrobials/) _2026-09-10_
- [[Devday] 2025](https://openai.com/devday/2025/) _2026-09-10_
- [[Index] Expanding Ai Access Us Government](https://openai.com/index/expanding-ai-access-us-government/) _2026-09-10_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/singularity — top 2 new
- [Huggingface security txt after the OpenAI incident](https://reddit.com/r/singularity/comments/1wclhgv/huggingface_security_txt_after_the_openai_incident/) ↑2003
- [Amazing Navier Stokes evolving vortex is going viral](https://reddit.com/r/singularity/comments/1wcoyof/amazing_navier_stokes_evolving_vortex_is_going/) ↑1109

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [Guardians everywhere](https://reddit.com/r/openclaw/comments/1wbdz8s/guardians_everywhere/) ↑99
- [Hermes vs OpenClaw: I benchmarked both on real work.  I left the one that learns.](https://reddit.com/r/openclaw/comments/1wbmu3f/hermes_vs_openclaw_i_benchmarked_both_on_real/) ↑92
- [Everytime I update OpenClaw, It makes me wanna try Hermes](https://reddit.com/r/openclaw/comments/1waqwug/everytime_i_update_openclaw_it_makes_me_wanna_try/) ↑58
- [Any way to use openclaw for free in my old laptop?(free)](https://reddit.com/r/openclaw/comments/1wcjul4/any_way_to_use_openclaw_for_free_in_my_old/) ↑5
- [Stopped 2.0 instance for now](https://reddit.com/r/openclaw/comments/1w6jiao/stopped_20_instance_for_now/) ↑5

### X — @openclaw
_No new tweets since the last digest. Most recent:_
- [OpenClaw Dashboards


@hrudolph
, 
@Pat_Erichsen
 and 
@jjjhenriksen
 demo personal and team dashboards, then show how t](https://x.com/openclaw/status/2097836892016558577)

### X — @steipete
- [Trading tokens for an AC. Who knew SF could be so hot 🫠](https://x.com/steipete/status/2098229090570629419) ↑0 🔁0 · recent
- [This makes a lot of sense. Duplicating logic is no longer painful. Abstractions still are.](https://x.com/steipete/status/2098089196800098798) ↑0 🔁0 · recent
- [Better hop on soon. Astra demand is growing too fast!](https://x.com/steipete/status/2098088917782413740) ↑0 🔁0 · recent
- [Finally got cloud sessions working *fast* in OpenClaw.
Remote Terminal, WebVNC and CUA for computer use.](https://x.com/steipete/status/2097935551735423464) ↑0 🔁0 · recent
- [Dashboards/Mini-Apps was something I pushed two months ago and now it replaced lots of custom tooling we built around OC](https://x.com/steipete/status/2097880507753382201) ↑0 🔁0 · recent
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
