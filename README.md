# Bet Finder

A self-contained, offline-capable page for looking up NFL / NBA / NHL bets by sport, date, game, team, player,
bet type, source and confidence. Live at https://superkole.github.io/bet-finder/

* `index.html` is generated daily by a private analysis pipeline and contains only the published betting data
  (prices shown are the better of FanDuel / BetMGM). No code, database, or credentials live here.
* Filters can be linked via the URL hash, e.g. `#s=nba&t=NY&m=Rebounds`.
* **My bets, search and watchlist** (stored only in your browser's localStorage, never uploaded): Ctrl+K / `/` search across
  games, players and lines; "＋ Placed" on any pick, Best 5 entry, parlay, slip or upcoming line to record the odds/stake you
  actually took; My bets shows results, real P/L and ROI next to the model's result, by sport / type / book, auto-grades from
  the page's own results or the final ESPN box score (else set a result by hand), and exports/imports JSON for backup or
  another device; ★ stars watch a player or game, with in-page line-move badges (DK open → now, pick price → now, ★ seen → now).
* For information only — lines move; re-check before betting.
