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
5. Place bet on Hard Rock Bet
6. After settlement: update results-log.md and bankroll.md

---

---

## SECTION 8 — LESSONS LEARNED (live betting history)

### 2026-06-10 — NBA Finals G4 Loss (NYK ML -130)
- **What happened:** Knicks were 2-1 series leaders at home (MSG). Historical Finals home win rate ~63%. Karl-Anthony Towns fouled out 62 seconds in after two controversial calls. Spurs shot 60% from the field in H1, made 14 3-pointers (Finals record), led 76-49 at halftime. Knicks cut it to 15 in Q3 but Spurs held on.
- **Edge miss:** Home-court and series-lead edge was real, but did not account for in-game injury/foul-out risk. KAT losing early effectively removed the Knicks' best interior defender/scorer before the game began. Key player availability (foul trouble = de facto absence) can negate home-court edge entirely.
- **New rule:** For NBA Finals picks, check not just injury reports but also early-foul-trouble risk for high-usage players. Consider buying reduced juice via alternate lines for Series home-court spots — the underlying edge is real but any individual game has high variance.

### 2026-06-10 — MLB TB Rays ML WIN (+$1.37)
- **What worked:** Pitcher matchup edge held. Bennett (4.35 ERA, 3rd MLB start) gave up runs to TB batters who had prior film on him. Rasmussen was solid. Edge thesis confirmed cleanly.
- **Reinforce:** Pitcher ERA and familiarity edges are repeatable. Continue targeting opponents facing young/inexperienced starters on limited outings.

### 2026-06-14 — MLB MIA@PIT Marlins ML WIN (+$2.80)
- **What worked:** Meyer (7-0) vs Skenes (6-6, 0-4 in last 6 starts). Nearly identical ERAs but market priced Pirates -166 / Marlins +140 (62.4% vs 41.7% implied). Marlins' true probability was closer to 46–47% — that's a +4.8% edge. Pick hit, Marlins 4-2.
- **Key validation:** When two elite starters have comparable ERA but opposite win-loss records (one on a skid, one on a streak), the market over-adjusts toward win-loss record. ERA and K-rate are more predictive; recent win-loss record for pitchers is highly luck-dependent (run support). **Rule reinforced:** Chase ERA/strikeout edge over surface win-loss record when market creates a +5 or more point spread on equivalent pitchers.

### 2026-06-15 — MLB COL@CHC OVER 9 LOSS (-$2.00)
- **What happened:** Wrigley wind was 11 mph out to left-center. Lorenzen had a 7.54 ERA. But Imanaga (Cubs) held the Rockies in check. Final: Rockies 3-2 (5 total runs, well under 9). Despite the bad opposing pitcher and favorable wind, the elite home starter (Imanaga, 9+ K/9) suppressed scoring.
- **Edge miss:** The OVER edge was calculated primarily on Lorenzen's ERA + wind, but did not discount for Imanaga's quality. An ace-level home starter can suppress 1.5–2 runs per game, easily negating a wind edge that adds ~0.5–1.0 runs.
- **New rule:** Weather OVER edge (Wrigley wind) only applies in full force when BOTH starters are average-or-worse (4.50+ ERA). If the home starter is elite (sub-4.00 ERA, 9+ K/9), reduce the weather edge contribution by 50%. If the home starter is truly elite (sub-3.50 ERA), skip the weather-OVER play entirely unless the opposing pitcher is also strong and the total is already elevated.

### 2026-06-15 — MLB NYM@CIN Reds ML WIN (+$1.38)
- **What worked:** Burns (1.96 ERA, 7-1) vs. Myers (emergency Triple-A recall). Reds won 12-0. Myers lasted only 1.1 innings before being pulled. The pitcher quality edge was decisive.
- **Reinforce:** Emergency recall starters are among the highest-edge spots in MLB. When a top-of-rotation ace faces a recall pitcher with minimal MLB experience/preparation time, the market consistently underprices the ace's team. Continue targeting these matchups.

### 2026-06-14 — MLB STL@MIN Cardinals ML LOSS (-$2.00)
- **What happened:** Cardinals 4-3 going into 8th, then Twins rallied. Kreidler RBI double off Cardinals reliever Soriano (3-1) scored tying and winning run. Cardinals lost 5-4.
- **Edge miss:** Cardinals had better SP (McGreevy 2.99 ERA vs Bradley 4.02), bullpen SIERA advantage (3.38 vs 4.51), and offensive wRC+ edge. But the Twins lineup executed in the clutch and the Cardinals bullpen cracked in the 8th — SIERA is an average measure, not a guarantee. The cardinals were also playing their 3rd rubber game in the series, a spot where opponent "resilience" matters.
- **New rule:** Bullpen SIERA edge is real but weakens in late-game, high-leverage situations — especially in series rubber games where both bullpens may be depleted. When betting rubber-game underdogs based primarily on bullpen edge, reduce stake by 0.5× compared to a standalone game edge.

