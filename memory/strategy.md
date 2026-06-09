# Sporty Betting Strategy — Knowledge Base
*Last updated: 2026-06-09 | Version: 1.0 (research build)*

---

## CORE PHILOSOPHY

Every bet needs a documented edge — a reason grounded in data, not a hunch. If you cannot name the edge before placing the bet, skip it. The market is efficient enough that vague confidence is not a strategy.

**Minimum viable bet checklist (all 3 required):**
1. Identified edge from the rules below
2. Implied probability calculated and compared to true probability
3. Bet size calculated via Half-Kelly (never gut-feeling sizing)

---

## SECTION 1 — BANKROLL & BET SIZING

### Kelly Criterion (the math)
Full Kelly formula: **f = (bp - q) / b**
- f = fraction of bankroll to bet
- b = decimal odds minus 1 (net odds, e.g. -110 line = b of 0.909)
- p = estimated win probability
- q = 1 - p (loss probability)

**Decimal odds conversion:** American +150 → 2.50 | American -110 → 1.909
**Implied probability conversion:** -110 line → 110/(110+100) = 52.4% implied probability
**Edge formula:** Edge % = True win probability − Implied probability
**Minimum edge threshold: +3% edge required before placing any bet.** (Industry standard for small bankrolls; below 3% the variance will eat you before the edge compounds.)

### Half-Kelly Rule (MANDATORY)
Use Half-Kelly, not Full Kelly. Full Kelly is theoretically optimal but practically brutal — drawdowns can hit 50%+ before recovering. Half-Kelly gives 75% of the growth rate with roughly half the max drawdown.

**Half-Kelly formula:** Bet size = (Full Kelly fraction / 2) × Bankroll

** bankroll examples:**
| Edge | Odds | Full Kelly | Half-Kelly Bet |
|------|------|-----------|----------------|
| 5% | -110 | .40 | .20 |
| 8% | -110 | .85 | .93 |
| 10% | +120 | .50 | .25 |
| 12% | -110 | .77 | .88 |

**Hard cap:  max per bet regardless of Kelly output.** Never exceed 10% of bankroll on a single wager.

---

## SECTION 2 — MLB EDGES

### 2a. Home Field Advantage
- MLB home teams win 53.5% of regular season games (2010–2019 historical baseline; SportsBettingDime)
- Home field is the weakest of the four major sports — do not blindly back home dogs
- **Edge:** Home underdog value only exists when combined with a second factor (better pitcher, bullpen rest advantage, favorable umpire)
- Umpire bias compounds home advantage: home pitchers receive more favorable called-strike decisions on full counts (documented via PITCHf/x data)

### 2b. Umpire Tendencies — Totals Edge
This is the most reliable and underused MLB edge for recreational bettors.

**Rule:** Always check the assigned HP umpire's O/U record before betting totals.
- Umpires with large strike zones → more strikeouts → fewer baserunners → **UNDER**
- Umpires with small strike zones → more walks and hittable pitches → more baserunners → **OVER**
- The umpire effect is most pronounced in pitcher-vs-pitcher matchups (low-run environments get amplified)
- Sources: OddsShark MLB Umpire Handicapping Stats, Covers.com Umpire Stats

**Lookup:** oddsshark.com/mlb/umpire-handicapping-statistics — filter by season O/U record

### 2c. Weather Impact on Totals (Wrigley-class parks)
- Wind out at Wrigley Field (Chicago) adds 0.5–1.0 run per game to expected total
- Wind in at Wrigley suppresses scoring meaningfully
- Oracle Park (SF), Coors Field (Denver altitude), Minute Maid Park (roof/closed) are the high-variance weather parks
- **Rule:** On any Wrigley game with 10+ mph wind out to center, lean OVER. Wind 15+ mph into the park, lean UNDER. Check wind direction and speed on game day, not the day before.

### 2d. First-5-Innings (F5) Betting
- F5 bets remove bullpen variance entirely — you're betting only on the starter
- Superior starters win ~57% of F5 markets vs. ~59% of full-game markets (OddsShark data)
- **Rule:** Use F5 when you have high confidence in the starting pitcher and low confidence in the bullpen
- **Best setup:** Ace pitcher (top-25% K/9, top-25% ERA) vs. weak lineup, with no bullpen information edge
- F5 lines are typically -5 to -15 cents tighter than full-game — pay attention to juice

### 2e. Strikeout Prop Framework (Pitcher K Props)
The most predictable pitcher prop in baseball. Use this three-factor framework:

**Factor 1 — Pitcher metrics (all 3 preferred):**
- K/9 above 9.0 (elite: 10.0+)
- CSW (Called Strike + Whiff) rate above 30% (elite: 33%+)
- Swinging strike rate (SwStr%) above 13%

**Factor 2 — Opponent:**
- Opposing team K rate above 24% (league average ~22%)
- Check splits by batter handedness — a LHP faces more RHBs who may have worse K-rate vs LHP

**Factor 3 — Umpire:**
- Run umpire lookup (see 2b). A big-zone umpire adds 0.5–1.0 Ks to projections

**Setup target:** All three factors aligned → bet the Over K prop
**Line caution:** K props are highly researched. If the line looks too good, it probably already moved — verify you're getting a fresh number, not stale odds.

### 2f. Line Movement Intelligence
Line movement is the market talking. Read it.

