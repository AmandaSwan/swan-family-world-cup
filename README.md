# 🏆 World Cup 2026 - Family Bracket Challenge

A simple, fun bracket-picking app for your family to bet on the 2026 World Cup knockout rounds.

## How It Works

1. **Add players** — Enter everyone's name who wants to play
2. **Make picks** — Each player picks winners for every match from Round of 16 through the Final
3. **Final bonus** — For the Final, also predict the goal differential (1-5)
4. **Enter results** — As games are played, enter actual results in the ⚙️ Results tab
5. **Check scores** — The 🏅 Scores tab shows the leaderboard

## Scoring

| Round | Points per correct pick |
|-------|------------------------|
| Round of 16 | 2 pts |
| Quarterfinals | 4 pts |
| Semifinals | 8 pts |
| Final | 16 pts |
| Goal Differential (Final) | 5 pts bonus |

## Setup

Just open `index.html` in any browser — no server needed! All data is saved in your browser's localStorage.

### To customize teams

Edit the `TEAMS.r16` array in the `<script>` section of `index.html` to match the actual Round of 16 matchups once they're set.

## Features

- 📱 Works on mobile and desktop
- 💾 Auto-saves all picks locally
- 👨‍👩‍👧‍👦 Multiple players on one device
- 🏅 Live leaderboard with scoring
- ⚽ Goal differential bonus for the Final
