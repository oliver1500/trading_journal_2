# Trading Journal — Narrative Log

This repo is the **qualitative** half of the trading journal: chart screenshots,
in-the-moment reasoning, and post-trade reflection for each trade.

For the **quantitative** half — structured P&L, R-multiples, win rate, profit
factor, setup performance, mistake tracking — see
[oliver1500/trading_journal](https://github.com/oliver1500/trading_journal)
(EdgeLog), a purpose-built trading journal app. Log every trade's numbers there;
use this repo for the story behind the numbers.

## Layout

- `TEMPLATE.md` — copy this for each new trade entry
- `trades/` — practice/demo trades, one file per trade, named `NNN-YYYY-MM-DD-TICKER.md`
- `trades_with_real_money/` — same format, for trades placed with real capital

## Trade index

### trades/ (practice)

| # | Date | Ticker | Setup | Entry |
|---|------|--------|-------|-------|
| 001 | 2026-08-07 | GE | Support/resistance, beginner reps | [trades/001-2026-08-07-GE.md](trades/001-2026-08-07-GE.md) |
| 002 | 2026-08-14 | NBIS | Relative strength vs SPY | [trades/002-2026-08-14-NBIS.md](trades/002-2026-08-14-NBIS.md) |
| 003 | 2026-09-01 | AAPL | Relative-strength scalp, panic exit | [trades/003-2026-09-01-AAPL.md](trades/003-2026-09-01-AAPL.md) |
| 004 | 2026-09-03 | AAPL | Breakout, timeframe mixed mid-trade | [trades/004-2026-09-03-AAPL.md](trades/004-2026-09-03-AAPL.md) |

### trades_with_real_money/

| # | Date | Ticker | Setup | Entry |
|---|------|--------|-------|-------|
| 001 | 2026-09-23 | MRNA | Breakout above prior-day high, stopped out | [trades_with_real_money/001-2026-09-23-MRNA.md](trades_with_real_money/001-2026-09-23-MRNA.md) |
| 002 | 2026-09-23 | PURR | Breakout above prior-day high, stopped out | [trades_with_real_money/002-2026-09-23-PURR.md](trades_with_real_money/002-2026-09-23-PURR.md) |

## Workflow for a new trade

1. Log the trade's numbers (entry, exit, size, stop, P&L) in EdgeLog as it happens.
2. Copy `TEMPLATE.md` to `trades/NNN-YYYY-MM-DD-TICKER.md` (or `trades_with_real_money/`
   for real-capital trades) and write the narrative while it's fresh — thesis,
   screenshots, what happened, lessons learned.
3. Add a row to the trade index above.
