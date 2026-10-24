# Word Solitaire (Solitaire Associations English)

Solitaire-style word puzzle, A1–B2. Gold cards name a group (category, place, synonym, opposite); open a pile on one of the limited slots and feed it the matching English words and pictures. Only top cards are free, removing one flips the card below, same-group cards stack in columns, and there is a draw deck. 5 levels; every deal was checked with a solver and the move limit is the solver's best + slack.

Open `index.html` in a browser, no build step. Levels live in `LEVELS` at the top of the script. Ad-test events are pushed to `window.dataLayer` / `fbq` if present (`ws_session_start`, `ws_first_move`, `ws_level_complete`, …); `#puzzle`, `#learn` or `#challenge` in the URL tags them with the ad variant.
