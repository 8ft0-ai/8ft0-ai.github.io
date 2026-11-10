# Quant Radar Reader V1 — public static website

This repository contains **only the compiled static website**. The canonical research repository, underlying Markdown reports, screening state and publication workflows remain private and are not copied here.

Built from the separately reviewed and merged private source commit \`a7dfccb2c075d305ec7c706ea22f7cc9528d54af\` in \`8ft0-ai/arxiv-quant-radar\`.

- Static output: 23 pages, including the weekly magazine, 17 paper briefs, dashboard, library and two public source-note pages.
- Original source qualifications: Week 44 was qualified partial historical curation, October was an incomplete research digest; evidence depth is **Abstract + metadata**.
- No accounts, server runtime, analytics or remote inference.
- Initial public release retains \`noindex,nofollow\` pending physical iPhone and assisted screen-reader acceptance.

## Updating and rollback

1. Review and merge a source change in the private research repository.
2. At the merged exact commit, run \`cd reader && npm ci --no-audit --no-fund && npm run check\`.
3. Replace **only the compiled output** in this public repository; keep \`.nojekyll\` and this README, commit and push to \`main\`.
4. Verify the published homepage, a paper, source notes, dashboard and assets. If verification fails, revert the public repository release commit and push to \`main\` to restore the prior deployment.

Tracked in source Issue #475. Public Pages hosting is not an automatic trigger for canonical research publication.

## V1.1 editorial presentation

The 5 November 2026 V1.1 release corrects the distinction between public source notes and private canonical reports, presents distinct source-supported methods/actions without repeating an overview, and adds /about/ with the editorial method and public corrections issue route. Full device and assisted screen-reader acceptance are not represented as complete.

## V1.2 — manuscript-grounded technical depth

The 5 November 2026 edition adds five technical briefs grounded in selected sections of the original version-pinned author manuscripts: both weekly Read properly papers, MintEval, Availability Contract, and Backtests vs Live. Each provides author-reported measurements, method, interpretation, paper-specific limitations, and one proposed falsification question. Canonical editorial source reports retain Abstract + metadata depth; no independent replication, code/data audit or trading advantage is claimed. Internal manuscript SHA-256 evidence stays in the private source repository. Noindex/nofollow remains until real-device and assisted-screen-reader acceptance.

## V1.2 — editorial promise

The editorial standard is published on /about/ and versioned in the private source reader/docs/featured-article-standard.md. Featured technical analyses must state what the research found, why it matters and how the claim could be tested, with explicit source attribution, limitations and no claim of independent replication. Shorter index entries remain suitable when the evidence gate cannot be met. The five existing enhanced manuscript notes are unchanged. Noindex,nofollow and physical accessibility acceptance limits remain.

## North Star charter (6 November 2026)

The private canonical source now preserves a founding charter in docs/north-star.md. The public homepage and /about/#north-star present its mission: turn quantitative research into better research decisions, with personal research utility first and publicly challengeable, evidence-grounded interpretation. Research actions are proposed, not executed. Static-only release; noindex,nofollow and physical accessibility acceptance limitations remain unchanged.

## V1.3 — research-first editorial revision (10 November 2026)

Compiled from reviewed source a7dfccb2c075d305ec7c706ea22f7cc9528d54af (PR #501, Issue #500). The Magazine and Research Landscape foreground source-grounded findings, independent interpretations, counterexamples and falsifiable tests; seven manuscript-informed article analyses are distinguished from ten concise notes. Evidence-depth labels, incomplete-cohort disclosures, original manuscript links and the public/private report boundary remain unchanged. Browser accessibility and scientific review evidence is recorded in private Issue #500. This release is static only; noindex,nofollow remains. Roll back with a Git revert of this public release commit if live acceptance fails.
