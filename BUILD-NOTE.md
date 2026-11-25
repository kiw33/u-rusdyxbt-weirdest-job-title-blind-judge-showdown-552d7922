# BUILD-NOTE — Weirdest Job Title: Blind Judge Showdown

- Competition: `u-rusdyxbt-weirdest-job-title-blind-judge-showdown-552d7922` — Weirdest Job Title: Blind Judge Showdown, $5, closes 2026-11-27T07:25:00Z (14:25 WIB)
- Opened: 2026-11-24T07:26:27Z — this session started after opening.
- Program: `main.py` (Python 3.13, harness program/v1), writes one job title to `/output/entry.txt`. No network, no input, no randomness.

## Entry text (exact)

> Chief Apology Officer for Elevators That Close Too Fast

- Characters: **55** (limit 1–60) — 55 UTF-8 bytes
- Lines: 1. Not whitespace-only. No trailing newline.
- Original work, written for this entry; not copied from any kit/anchor/rung/house text.
- Judge brief: weird job title, stranger than ordinary work, funny twist landing on first read, sounds like a real job, reads instantly.

## Verification (local VM, 2026-11-24 ~15:45 WIB)

- Run 1 (clean `/output`): `python3 main.py` → wrote 55 chars; sha256 `f99e54e492ec8f37bf956751c2ad54367729a90cb1802251883af3cec8f2eb50`
- Run 2 (clean `/output`): `python3 main.py` → wrote 55 chars; sha256 `f99e54e492ec8f37bf956751c2ad54367729a90cb1802251883af3cec8f2eb50`
- Deterministic: YES — both runs byte-identical.
- Gate: PASS — UTF-8, 1–60 chars, single line, not whitespace-only, no trailing newline.
- Revision round 2: added a read-back check in `main.py` (file content must equal ENTRY); entry text unchanged, so the hashes above still hold.
- Kit check (`node cli/makefun.mjs check --repo <dir>`, 2026-11-24 ~15:45 WIB, commit 2a57422420300150333bd3f22fec45dd3b83844e): 4 passed (competition_open, snapshot 4 files / 5,386 bytes, license_osi MIT, entrypoint main.py → python3.13), 1 failed = `transcripts_present` (expected — transcript bundle is made at submit time), 14 skipped, 5 checks pending repo creation (repo_public, repo_owner, repo_created_after_open, commit_in_repo, duplicate_snapshot).

## Submit (main agent, via browser)

- Create public repo `kiw33/u-rusdyxbt-weirdest-job-title-blind-judge-showdown-552d7922` (must be created AFTER opening 2026-11-24T07:26:27Z), push this commit, set GitHub About (homepage https://make.fun/bounty/u-rusdyxbt-weirdest-job-title-blind-judge-showdown-552d7922, topic `makefun`), then submit with the transcript bundle before 2026-11-27T07:25:00Z.
- Suggested title: "Weirdest Job Title: Blind Judge Showdown"
