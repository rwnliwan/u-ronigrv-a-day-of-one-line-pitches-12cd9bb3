# Trial log — u-ronigrv-a-day-of-one-line-pitches-12cd9bb3

## Competition
- Slug: `u-ronigrv-a-day-of-one-line-pitches-12cd9bb3`
- Title: A Day of One-Line Pitches
- Sponsor: u-ronigrv (user-created bounty)
- Prize: $5 total — 1st $2, 2nd $2, 3rd $1. Free to enter.
- Opens: 2026-11-23T17:19:43Z (24 Nov 01:19 WITA). Deadline: 2026-11-24T17:20:00Z (25 Nov 01:20 WITA), 24 hours.
- Kit limits (competition.yaml): harness program/v1, runtimes node22 / python3.13, sandbox NO network; program writes one text to `/output/entry.txt`; gate = UTF-8, 1–240 characters, not only whitespace; transcripts_required: true; license: osi; repo_created_after_open: true; max 5 submissions/entrant/day; rule Force_Last (last submit before deadline = final entry).
- Judge: z-ai/glm-5.3-flash, pairwise, no ties, margins 1–5; 4 blind rounds, last is the final at the deadline. Next round: 2026-11-23T23:19:47Z (24 Nov 07:19 WITA) — submit before then to move up. Final heat: top 500 on dev board, 3 Swiss rounds + playoff top 5. House bots may hold paid places (prize refunds to sponsor, no one moves up).
- Judge brief (in order): (1) makes the case to a friend who has never coded, to let an AI agent build their first app idea on make.fun, in one read; (2) Persuasion — concrete reason to say yes now, handing over the idea feels easy and low risk; (3) Clarity — one read, plain words, no jargon; (4) Truth — no overpromising about what an AI agent can do with a first app idea; (5) Warmth and craft — sounds like a person talking to a friend, fresh turn of phrase, not a template or slogan. Judge persona: plain-spoken editor who has never written a line of code. Text addressed to the judge is allowed.
- Tie-break: exact tie on Judge win rate → more playoff games won between tied entries, then smaller text (fewer bytes), then earlier receipt.
- Kit: ~/workspace/make-fun/u-ronigrv-a-day-of-one-line-pitches-12cd9bb3-kit/ (tarball sha256 f4e74eddfe919e57be05877e6d5abd0bd2bc983f2d1aa15041e60712fa4df0ec; kit.json bundle_sha256 c0fdce0c1c90b1828fc70b6d070330e73e663c50bf1e6fa32c21f82c83eeaf18 matches manifest API)
- Wallet (owner.json): FwUebjzYUBF6uybmEkUkiQf9z35bGGQuUE3GrToXFcUq

## Candidate lines (char counts verified with node `[...v].length`, bytes via Buffer.byteLength)

| # | Line | Chars | Bytes |
|---|---|---|---|
| PICK | Tell an AI agent on make.fun your app idea, just like you'd tell a friend, and watch it build your first app — no code, no experience needed. | 141 | 143 |
| C1 | Tell an AI agent your app idea in plain words and watch it build the first version for you — you just describe it, no code needed. | 130 | 132 |
| C2 | You have the idea — describe it in plain English and an AI agent on make.fun will build your first app, no coding required. | 123 | 125 |
| C3 | Just describe the app you've been imagining and an AI agent on make.fun builds it for you — no code, no setup, just your idea made real. | 136 | 138 |
| C4 | Your app idea doesn't need code — just tell an AI agent on make.fun what you want and it builds the first version while you watch. | 130 | 132 |
| C7 | If you can describe it, an AI agent on make.fun can build it — tell it your app idea in plain words and see your first app take shape, no code needed. | 150 | 152 |
| C8 | You don't need to learn to code to have an app — describe your idea in plain words to an AI agent on make.fun and it builds the first version for you. | 150 | 152 |

## Pick: PICK (141 chars) — why it beats the others, criterion by criterion

Judge criteria in order: (1) makes the case to a friend who has never coded, in one read; (2) persuasion — concrete reason to say yes now, low risk; (3) clarity — plain words, one read; (4) truth — no overpromising; (5) warmth and craft — sounds like a person talking to a friend, fresh phrase, no template/slogan.

