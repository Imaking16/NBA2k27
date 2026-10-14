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

The game includes a Tip-Off screen with 1v1, 3v3, and 5v5 modes, a basic 3D court, player motion, AI opponents and teammates, shooting physics, and a score HUD. CPU difficulty applies in every mode. Win rewards are Rookie: 24/48/96 coins, Pro: 48/96/192, Hall of Fame: 72/144/288, and Legend: 100/200/400 for 1v1/3v3/5v5; losses retain the salary-based payout, scaled by mode. Rookie, Pro, and Hall of Fame use the standard CPU block range; Legend uses the longer range. Your win/loss record, coins, and Warriors upgrades are saved in your browser.

Team modes let you select multiple created profiles from the Tip-Off slots; selected slots are highlighted, and the lineup fills remaining places with CPU teammates. Missing 3v3 teammates are automatically rated 50 and 80 when only one player is selected; other CPU teammate slots are assigned by the 50/80 spin wheel. All user-team players wear blue jerseys. In team modes, press **P** or use **PASS & SWITCH** while holding the ball to animate a pass and hand control to the teammate when the ball arrives. The previous player stays on court under teammate AI, and each created player keeps their own upgrades; switching control does not remove anyone from either roster. Off-ball teammates move to create space and guard opposing players. CPU teammates use Pro shooting accuracy.

The opposing NBA team is randomly chosen from the 29 teams other than Golden State before each match. Its primary team color outlines the Tip-Off opponent card; teams with blue primary colors use their mapped non-blue fallback for CPU jerseys. Score four consecutive layups and/or regular dunks to charge the Ankle Breaker, then press **G** or click its on-screen button to stun the defender. Use **UPGRADE SELECTED PLAYER** to open the selected created player's builder directly from Tip-Off.

The player builder upgrades speed, three-point shooting, layup/dunk finishing, steals, block timing, block range, super dunks, and ankle breakers. Block range tops out at 1.5 player-heights and the block meter's upgraded green window caps at 50%, with timing difficulty increasing as distance grows. Attribute upgrades cost 4 coins for the first five upgrades in each attribute, then 8 coins; power-up upgrades cost 8 coins, and salary upgrades cost 6 coins.

Create up to four named player profiles from the empty slots at the bottom of the Tip-Off screen. New players start with base upgrades; use the builder's Next Game button to save the new profile and return to Tip-Off. Select a saved profile for a game, delete it with the trash button, or open its upgrade page directly with **UPGRADE SELECTED PLAYER**. After a team-mode win, upgrade the selected player, return to Tip-Off, and select another used player to upgrade them.