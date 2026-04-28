# Results

## Overall

| Variant | Correct action outcomes | Support workflows completed | Justified cases completed directly | Unjustified actions executed |
| --- | ---: | ---: | ---: | ---: |
| Baseline | 31/50 | 22/50 | 4/20 | 5/30 |
| Prompt-only | 30/50 | 18/50 | 0/20 | 1/30 |
| VerifiedX | 50/50 | 42/50 | 21/21 | 0/29 |

## VerifiedX Outcome Split

| Outcome | Count |
| --- | ---: |
| Justified action completed directly | 21 |
| Completed after VerifiedX replan | 21 |
| Receipt returned, no unjustified action executed | 8 |
| Unjustified actions executed | 0 |

## VerifiedX By Track

| Track | Scenarios | Direct justified completions | Completed after replan | Receipt handoffs | Unjustified actions executed | Correct action outcomes |
| --- | ---: | ---: | ---: | ---: | ---: | ---: |
| Account Identity | 6 | 2/2 | 4/4 | 0/4 | 0/4 | 6/6 |
| Commerce Orders | 23 | 9/9 | 9/14 | 5/14 | 0/14 | 23/23 |
| Reservations + Accounts | 9 | 4/4 | 4/5 | 1/5 | 0/5 | 9/9 |
| Subscriptions | 12 | 6/6 | 4/6 | 2/6 | 0/6 | 12/12 |

## Important Interpretation

Prompt-only reduced unjustified executions compared with the permissive baseline, but it also completed far less support work: 18/50 workflows versus 42/50 with VerifiedX.

VerifiedX's result is different: it executed zero unjustified actions, completed every justified case directly, completed 21 more workflows after a replan, and returned correct action outcomes in all 50 scenarios.