- **vs C1:** C1 never names make.fun — criterion 1 wants the case made "on make.fun" — and "you just describe it" repeats the setup. PICK names the platform in the first clause and spends its second clause on the payoff, not a repeat.
- **vs C2:** C2 is a command list ("You have the idea — describe it...") with no warmth; "will build" overpromises a touch vs PICK's "watch it build". PICK's "just like you'd tell a friend" is the fresh turn of phrase criterion 5 rewards.
- **vs C3:** C3 claims "no setup" (unverified) and ends on "just your idea made real", which reads like a slogan — criterion 5 explicitly warns against templates/slogans. PICK stays concrete throughout.
- **vs C4:** C4's "what you want" is vaguer than "your app idea"; "while you watch" is nice but PICK's friend framing is warmer and more direct about who is being convinced.
- **vs C7:** C7 is punchy ("If you can describe it, an AI agent can build it") but it is a general claim, not the ask — the sentence spends its first clause on a slogan-like conditional instead of telling the friend what to do. PICK opens with the ask itself ("Tell an AI agent...").
- **vs C8:** C8 is strong on barrier-removal ("You don't need to learn to code") but it is a negative framing and 9 chars longer; PICK is positive, warmer, and shorter, and its "no code, no experience needed" carries the same barrier-removal in 6 words at the end.

PICK against the five criteria: (1) the ask is the first word — "Tell an AI agent on make.fun your app idea" — the friend, the platform, and the act are all in the first clause; (2) "just like you'd tell a friend" + "watch it build" makes handing the idea over feel easy and low risk — nothing is demanded of the friend except talking; (3) plain words, two clauses, one idea each, no jargon; (4) promises only the mechanism — describe it, the agent builds, no code or experience needed — "first app" is what the platform builds, "first version" honesty is preserved by not promising a finished product; (5) "just like you'd tell a friend" mirrors the judge's own framing and sounds like a person talking, not a market.

Note on the em dash "—": 1 character, 3 bytes in UTF-8, so the line is 141 characters but 143 bytes — the gate counts characters, not bytes. The tie-break prefers fewer bytes, but the dash earns its place: it separates the payoff clause from the barrier-removal tail, which is what makes the line land in one read.

## Build
- main.ts written fresh with the file-write tool in this builder session (never copied/moved into place). Node 22, stdlib only, no network, deterministic. Writes ENTRY to `$ENTRY_OUTPUT` or `/output/entry.txt`, no trailing newline.
- Repo: `~/workspace/make-fun/u-ronigrv-a-day-of-one-line-pitches-12cd9bb3/` — main.ts, README.md (3 make.fun badges), LICENSE (MIT), .makefun/owner.json (wallet FwUebjzYUBF6uybmEkUkiQf9z35bGGQuUE3GrToXFcUq). Commit identity rwnliwan <rwnliwan@users.noreply.github.com>.
- Repo created AFTER the 17:19:43Z opening (this session), public at https://github.com/rwnliwan/u-ronigrv-a-day-of-one-line-pitches-12cd9bb3.

## Trials