### 2026-06-13 — MLB PHI@MIL Brewers ML LOSS (-$2.00)
- **What happened:** Phillies won 8-5. Drohan (3-1, 3.11 ERA) gave up runs despite strong metrics; Nola (3-4, 5.86 ERA) allowed only 5 runs. Brewers had won the series' first two games convincingly; Phillies bounced back in Game 3.
- **Edge miss:** ERA and K/9 metrics on Drohan were real, but the Phillies offense is capable of big run games regardless of opposing pitcher quality. Series context matters — opponent teams often make adjustments after consecutive blowout losses. This is normal variance on a +5.3% edge bet.
- **New rule:** When betting in a series (3+ games), factor in opponent's "bounce-back" motivation after consecutive losses. If a team has been shut out or blown out 2 games in a row, their offensive effort in the next game may be elevated beyond what ERA metrics suggest. Consider reducing stake or passing on the same opponent in Game 3 of a series sweep attempt.

### 2026-06-12 — MLB PHI@MIL Double Win (+$6.36)
- **What worked:** Both bets cashed cleanly. Misiorowski (7-2, 1.50 ERA, elite K%) delivered a shutout vs. Phillies (Brewers 6, Phillies 0). The Under 7.5 hit with 6 total runs. The -1.5 run line covered by 6 runs.
- **Key validation:** Run line at -115 vs. heavy favorite ML at -250 was the right call. $4.00 at -115 returned $3.48 win. Taking the ML at -250 would have returned only $1.60 on the same stake. For strong favorites with elite starters, the run line is consistently better EV.
- **Starter confirmation worked:** Misiorowski was confirmed as the day-of starter and he started — the confirmed-starter rule held and protected the pick.
- **Reinforce:** When an elite ace (sub-2.00 ERA, top-5% K%) goes against a struggling opponent starter (6+ ERA), both the Under AND the run line are viable plays that can compound returns when both hit.

### 2026-06-11 — MLB STL Cardinals ML LOSS (-$1.50)
- **What happened:** Cardinals lost 5-4 to the Mets. Day-of Mets starter was Hunter Dobbins — NOT Sean Scott (2.50 ERA) who was the basis of the edge analysis. Cardinals' win streak ended at 5. Mets held on to avoid the sweep.
- **Edge miss:** Pick was scouted against Scott. Dobbins is a different pitcher with different tendencies. The walk-rate and ERA edge no longer applied. The bet should have been reassessed when Dobbins was confirmed as the starter.
- **New rule (CRITICAL): Confirm the day-of starting pitcher for BOTH teams before placing any MLB bet. If either starter differs from who was scouted, re-run the entire edge analysis or skip the bet. Never let a bet go live based on a pitcher who isn't actually starting.**

---

### 2026-06-17 — MLB MIA@PHI Marlins ML WIN (+$1.56)
- **What worked:** Alcantara (6-4, 4.25 ERA) vs Painter (1-7, 6.43 ERA). Public was 88% on Phillies at home, but the SP quality gap was real. Marlins blew out Phillies 12-4. Reverse Line Movement (RLM) fade of 88% public at +104 produced one of the cleanest wins of the session.
- **Reinforce:** RLM + clear SP quality edge is a high-confidence combo. When public is 85%+ on a home favorite and the opposing road starter is meaningfully better, the contrarian ML on the dog is worth full sizing. Market is pricing crowd sentiment, not pitching.

### 2026-06-17 — MLB CLE@MIL Guardians ML LOSS (-$2.00)
- **What happened:** Williams (9-3, 3.32 ERA) started for Cleveland but gave up 9 runs — the Brewers' lineup exploded at home. Guardians only managed 4 runs off Sproat (5.70 ERA). Despite the road team having an elite ace vs. a struggling home starter, the Brewers won convincingly 9-4.
- **Edge miss:** ERA predicts averages, not individual game performances. An elite pitcher can still give up 9 runs in a single outing, especially when facing a high-power home lineup. American Family Field (Milwaukee) historically plays well for the Brewers lineup.
- **New rule:** Road ace SP edge (road team elite pitcher vs. weak home starter) needs a supporting lineup advantage to be high-confidence. If the road team's offense ranks bottom-third in wRC+, reduce the stake by 0.5× even if the SP edge is large — you're betting on preventing runs but not necessarily scoring them. A loss by the road ace on his own is outcome-changing regardless of edge.

