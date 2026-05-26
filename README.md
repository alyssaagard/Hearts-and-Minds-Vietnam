# Hearts &amp; Minds: Vietnam 1961–1975

A browser-based cognitive strategy simulation, and a companion to the tabletop board game of the same name. It models the central argument of the design: the war for South Vietnam is won or lost on **legitimacy and governance**, not on body count.

**Play it live:** https://alyssaagard.github.io/hearts-and-minds-vietnam/

(The link goes live once GitHub Pages is enabled for this repository. See "Hosting" below.)

## What it is

One turn is one year, from 1961 to 1975. Four factions act each year in order: the **United States**, **South Vietnam**, **North Vietnam**, and the **White Cell** (UN, USSR, China, SEATO). Each faction spends Action Points on its DIMEFIL decks (Diplomatic, Economic, Information, and, for the United States, Military). Scripted history fires each year, from the Diem coup and the Gulf of Tonkin through Tet, Cambodia, the Paris Accords, and the final offensive of 1975.

The headline metric is the **Rural Governance Index (RGI)**, a single 0 to 100 score that answers the plain-language test from the design notes: do the villages have effective governance at night? It is weighted toward South Vietnamese legitimacy, with escalation and enemy will pulling it down even when the map looks like a military success.

## Features

- The full hex map as the game board, with the five strategic tracks and the Communist Patronage slider.
- Complete card decks: 25 United States military cards, plus economic, information, and phase-locked diplomatic decks for all four factions (145 cards in all).
- A setup screen for 1 to 4 players, with quick presets and faction assignment (including team play and open hotseat seats).
- A Card Library and virtual deck you can browse, filter, and draw from.
- Built-in How to Play instructions.
- Live verdict scoring with a 1965 checkpoint and milestone readouts at 1965, 1968, and 1972.
- China and Soviet intervention checks on the largest escalation cards.

## How to play

Open the page, choose your players on the setup screen, and press **Begin Campaign**. On each faction's turn, click cards to spend Action Points, then press **End Turn**. Use **Card Library** to browse the deck, **How to Play** for the full rules, and **Assess Outcome** at any time to read the projected result. Full instructions are inside the game.

## The cognitive model

- **Ends:** South Vietnamese villages become resilient to insurgency, so the North must seek other means.
- **Ways:** develop respected, democratically legitimate leadership at every level, rather than a coerced regime competing for hearts and minds by force.
- **Means:** party development, popular-issue gathering, and legitimate civic and financial support for officials who actually win elections.

The design deliberately makes the tempting path the losing one. Search and destroy, heavy bombing, and widening the war raise escalation and erode legitimacy and world opinion. Quiet, cheap civic and economic work builds the governance that wins.

## Files in this repository

- `index.html` is the entire game (HTML, CSS, and JavaScript in one file).
- `Hearts_and_Minds_Map.png` is the board image used as the game map. The filename must stay exactly as written, including capitalization.
- `README.md` is this file.
- `LICENSE` holds the usage terms.

## Hosting on GitHub Pages

1. Keep `index.html` and `Hearts_and_Minds_Map.png` together at the top level of the repository.
2. Go to **Settings**, then **Pages**.
3. Under "Build and deployment," set the source to **Deploy from a branch**, the branch to **main**, and the folder to **/ (root)**, then **Save**.
4. Wait a minute or two. The live link appears at the top of the Pages settings.

## Updating

In the repository, click **Add file**, then **Upload files**, drag in the changed file (for example a new `index.html`), and commit. GitHub replaces the old version and the live site refreshes within a couple of minutes.

## Credits

Game design and concept: **Wayne Stilwell**. Digital implementation: **Alyssa Agard**. This simulation is a companion to the physical board game; the printed cards, board, and rulebook remain the authoritative reference.

## License

See the `LICENSE` file. All rights reserved by default. If you would prefer to release the project under an open license such as MIT (for the code) or Creative Commons (for the game content), replace the `LICENSE` file accordingly.
