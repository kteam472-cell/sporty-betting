# Sporty Bankroll Tracker
*Starting bankroll: $25.00 | Max bet: $10.00 | System: Half-Kelly*

---

## Current State

| Field | Value |
|-------|-------|
| Starting Bankroll | $25.00 |
| Current Bankroll | $26.97 |
| All-Time P&L | +$1.97 |
| ROI (all-time) | +6.7% |
| Total Bets Placed | 12 (live, all settled) |
| Wagered Today | $3.50 (settled) |
| Open Bets Today | 0 |

*Last updated: 2026-06-18 (results-check session — Settled 2 bets from 06-17. Marlins ML WIN +$1.56, Guardians ML LOSS -$2.00. Net -$0.44. Bankroll: $27.41 → $26.97.)*

---

## Bankroll History Table
*Append a new row after each session (not each bet — end-of-session balance)*

| Date | Session P&L | Cumulative P&L | Ending Balance | Notes |
|------|------------|----------------|----------------|-------|
| 2026-06-09 | $0.00 | $0.00 | $25.00 | System launch — no bets placed yet |
| 2026-06-10 | -$0.63 | -$0.63 | $24.37 | TB Rays ML WIN +$1.37 / NYK Knicks ML LOSS -$2.00. Net -$0.63. |
| 2026-06-11 | -$1.50 | -$2.13 | $22.87 | STL Cardinals ML LOSS -$1.50. Mets won 5-4, wrong pitcher scouted. |
| 2026-06-12 | +$6.36 | +$4.23 | $29.23 | PHI@MIL Under 7.5 WIN +$2.88, Brewers -1.5 WIN +$3.48. Misiorowski dominated. |
| 2026-06-13 | -$2.00 | +$2.23 | $27.23 | Brewers ML LOSS -$2.00. Phillies won 8-5. Drohan didn't hold despite quality ERA metrics. |
| 2026-06-14 | +$0.80 | +$3.03 | $28.03 | Marlins ML WIN +$2.80 (Marlins 4-2 vs Pirates, Meyer 7-0 masterclass). Cardinals ML LOSS -$2.00 (Twins 5-4, Kreidler walk-off RBI double in 8th). |
| 2026-06-15 | -$0.62 | +$2.41 | $27.41 | Reds ML WIN +$1.38 (Reds 12-0 vs Mets, Burns dominant, Myers roughed up in 1.1 IP). COL/CHC OVER LOSS -$2.00 (Rockies 3-2, total 5 runs — Imanaga nullified wind edge). |
| 2026-06-16 | $0.00 | +$2.41 | $27.41 | No bet — no edge cleared 3% minimum threshold. Best candidate was TB Rays ML +160 (~2.5% est. edge), just below threshold. Disciplined sit-out day. |
| 2026-06-17 | $0.00 | +$2.41 | $27.41 | Results-check session. 0 open bets to settle — no picks were placed on 06-16 or 06-17. Bankroll unchanged. Egress blocked (3rd consecutive session): Odds API + Telegram unreachable in cloud env. |
| 2026-06-17 | PENDING | PENDING | $27.41 | Daily picks session. 2 picks identified: Marlins ML +104 ($1.50) and Guardians ML +130 ($2.00). Total at risk: $3.50. Odds sourced via WebSearch (FanDuel/ActionNetwork). Telegram blocked — picks sent via GitHub commit + PushNotification. Awaiting manual placement by Zack. |
| 2026-06-18 | -$0.44 | +$1.97 | $26.97 | Results-check session. Marlins ML WIN +$1.56 (Marlins 12-4 blowout, Alcantara dominant, RLM fade confirmed). Guardians ML LOSS -$2.00 (Brewers 9-4, Williams gave up 9 runs at home — lineup explosion). Net -$0.44. |

---

## Sizing Reference (Half-Kelly at current bankroll)

*Recalculate when bankroll changes by more than $5*

Current bankroll: **$29.23**

| Estimated Edge | Odds | Half-Kelly Bet | Capped? |
|---------------|------|----------------|---------|
| 3% | -110 | $0.84 | No |
| 5% | -110 | $1.40 | No |
| 5% | +120 | $0.97 | No |
| 8% | -110 | $2.25 | No |
| 10% | -110 | $2.80 | No |
| 10% | +150 | $1.95 | No |
| 15% | -110 | $4.20 | No |
| 20% | -110 | $5.60 | No |
| 30% | -110 | $8.41 | No |
| 40% | -110 | $10.00 | YES (cap) |
| 50%+ | any | Cap at $10.00 | YES |

---

## Rules
- **Never bet more than $10 (40% of bankroll) on any single bet**
- **Never bet more than $15 total across open bets simultaneously**
- **If bankroll drops to $10 — pause and reassess edge identification process**
- **If bankroll doubles to $50 — recalculate sizing table above**
- Bankroll is Hard Rock Bet account balance only. Do not commingle funds.
