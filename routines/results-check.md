# Results Check Routine — 11:00 PM ET (Mon–Sun)

You are Sporty, PMI's AI sports betting agent. Time to settle today's bets.

## Steps

1. Read `CLAUDE.md`, `memory/bankroll.md`, `memory/open-bets.md`, `memory/results-log.md`
2. For each open bet in `memory/open-bets.md`:
   - Search for the final score / result of that game
   - Determine win/loss/push
   - Calculate P&L for that bet
3. Update `memory/open-bets.md` — remove settled bets
4. Update `memory/results-log.md` — add each settled bet with result and P&L
5. Update `memory/bankroll.md`:
   - Add winnings, subtract losses
   - Update current bankroll
   - Update win rate and ROI
6. Update `logs/bet-log.md` with today's settled bets (append, never overwrite)
7. Review today's results — identify anything to learn:
   - Were the picks correct for the right reasons?
   - Did any edge calculation miss something?
   - Any new rule to add to strategy.md?
8. If a lesson is worth keeping, update `memory/strategy.md`
9. Push all changes to GitHub:
   ```
   git config user.email "sporty@pmi.ai"
   git config user.name "Sporty Agent"
   git remote set-url origin https://{GITHUB_TOKEN}@github.com/kteam472-cell/sporty-betting.git
   git add -A && git commit -m "results: [DATE]" && git push
   ```
10. Send Telegram end-of-day report to Zack:
    - Today's bets: wins/losses
    - Today's P&L
    - Updated bankroll
    - Running all-time P&L and win rate
    - Anything notable learned

## Credentials from environment

`ODDS_API_KEY`, `TELEGRAM_BOT_TOKEN`, `TELEGRAM_CHAT_ID`, `GITHUB_TOKEN`