**Sharp money indicators:**
- **Reverse Line Movement (RLM):** 70%+ of public betting one side, but the line moves the other direction. This is sportsbooks responding to sharp (professional) money. **Rule: When you see RLM, the sharp side has edge.**
- **Steam move:** Rapid coordinated line movement across multiple books within minutes. Indicates a syndicate fired. If you catch it early, follow. If you're late (the line already moved 15+ cents), the value is gone.
- **Key MLB line moves:** A 20–40 cent swing on a moneyline = significant sharp action. Caused most often by: pitcher confirmation, lineup leak, or sharp syndicate fire.

**What to do:**
1. Note the opening line
2. Check public betting % (ESPN BET / Action Network / Sports Insights)
3. If public is heavy one way but the line moved the other way → that's your signal
4. Do NOT chase steam after the move — get there early or wait for the next game

---

## SECTION 3 — UFC EDGES

### 3a. Late Replacement Fighter Dynamics
- Late replacements (less than 10 days' notice) have documented disadvantages: incomplete game-planning, no full training camp for this specific opponent
- BUT: replacements often come in heavier (didn't cut weight for this fight) — size advantage is possible
- **Net read:** Late replacement = fade in technical matchups, slight lean toward replacement in pure power/pressure-fighter matchups where game-planning matters less
- **Rule:** Do not back late replacements as favorites. As large underdogs (+200 or more), the value exists in limited scenarios.

### 3b. Weight Cut / Missed Weight Signal
- Fighters who miss weight by 1–2 lbs perform at roughly normal rates
- Fighters who miss weight by 3+ lbs show degraded cardio performance — the cut damaged them
- **Rule:** If a fighter misses weight by 3+ lbs, consider fading them, especially in later rounds (rounds 3+)
- Check same-day weigh-in news — fighters who struggle at the scale are often dehydrated going into the fight

### 3c. Reach Advantage
- Reach advantage is a meaningful edge in standing striking matchups
- Reach advantage of 4+ inches becomes statistically significant at the top level
- **Rule:** In striker-vs-striker matchups, reach advantage of 4+ inches to the underdog = value on the underdog when priced at +150 or higher
- This edge is neutralized in grappling-heavy matchups

### 3d. Title Fight Motivation / Last Fight Status
- Fighters coming off a loss are often better motivated and more dangerous (nothing to lose, extra preparation)
- Champions defending for the 4th+ time in a year show statistically lower performance (mental fatigue, fewer adjustments)
- **Rule:** Underdog coming off a loss vs. champion on back-to-back defenses = worth a look at the price

---

## SECTION 4 — NBA EDGES

### 4a. Back-to-Back Second Night (B2B)
This is one of the most durable edges in NBA betting.

**Historical data (per OddsShark / SportsInsights, 2005–2025):**
- Teams on B2B second night: 2,058–2,118 ATS (49.3% win rate) over the full dataset
- More recent data (2020+): teams on B2B second night lose ATS 57% of the time
- Home teams on B2B: 636–730 ATS since 2005 — fading them yields 53.44% win rate
- **Road B2B is worse** — travel + fatigue + unfamiliar crowd compounds the physical deficit

**Why it works:** Glycogen stores take 48–72 hours to fully replenish. Playing on 0–24 hours rest means players start each possession at a physiological deficit that compounds by Q4.

**Rule:** Fade B2B teams on the second night, especially on the road, at home vs. a rested opponent, and when the line hasn't moved to compensate. If the book has already priced in 3–4 points for B2B fatigue, the edge may be gone — check if it's already in the number.

### 4b. Rest Advantage
- Teams with 3+ days rest vs. B2B opponent: significant ATS edge for the rested team
- Check schedule context, not just tonight's matchup

### 4c. Pace Matchup for Totals
- High-pace teams (top-10 possessions/game) vs. high-pace opponents → OVER value
- Slow-pace teams (bottom-10) vs. slow opponents → UNDER value
- **Rule:** When two top-5 pace teams meet, lean OVER unless one is on B2B or has significant injury news

---

## SECTION 5 — VALUE IDENTIFICATION PROCESS

### Step 1: Convert line to implied probability
- American positive (+150): 100 / (150 + 100) = 40.0%
- American negative (-130): 130 / (130 + 100) = 56.5%

### Step 2: Estimate true probability
Use your edge framework above. Be conservative — most bettors overestimate their edge by 3–5%.

### Step 3: Calculate edge
Edge = True probability − Implied probability
**Minimum edge to bet: +3%** (e.g., you estimate 55% true probability vs. 52.4% implied = +2.6% — skip it)
**Comfortable edge: +5%+**
**Strong edge: +8%+**

### Step 4: Size via Half-Kelly
Run the formula. Cap at .

### Step 5: Document before betting
Log the bet in results-log.md BEFORE placing it. If you're not willing to write it down, you're not confident enough to bet it.

---

## SECTION 6 — WHAT NOT TO DO

- **No parlays on games with identified edges.** Parlays destroy edge by compounding vig. Use singles.
- **No live betting without a pre-game plan.** Live lines move too fast to calculate edge in real time.
- **No chasing losses.**  bankroll means a losing day ends. No doubling down.
- **No bets above ** regardless of how good the edge looks.
- **No betting when tired or distracted.** The math only works if executed correctly.
- **No feel bets.** If it's not in the framework, it doesn't get a bet.

---

## SECTION 7 — SESSION WORKFLOW

1. Check bankroll.md — confirm current balance
2. Identify 1–3 games with edge setups (use checklist above)
3. For each bet: calculate implied probability → estimate true probability → calculate edge → size via Half-Kelly
4. Log in results-log.md before placing
5. Place bet on DraftKings
6. After settlement: update results-log.md and bankroll.md

---

*Sources: OddsShark, Sports Insights, Action Network, BetStamp, Covers.com, SportsInsights.com, academic research via Bet Labs / QuantifiedStrategies.com*
