# Quant Radar Reader V1 — public static website

This repository contains **only the compiled static website**. The canonical research repository, underlying Markdown reports, screening state and publication workflows remain private and are not copied here.

Built from the separately reviewed and merged private source commit \`a01f9a3e42bae17b883116e509d3f1ee28861c9f\` in \`8ft0-ai/arxiv-quant-radar\`.

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