---

### 2026-06-18 — MLB CWS @ NYY Yankees ML LOSS (-$1.50)
- **What happened:** Yankees were -154 home favorites vs CWS. Sean Burke (3-4, 4.15 ERA) pitched a masterclass: 7.1 IP, 1 ER, 8 Ks on 88 pitches. Benintendi hit a pinch-hit grand slam in the 8th. CWS won 5-1.
- **Edge miss:** The pick edge was real (+3.8%) and the team-quality gap was real. But season ERA is a regressed mean — any individual pitcher can outperform it dramatically in a single game. Burke's 4.15 ERA told us nothing about his ceiling on June 18.
- **New rule:** When betting heavy favorites (-150 or steeper) based on team quality alone (no clear SP edge), note that the opposing pitcher can easily outperform their average. Heavy favorites lose ~35–37% of the time. At -154, we only need to win 61% of such picks to break even — tight margins. Cap team-quality-only picks at $1.00–$1.25 when the only edge is opponent weakness, not our team's starter.

### 2026-06-18 — ATL Braves ML + Under 8 VOIDED (Postponement)
- **What happened:** Giants @ Braves series finale postponed before first pitch due to Tropical Storm Arthur remnants. Severe weather threat in north Georgia. Game rescheduled for August 31.
- **Incidental observation:** Giants had swept the prior two series games (7-2 and 7-5), meaning the Braves motivation edge was failing in real time. The postponement voided the bets but the series result validated suspicion that the edge wasn't as clean as modeled.
- **New rule (weather):** For June–September games in the Southeast (Atlanta/Truist Park, Miami/loanDepot, Houston/Minute Maid), check tropical storm/hurricane watch bulletins during Atlantic hurricane season, not just local wind/rain forecasts. Tropical remnants can cause full postponements with 24-hour notice. If a named storm track shows any path within 300 miles of the park within 48 hours, delay the bet or pass. A voided bet is neutral, but it's a process risk for PENDING_MANUAL picks where the game disappears after Zack places.

---

### 2026-06-19 — MLB CWS @ DET White Sox ML LOSS (-$1.25)
- **What happened:** White Sox were 32-27 vs Tigers 22-38 — a 10-game team-quality gap at +110. But Tarik Skubal (returning from NanoScope elbow surgery, pitch-limited to ~80 pitches) struck out 8 batters, and the Tigers held on 4-3.
- **Edge miss:** The theory was: Skubal pitch-limited → DET 22-38 bullpen inherits a close game for ~5 innings → CWS team quality wins out. In reality, an elite pitcher like Skubal can be fully dominant even at 80 pitches (enough for 5-6 innings), and 80 pitches in a 4-3 game means he retired enough batters to hand off a slim lead — not the 5-inning, 50-pitch exposure we modeled.
- **New rule:** Returning-from-injury elite pitchers (ace-level, sub-3.50 ERA career) with pitch limits are NOT safe to fade purely on pitch count. Even 75–80 pitches can deliver 5+ dominant innings. A pitch-limited ace is still an ace. Fade the pitch limit angle only if the return is their first 2 starts or they are demonstrably compromised (ERA 5+ in limited return outings). For healthy-returning aces in their 3rd+ start back, treat them as normal starters.

### 2026-06-19 — MLB MIL @ ATL Under 7.5 WIN (+$1.19) / TOR @ CHC Cubs ML WIN (+$0.83)
- **What worked (Under):** Misiorowski (8-2) + Pérez (2.90 ERA) delivered a 3-2 final. Second Misiorowski Under in 8 days. When Misiorowski starts, the Under is the default lean regardless of opponent — his 1.50 ERA and sub-0.85 WHIP make him among the most reliable low-total anchors in MLB.
- **What worked (Cubs ML):** Ben Brown delivered a dominant performance and the Cubs offense exploded for 16 runs. Elite SP at a reasonable price (-120) with home field confirmed again. The Ben Brown edge thesis is reliable — his 1.44 ERA as a starter represents a genuine market inefficiency while he's still perceived as a young arm.
- **Reinforce:** Misiorowski Unders are a repeatable play whenever he starts and the total is set at 8.5 or below. His floor is elite even on bad days.

---

*Sources: OddsShark, Sports Insights, Action Network, BetStamp, Covers.com, SportsInsights.com, academic research via Bet Labs / QuantifiedStrategies.com*