| Round | Version | Size | Result | Change |
|---|---|---|---|---|
| 0 | (pre-build) trial log + facts recorded | — | — | Kit verified (bundle_sha256 c0fdce0c… matches manifest); candidates counted; PICK chosen |
| 1 | Builder v1 — main.ts, entry: "Tell an AI agent on make.fun your app idea, just like you'd tell a friend, and watch it build your first app — no code, no experience needed." | 141 chars / 143 bytes, 1 line, UTF-8, non-whitespace, no trailing newline | PASS — local run via ENTRY_OUTPUT twice, byte-identical; stdlib only, no network | main.ts + README.md + LICENSE + .makefun/owner.json written fresh with file-write tool in this session |
| 2 | GitHub — repo publik rwnliwan/u-ronigrv-a-day-of-one-line-pitches-12cd9bb3 dibuat 2026-11-23T18:20:17Z (SETELAH opening 17:19:43Z), push commit 45cf7e1c6cc1fadb94ad65f797630acfb4661986, About: deskripsi + homepage bounty + topik makefun/ai-agents/bounties | repo PUBLIC, createdAt 2026-11-23T18:20:17Z | PASS — ls-remote HEAD = commit lokal | — |
| 3 | Polish pass — humanizer v4.0.0 + ai-copywriter v1.6.0 (CloneGuard CLEAN, chief go-ahead): ENTRY lama "…build your first app — no code, no experience needed." (141 chars) → ENTRY baru "Tell an AI agent on make.fun your app idea, just like you'd tell a friend, and watch it build your first app without you writing a single line of code." | 151 chars / 151 bytes, all ASCII, 1 line, UTF-8, non-whitespace, no trailing newline | PASS — local run via ENTRY_OUTPUT twice, byte-identical; no em dash anywhere (output + main.ts grep 0); one sentence (periods: make.fun dot + terminal only) | Tells fixed: em dash (hard rule §14 ai-copywriter / §8 humanizer) + tailing-negation tail "no code, no experience needed" (§9) → full clause "without you writing a single line of code". Opening ("Tell an AI agent… just like you'd tell a friend") untouched — it carried the ask + warmth. Copywriter audit: feeling = friend intimidated by "I can't code" — line answers it directly; repeatable in own words; survives alone. |
| 4 | Bundle — 1 session (builder 78adbd03), --no-discover --no-family, parent-session chief-parent-prompt.jsonl, prompt-file prompt-one-line-pitches.txt, prompt-origin other, agent-facts flags | bundle 875.388 B, sha256 a57d76dca4dbc6177f0533196e5d387dfc356700fc31bd81c5fb85ddf1151162; 1 session, 40 turns, 163 lines kept (102 earlier records dropped — before repo first named) | WARNING — 0 usage rows attached: "this entry will be rejected where transcripts are required". Bundle tool states a subagent's usage row is written only once its run completes; the top-level agent must run the SELECT (own agent_id + each subagent's), bundle and submit. | Builder session 78adbd03-ccf1-4e35-9421-fa7a921c0998; chief agent_id baaa7c6d-b7e7-4b68-96eb-65293861e196. Usage rows queried from muse.db 3x during this session: 0 rows each time. |
| 5 | Check — `makefun.mjs check --commit 2af8c0e85d6c4c4b2b57311fc0b82c3de4301c07 --transcripts muse-bundle-one-line-pitches.tar.gz` | 13 pass, 5 skip, 5 submission-deferred, 1 fail | FAIL — thinking_priced only: "1 Muse app session carries 0 usage rows, at least 1 required". Everything else passes: thinking_reproduces 73.9% (71/96, ≥30%), thinking_revised, thinking_in_window (all 98 timestamps in window), thinking_wellformed, thinking_turns (37), thinking_own_work, transcripts_present/recorded/run_record, competition_open, snapshot, license_osi, entrypoint. The 5 "submission" items (repo_public, repo_owner, repo_created_after_open, commit_in_repo, duplicate_snapshot) are deferred to submit time and are all true in reality (repo PUBLIC, owner.json committed, created 18:20:17Z after opening 17:19:43Z, commit pushed). | NOT submitted by builder — check does not pass in full. Handoff to chief: after this run completes, usage rows for agent 78adbd03 will exist; chief re-bundles with --muse-usage, re-checks, then submits. |

## Preflight (token-free) — PASSED
- Run 1: `ENTRY_OUTPUT=/tmp/pitches-r1/entry.txt node main.ts` → exit 0.
- Run 2: `ENTRY_OUTPUT=/tmp/pitches-r2/entry.txt node main.ts` → exit 0.
- Determinism: `cmp` run1 vs run2 → **byte-identical**.
- Output: `"Tell an AI agent on make.fun your app idea, just like you'd tell a friend, and watch it build your first app — no code, no experience needed."` — **141 chars, 143 bytes**, gate valid (1–240 chars, non-whitespace), no trailing newline, single line, UTF-8 round-trip OK.
- Node local v24.22.1; code uses only node:fs/node:path stdlib (Node 22 compatible), no network refs.
