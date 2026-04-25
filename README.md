# ActionProof Support-50

**ActionProof Support-50** is a support-agent benchmark for action correctness: can an AI support agent take the right customer-impacting action and refuse the wrong one?

It was built by [VerifiedX](https://verifiedx.me) from 50 synthetic, Kustomer-style support workflows spanning refunds, cancellations, shipping edits, subscription changes, reservation changes, account writes, case tags, and customer-facing messages.

## Headline Result

| Metric | Baseline | Prompt-only | VerifiedX |
| --- | ---: | ---: | ---: |
| Correct action outcomes | 31/50 | 30/50 | **50/50** |
| Right actions completed | 5/21 | 1/21 | **18/21** |
| Wrong actions executed | 4/29 | 0/29 | **0/29** |
| Wrong actions stopped or redirected | 0/29 | 0/29 | **29/29** |
| Original support request completed | 22/50 | 18/50 | **42/50** |

Prompt-only avoided wrong actions by mostly avoiding action. VerifiedX stopped wrong actions while preserving useful support work.

## What Is Included

- `index.html`: public benchmark report with visuals.
- `data/results.json`: sanitized aggregate and scenario-level results.
- `METHODOLOGY.md`: definitions, variants, and scoring rules.
- `RESULTS.md`: compact result tables.
- `assets/action-correctness-map.svg`: the main action-correctness visual.

This public repo intentionally excludes raw traces, full tool payloads, private prompts, API keys, installer smoke artifacts, and VerifiedX internals.

## Notes

The scenarios are synthetic and do not use Kustomer data. Kustomer is only category inspiration for modern AI support systems with customer context, policy gates, human review, and real side effects. This benchmark is not affiliated with Kustomer.
