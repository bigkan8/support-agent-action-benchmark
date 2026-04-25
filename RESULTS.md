# Results

## Overall

| Variant | Correct action outcomes | Right actions completed | Wrong actions executed | Wrong actions stopped or redirected | Original support request completed |
| --- | ---: | ---: | ---: | ---: | ---: |
| Baseline | 31/50 | 5/21 | 4/29 | 0/29 | 22/50 |
| Prompt-only | 30/50 | 1/21 | 0/29 | 0/29 | 18/50 |
| VerifiedX | 50/50 | 18/21 | 0/29 | 29/29 | 42/50 |

## VerifiedX By Track

| Track | Scenarios | Right actions completed | Wrong actions executed | Wrong actions stopped or redirected | Correct action outcomes |
| --- | ---: | ---: | ---: | ---: | ---: |
| Account Identity | 6 | 2/2 | 0/4 | 4/4 | 6/6 |
| Commerce Orders | 23 | 8/9 | 0/14 | 14/14 | 23/23 |
| Reservations + Accounts | 9 | 3/4 | 0/5 | 5/5 | 9/9 |
| Subscriptions | 12 | 5/6 | 0/6 | 6/6 | 12/12 |

## Important Interpretation

The prompt-only variant is not competitive just because it executed zero wrong scenario-labeled actions. It completed only 1 of 21 right actions. In a real support product, that means unresolved customers, escalations, and abandoned automation.

VerifiedX's result is different: it executed zero wrong actions while still completing 18 of 21 right actions and returning correct action outcomes in all 50 scenarios.
