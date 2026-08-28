# 1. Reasoning

**Source documents I pulled the numbers from**

| Account | June statement balance | APR | Regular pmt paid in June (checking register) |
|---|---|---|---|
| Meridian Visa ("Fury") | \$5,240.00 | 27.99% | \$104.80 (its minimum) |
| Summit Mastercard ("Nuisance") | \$3,480.00 | 22.99% | \$615.20 (this is your "extra" target) |
| Liberty Point loan ("Anchor") | \$7,850.00 | 14.99% | \$278.26 |
| Sterling student loan ("Ghost") | \$31,430.00 | 8.75% | \$342.00 |

Summit's minimum is \$69.60, so the recurring **extra you currently throw at Summit = \$615.20 − \$69.60 = \$545.60/mo**. Total out of pocket to the four accounts in June = \$1,340.26.

**Meridian after the one-time \$500.** The June closing balance is \$5,240.00 (already includes the \$122.22 June interest). A \$500 principal payment before the July cycle: \$5,240.00 − \$500 = **\$4,740.00**.

**Which account minimizes interest.** "Least total interest" = avalanche = attack the highest APR first. Your APRs rank Meridian 27.99% > Summit 22.99% > Liberty 14.99% > Sterling 8.75%. Your tracker's "Payoff order" tab is a **snowball** (smallest balance first, "quick win"), which is *not* the least-interest path. To pay the least interest, the extra should go to **Meridian (Fury)**, not Summit.

**Card interest model.** I reverse-engineered your statements: interest = balance × APR/12 (Meridian June: \$5,240 × 27.99%/12 = \$122.22 exactly; Summit: \$3,480 × 22.99%/12 = \$66.67 exactly). I carried that forward six months with no new purchases. Liberty and Sterling get identical fixed payments in both scenarios, so I read their December balances straight off the lenders' own projection tables.

**Budget-tab reconciliation (the important part).** Your Budget tab "leftover" of \$2,970.20 rests on two wrong inputs:

- **Income overstated.** "Take-home pay \$5,466.66 (two paychecks)" is actually your **gross** (2 × \$2,733.33). Your paystub shows **net pay = \$1,976.33/check**, so real take-home for two checks = **\$3,952.66**.
- **Debt payments understated.** "Minimums on the other debts = \$490" doesn't match reality. The three debts *not* getting the extra are Meridian, Liberty, and Sterling, whose actual June payments were \$104.80 + \$278.26 + \$342.00 = **\$725.06**.

Keeping your other expense lines as recorded (rent \$1,250, utilities \$246, groceries/dining/gas \$455, subscriptions \$55.46 — which ties exactly to Netflix+Spotify+Planet Fitness+iCloud):

Real leftover = \$3,952.66 − \$1,250 − \$246 − \$455 − \$55.46 − \$725.06 = **\$1,221.14**.

**401(k) fee.** Northmark's fee disclosure: recordkeeping/administrative fee for the period = **\$9.50**. As a one-time cost this month: \$1,221.14 − \$9.50 = **\$1,211.64**.

**Anomaly flag:** In Scenario 1, Summit is fully retired in December — the \$615.20 December payment overshoots its ~\$572 balance by ~\$43, so it can't literally end at −\$43.64; it ends at \$0 with a small overpayment/credit. This is why the two strategies nearly converge by year-end; the avalanche's real advantage compounds *after* December, while Meridian keeps costing 27.99%.

---

# 2. Output

**Meridian principal immediately after the one-time \$500 payment: `\$4,740.00`**

**Where to send the recurring extra (for least total interest): `Meridian Visa (Fury)` — it's your highest APR at 27.99%.** Your current tracker sends it to Summit (snowball); switch it to Meridian to minimize interest.

**Real monthly leftover (income + debt assumptions corrected): `\$1,221.14`**
- Corrected take-home: \$3,952.66 (not \$5,466.66 — that was gross)
- Corrected "other minimums": \$725.06 (not \$490)

**Adjusted leftover after subtracting the one-time \$9.50 401(k) fee: `\$1,211.64`**

**Scenario 1 — keep the extra on Summit (both start after the \$500 Meridian payment); December balances:**
| Account | After Dec payment |
|---|---|
| Meridian Visa | **\$4,777.57** |
| Summit Mastercard | **\$0.00** (paid off in December, ~\$43 overpayment) |
| Liberty Point | **\$6,734.47** |
| Sterling | **\$30,740.60** |
| **Total** | **≈ \$42,252.64** |

**Scenario 2 — redirect the same \$545.60 extra to Meridian (Summit drops to its \$69.60 minimum); December balances:**
| Account | After Dec payment |
|---|---|
| Meridian Visa | **\$1,219.18** |
| Summit Mastercard | **\$3,461.18** |
| Liberty Point | **\$6,734.47** |
| Sterling | **\$30,740.60** |
| **Total** | **\$42,155.43** |

**Difference in total debt: Scenario 2 (Meridian-first) comes out ahead by ≈ `\$53.57` in net terms** (about **\$97** in headline debt once you count Summit closing out and pocket the ~\$43 December overpayment). The gap is small at the six-month mark only because both plans nearly clear Summit by December anyway — the avalanche's larger savings accrue in 2027, when Scenario 1 would still be grinding down \$4,777 at 27.99%.

*Notes/flags:* (1) Liberty/Sterling December figures are from the lenders' scheduled-payment projection tables; their daily-accrual ledgers show slightly lower (\$6,687.63 and \$30,607.99) because those ledgers start accruing 07-01 and skip ~2–3 weeks of interest — a minor inconsistency in the statements. (2) The exact difference is model-sensitive (\$36–\$54) depending on the interest convention; I used the one that reproduces your statements to the penny. (3) Separate from your ask: your 2025 tax tab deducts \$2,852.47 of student-loan interest (the cap is \$2,500) and \$3,480 of credit-card/personal-loan interest (not deductible) — that overstates your adjustments and refund, worth fixing later. (4) Your register also shows a \$50/mo transfer to savings that isn't on the Budget tab; I left it out per your instruction to keep the other expense lines as recorded.