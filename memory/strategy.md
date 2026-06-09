# Betting Strategy

## Core Approach

Find value — bet where the true probability of winning is higher than what the odds imply.

## Value Calculation

```
Implied probability from odds = 1 / decimal_odds
If my estimated win probability > implied probability → bet has positive expected value
```

Example: DraftKings shows Yankees ML at -130 (implied: 56.5%). If I assess Yankees win probability at 62% → bet has edge.

## Signal Priority (MLB)

1. **Starting pitcher matchup** — ERA, WHIP, recent form, home/away splits
2. **Bullpen strength** — games where ace goes 5-6 innings, then what?
3. **Lineup vs. pitcher handedness** — L vs R splits matter
4. **Weather** — wind direction/speed affects totals, rain = postponement risk
5. **Umpire** — high K-rate umps favor pitchers (bet Under), low K-rate favors hitters (bet Over)
6. **Line movement** — if line moves significantly from open, sharp money is on one side

## Signal Priority (UFC)

1. **Style matchup** — wrestler vs. striker, reach advantages
2. **Recent form** — last 3 fights, any KO losses (chin concerns?)
3. **Camp quality** — team changes, coaching
4. **Odds value** — underdogs with style advantages are highest EV

## Signal Priority (NBA)

1. **Rest advantage** — back-to-back games tank performance
2. **Injury report** — star player out = line shift opportunity
3. **Pace and total** — high-pace teams inflate totals
4. **Home court** — stronger in NBA than other sports

## Rules Written From Results

*(Populated as bets are placed and results logged)*
