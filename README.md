# NBA2k27

This project is a lightweight browser-based mini basketball game inspired by NBA 2K27.

## Run it locally

Open `index.html` in a browser, or serve the folder with a local web server:

```bash
cd /workspaces/NBA2k27
python3 -m http.server 8000
```

Then open `http://localhost:8000` in your browser.

## Controls

- Move: W, A, S, D
- Shoot: Spacebar

- Pause/resume: Escape

The game includes a team-selection screen, a basic 3D court, player motion, AI opponent movement, shooting physics, and a score HUD. Choose Rookie, Pro, Hall of Famer, or Legend CPU difficulty before tip-off. Your win/loss record, coins, and Warriors upgrades are saved in your browser. Wins pay your upgraded salary (up to 24 coins); losses pay 2 coins at base salary and up to 8 coins at max salary. From the post-game record page, open the optional player builder or start the next game.

The player builder upgrades speed, three-point shooting, layup/dunk finishing, steals, block timing, block range, super dunks, and ankle breakers. Block range tops out at 1.5 player-heights and the block meter's upgraded green window caps at 50%, with timing difficulty increasing as distance grows. Attribute upgrades cost 4 coins for the first five upgrades in each attribute, then 8 coins; power-up upgrades cost 8 coins, and salary upgrades cost 6 coins.

Create up to four named player profiles from the empty slots at the bottom of the Tip-Off screen. New players start with base upgrades; use the builder's Next Game button to save the new profile and return to Tip-Off. Select a saved profile for a game, or delete it with the trash button.