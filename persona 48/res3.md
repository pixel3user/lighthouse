# Winifred A. Ojo — Debt Payoff Analysis

## Reasoning

### Files used
- **Meridian Visa (06/22/26):** New balance **\$5,240.00**, APR **27.99%**, min **\$104.80**
- **Summit Mastercard (06/22/26):** New balance **\$3,480.00**, APR **22.99%**, min **\$69.60**
- **Liberty Point personal loan:** Balance \$7,850.00, 14.99% fixed, scheduled \$278.26 — installment amortization given
- **Sterling student loan:** Balance \$31,430.00, 8.75% fixed, scheduled \$342.00 — installment amortization given
- **Paystub:** Semimonthly net **\$1,976.33** → monthly take‑home = **\$3,952.66**
- **Checking CSV (June):** non‑debt expenses + the June debt payments
- **401(k) Q2 statement:** Recordkeeping & administrative fee = **\$9.50**

### 1) One‑time \$500 principal payment to Meridian
The \$500 check clears next business day and is applied as a one‑time principal reduction before July. This is not a projection month, so no interest step is applied to it:
**\$5,240.00 − \$500.00 = \$4,740.00.** This becomes the July opening balance.

### 2) Which debt gets the recurring extra
To minimize total interest, target the **highest APR** = **Meridian Visa (27.99%)** — the avalanche method. (Summit 22.99% > Liberty 14.99% > Sterling 8.75%.)

### 3) Recalculated monthly leftover
- Take‑home: 2 × \$1,976.33 = **\$3,952.66**
- June **non‑debt expenses** (rent 1,250.00; groceries 131.63+57.15+98.14; utilities Evergy 110.90, Spire 32.98, Water 38.72, Fiber 70.00; subscriptions Netflix 15.49, Spotify 11.99, Apple 2.99, Planet Fitness 24.99; dining Minsky's 31.20, Christopher Elbow 14.75; fuel 43.10) = **\$1,934.03** *(the \$50 savings transfer is a transfer, not an expense, so it is excluded — see anomaly note)*
- June total debt payment: 104.80 + 615.20 + 278.26 + 342.00 = **\$1,340.26**

**Leftover = 3,952.66 − 1,934.03 − 1,340.26 = \$678.37**

### 4) Two scenarios, July–Dec (opening Meridian = \$4,740; cards: interest on opening balance, then payment; loans follow scheduled amortization)
Monthly rates: Meridian 27.99%/12 = 2.3325%; Summit 22.99%/12 = 1.915833%.

**Scenario A – repeat each June payment** (Mer 104.80 / Sum 615.20 / Lib 278.26 / Ster 342.00)
**Scenario B – avalanche, same \$1,340.26 total** (others at minimums: Sum 69.60, Lib 278.26, Ster 342.00 → Meridian remainder = 1,340.26 − 689.86 = **\$650.40**)

Loans are identical in both (scheduled): **Liberty Dec = \$6,734.47**, **Sterling Dec = \$30,740.60**.

Card balances after the December payment:

| Debt | Scenario A (repeat June) | Scenario B (avalanche) |
|---|---|---|
| Meridian Visa | \$4,776.64 | \$1,306.11 |
| Summit MC | \$27.11 | \$3,461.56 |
| Liberty Point | \$6,734.47 | \$6,734.47 |
| Sterling | \$30,740.60 | \$30,740.60 |
| **Total debt** | **\$42,278.82** | **\$42,242.74** |

**Difference = 42,278.82 − 42,242.74 = \$36.08** lower under the avalanche scenario (both scenarios pay the same \$1,340.26/month, so the gap is pure interest saved by shifting dollars from the 22.99% card to the 27.99% card).

### 5) 401(k) fee adjustment
Leftover \$678.37 − \$9.50 recordkeeping/admin fee = **\$668.87**

---

## Output

**Meridian balance immediately after the one‑time \$500 payment:** **\$4,740.00**

**Debt to receive the recurring extra (to minimize total interest):** **Meridian Visa** (27.99% APR — highest rate).

**Recalculated monthly leftover:** **\$678.37**  (= \$3,952.66 take‑home − \$1,934.03 June non‑debt expenses − \$1,340.26 June total debt payment).

**Balances after the December payment:**

| Debt | Scenario A – repeat June payments | Scenario B – avalanche (extra to Meridian) |
|---|---|---|
| Meridian Visa | **\$4,776.64** | **\$1,306.11** |
| Summit Mastercard | **\$27.11** | **\$3,461.56** |
| Liberty Point loan | **\$6,734.47** | **\$6,734.47** |
| Sterling student loan | **\$30,740.60** | **\$30,740.60** |
| **Total** | **\$42,278.82** | **\$42,242.74** |

**Difference in total debt between scenarios:** **\$36.08** (Scenario B / avalanche is lower — less interest paid).

**Leftover after subtracting the 401(k) recordkeeping & administrative fee (\$9.50):** **\$668.87**

**Notes / anomalies flagged**
- The recurring \$50 "TRANSFER TO SAVINGS" is categorized as a transfer, not an expense, so it is excluded from non‑debt expenses. If you instead treat it as an outflow, non‑debt expenses = \$1,984.03, leftover = **\$628.37**, and the fee‑adjusted amount = **\$618.87**.
- Scenario B's extra to Meridian (\$650.40) exceeds its \$104.80 minimum, as intended; the installment loans were held to their scheduled amortization in both scenarios, so all scenario differences arise solely from the two credit cards.
- Both scenarios use the identical total monthly debt outlay (\$1,340.26) and identical starting balances, so the \$36.08 gap equals the difference in interest accrued over July–December.