# awesome-ai-agents-2026 — Maintenance Run Brief (2026-06-16)

Repo: `/home/xiaoni/projects/awesome-ai-agents-2026` (GitHub: Zijian-Ni/awesome-ai-agents-2026)
Three READMEs MUST stay in sync: `README.md` (English, source of truth), `README.zh-CN.md` (中文), `README.ja.md` (日本語).
`gh` is authenticated as Zijian-Ni. Working tree is clean, local == origin/main.

This is the recurring maintenance task the owner runs. Do the full cycle, then verify. Take the time needed; do not stop early.

## Current state (verified)
- Open issues: 0
- Open PRs: 2 — both touch ONLY README.md (English) and need en/zh/ja sync if accepted:
  - **PR #42** (zlc000190:add-seedream): adds "Seedream AI Studio" (https://seedream4.video/) to Image Generation — ByteDance multi-model image gen + image-to-video via Kling 2.1, free tier.
  - **PR #41** (Armigerous:add-dependency-freshness-mcp): adds "dependency-freshness-mcp" (https://github.com/Armigerous/dependency-freshness-mcp) to Tool & API Integration — MCP server for npm/PyPI dependency freshness.
- CI: `.github/workflows/link-check.yml` (lychee), `pr-spam-guard.yml`, `refresh-badges.yml`. Local link checker: `scripts/check_links.py`.

## TASKS

### 1. Review & resolve the 2 open PRs
For each PR: verify the project is real and the link resolves (fetch the URL / its GitHub repo), check it isn't spam/parallel-blast (the spam-guard bot comments on PRs — read its comment via `gh pr view <n> --comments`), confirm correct category placement, and that the entry style matches the list (badge for GitHub repos, status tags 🆕/⚠️/etc. as appropriate, concise one-line description).
- If acceptable: incorporate the entry into README.md in the right ranked position AND add the equivalent localized entry to README.zh-CN.md and README.ja.md (translate the description naturally — match the tone/format of neighboring zh/ja entries). Then close the PR with a thank-you comment noting it was merged-by-maintainer with en/zh/ja sync (since the contributor only edited English). Prefer incorporating manually + closing with credit over a raw merge, because raw merge would leave zh/ja out of sync — but if you do merge, you MUST immediately follow with the zh/ja sync commit.
- dependency-freshness-mcp: it's a brand-new single-maintainer repo — if low stars/very new, still listable but tag it appropriately (e.g. ⚠️ Unverified / 🆕) consistent with how similar new/unverified entries are handled in the list.
- If a PR is clearly spam or broken: close with a polite explanation instead.

### 2. Add the latest June 2026 AI updates across ALL categories (en/zh/ja)
Like prior runs (see CHANGELOG.md and recent commits for the established style), refresh the list with genuinely notable, REAL developments from ~June 2026. Cover the existing categories where there's real news (LLMs/foundation models, coding agents, image/video gen, agent frameworks, MCP/tools, sandboxing, etc.).
- Every addition MUST be real and verifiable — search the web and confirm before adding. NO hallucinated products, repos, dates, or links. If you can't verify it, don't add it. (Owner rule: absolutely no fabricated entries/links/stats.)
- Date-stamp time-sensitive entries (e.g. **June X, 2026**) and apply the project's status-tag conventions.
- For each English addition, add the matching zh-CN and ja entries in the same position. Keep category ranking sensible (strength/recency/popularity) consistent with the existing ordering philosophy.
- Update CHANGELOG.md with a dated entry summarizing what changed.

### 3. Full en/zh/ja sync audit
After all edits, verify the three files are structurally in sync: same categories in same order, same entries per category (localized text differs, but the set of entries and their order should match), no entry present in one language but missing in another, no broken markdown, no duplicate entries. Fix any drift you find (including pre-existing drift you notice).

### 4. Verify
- Run `python3 scripts/check_links.py` (or a scoped version on just the changed/added links if the full run is too slow — but prefer full). Report dead/broken links and FIX or remove any newly-introduced ones. Pre-existing dead links from third parties: note them, don't necessarily block on them, but fix if trivial (e.g. moved official URL).
- Sanity-check markdown renders (no broken tables/links/badges in the added lines).
- Confirm entry counts per category match across en/zh/ja for anything you touched.

### 5. Commit & push
- Make clean, well-described commits (match the existing commit-message style, e.g. `feat: ...`, `fix: ...`, en/zh/ja sync noted).
- Push to origin/main.
- Close/merge the handled PRs with appropriate comments.

## Constraints
- NO fabricated content. Verify every new entry via web before adding.
- Keep en/zh/ja in lockstep — never leave one language out of sync.
- Match existing formatting, badge style, status tags, and ranking conventions exactly.
- Don't rewrite unrelated sections or reorder the whole file gratuitously.

