# Ski 2027 — trip board

Live: https://jasonxu8693.github.io/ski-week-2027-planning-board/

Shared planning board for the **9–16 January 2027** week in the 3 Vallées
(Méribel / Val Thorens). Accommodation shortlist, costs, food, gotchas, and a
live "Who's in" tracker.

**The Who's-in list is shared.** It saves to a Supabase row
(`board_state.board_key = 'ski-2027-trip-board'`) within a second of a change and
everyone else picks it up within ten. Table filters and the selected tab stay on
each person's own device.

Every property was opened on its live listing and checked against the real dates
before it went on the board.

## Editing

Change `index.html`, then `git commit && git push` — Pages redeploys in about a minute.

`archive/` holds the July 2026 static resort-options page this replaced.
