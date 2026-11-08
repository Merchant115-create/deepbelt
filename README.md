# Deepbelt

A 2D factory idle game that runs in your browser. Drill it, upgrade it, smelt it.

Inspired by Roblox *Miner's Haven*. It is one HTML file with no install and no server.

## Play

Open `index.html` in any modern browser, or use the GitHub Pages link on this repo.
Progress saves in your own browser (localStorage), so each player has their own save.

## How it works

- **Drills** dig ore, **belts** carry it, **upgraders** multiply its value, **furnaces** sell it.
- **Power:** coal travels on belts to a Life force converter, which charges your energy store.
  When the store runs dry machines break and must be repaired.
- **Effects:** fire, frost, electric and gold effects wear off after a few seconds.
  Matching furnaces (for example a Subzero furnace for frozen ore) pay much more.
- **Rebirth:** you get 10 lives. Each one costs 10 times more than the last, and gives one core
  (spent on Core tech) plus an Ascended item and a new Ascended square to place it on.
- **Land:** start on a small plot and buy more tiles as you grow.

## Controls

R rotates, L buys land, X removes, Esc deselects. Click a broken machine to repair it.
Larger items cover several tiles and rotate around their bright "head" tile.