## Final report (exact)
- The 2 PRs: decision + action taken (merged-with-sync / closed) + the comment posted.
- New June-2026 entries added (list them with their category + source URL you verified).
- en/zh/ja sync audit result (drift found + fixed).
- Link checker result (broken links found / fixed).
- Commits made + push confirmation (git log --oneline -n top + `git status` clean + origin up to date).

---

# Maintenance tooling (added 2026-07-30) — run these, don't eyeball it

Two scripts now enforce what used to be checked by hand. Both exit non-zero on
failure and run in CI via `.github/workflows/structure-check.yml`.

```bash
python3 scripts/sync_audit.py      # en/zh/ja structural lockstep
python3 scripts/check_markdown.py  # anchors, tables, entry syntax, code fences
```

**Run `sync_audit.py` before and after every editing session.** On 2026-07-30 it
surfaced drift that had accumulated invisibly across previous runs:

- entry counts were **795 / 794 / 792**, not equal;
- zh and ja were **missing the entire Quick Navigation table**;
- ja was missing the whole **Ecosystem Choices** subsection;
- ~30 entries sat under the **wrong heading** — most glaringly, 9–11
  humanoid-robot entries were filed under *Autonomous Driving* in both zh and
  ja, and 4 IDE tools were under *Autonomous Software Engineers*.

None of that is visible when you're editing one language at a time, and none of
it trips a link checker. Every link resolved fine the whole time.

## What `sync_audit.py` actually compares

Headings are translated, so it cannot match on heading text. Instead it matches
**positionally** (heading count + level + order) and identifies entries by their
**first markdown link target**, since URLs are not translated. Per section it
reports missing / extra / misordered entries using multiset comparison, so a URL
that legitimately appears twice is handled correctly.

Repeated URLs inside one section are only reported when the repeat count is
**asymmetric across languages**. Eight OpenAI models all pointing at
`openai.com` is normal and stays quiet; the same URL appearing 3× in one file
and 2× in another means an entry was lost or cloned, and that is flagged.

In-page anchors (`#-foo`) are excluded from comparison — they're derived from
translated headings and are expected to differ. `check_markdown.py` validates
those separately against each file's own headings.

## Ordering conventions

`README.md` is the source of truth for entry order. When zh/ja ordering drifts,
permute the existing localized lines into EN order rather than retranslating —
the text is already correct, only its position is wrong.

## Verification standard (non-negotiable)

The owner's rule is no fabricated content, and "a search summary said so" does
not clear that bar. **Fetch the primary source and quote it.**

If `web_fetch` fails with *"Blocked: resolves to private/internal/special-use IP
address"*, that is a WSL DNS quirk (public hostnames resolve into `fc00::/7` /
`198.18.x`), not a dead site. Fall back to:

```bash
bash ~/.openclaw/workspace/tools/fetch-verify.sh <url> [max_chars]
```

which fetches over curl with a real User-Agent and renders readable text via
pandoc, printing the HTTP status and final URL. Other reliable paths that bypass
the same problem: `gh api repos/<owner>/<repo>` for stars / archived / pushed_at,
`gh api repos/<owner>/<repo>/releases/tags/<tag>` to confirm a release date, and
`https://huggingface.co/api/models/<org>/<model>` for weight drops
(`lastModified`, `gated`, shard count).

Note that `openai.com/index/*` and `midjourney.com` return 403 to curl. Use
`openai.com/news/rss.xml` or `developers.openai.com/**.md` instead, and if no
canonical URL can be resolved for a claim, **leave the claim out** — that is what
happened to a reported "Lyria 3.5 / Flow Music" launch on 2026-07-30.

## Cross-check contributor-supplied numbers

PR #68 (ClawBench) stated "283 tasks across 163 websites". The arXiv abstract
says 153 tasks across 144 platforms, and the project's own leaderboard showed a
130-task / 63-platform slice. Contributors are not necessarily wrong on purpose,
but always read the paper or docs yourself before publishing a figure.

## Recurring corrections worth re-checking each run

Items previously listed as "promised" or "upcoming" that have since shipped, and
any version string more than a few weeks old:

- Did a "promised" open-weights drop actually land? (Kimi K3 had; the list still
  said "promised".)
- Did a spec/model listed as a future target actually ship, and does the entry
  link the **release** post rather than the release *candidate*? (MCP 2026-07-28
  had shipped but linked the RC.)
- Are pricing claims still true? (DeepSeek V4 was listed with peak/off-peak 2×
  pricing; the official page shows flat rates.)
- Are framework versions current? (Google ADK was listed at "v2.0 beta" while
  v2.5.0 was out.)
- Did an announced acquisition actually complete? (Meta × Manus was blocked by
  China's NDRC in April 2026.)
