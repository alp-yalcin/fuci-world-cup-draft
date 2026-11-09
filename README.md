# FUCI World Cup Draft ⚽

**[Play it here](https://alp-yalcin.github.io/fuci-world-cup-draft/)** · Turkish UI · no install, no account

Build your dream XI from World Cup legends, then take it through a simulated World Cup against the greatest national teams in history.

## Features

- **350 legends from 48 nations**, each rated by position and World Cup year
- **Tactical draft board** with four formations (4-3-3, 4-4-2, 3-5-2, 4-2-3-1), limited re-rolls and position-aware picks
- **World Cup simulation** against 92 historic national teams, with a live event feed for every match
- **Friends League without accounts or a server:** your squad becomes a short code you share in a group chat; results are seeded, so every friend sees exactly the same matches

## How it's built

One self-contained `index.html`: vanilla JavaScript, CSS and the player database in a single file, no build step and no backend. Team codes are base64-encoded squads and the match engine uses a seeded random generator, which is what makes a serverless league possible.

Built by directing AI coding tools; the game idea, product decisions and testing are mine.
