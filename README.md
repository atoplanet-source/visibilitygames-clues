# Who's That? - Clue Reviewer

A tool for reviewing, editing, and AI-generating clues for the "Who's That?" celebrity guessing game.

## Features

- **Upload CSV** - Import celebrity clue data
- **Review & Edit** - Click through clues card-by-card
- **AI Remake** - Use Claude to regenerate individual clues with custom guidance
- **Progress Tracking** - See how many clues you've approved
- **Export** - Download approved clues as CSV

## Clue Format

Each celebrity has 5 clues that progressively get easier:

| Clue | Difficulty | Description |
|------|------------|-------------|
| 1 | Hardest | Super niche, weird fact ("wait, what?") |
| 2 | Hard | Interesting but obscure |
| 3 | Medium | The "aha" moment - should click here |
| 4 | Easy | Getting obvious |
| 5 | Easiest | Dead giveaway |

**Guidelines:**
- Max 20-25 characters (shorter is better)
- Crossword-style phrasing (punchy, clever)
- Fun facts that teach something interesting
- Diverse categories: athletes, musicians, actors, activists, designers, etc.

## CSV Format

```csv
Answer,Clue 1,Clue 2,Clue 3,Clue 4,Clue 5,Category
Michael Jordan,Food poisoning flu game,"Wore #12 once, scored 49",UNC shorts under uniform,"Cut from HS team, 6 rings",Space Jam star,Athlete
```

## Setup

1. Get a Claude API key from [console.anthropic.com](https://console.anthropic.com)
2. Open the app and enter your API key
3. Upload a CSV file with clues
4. Review, edit, and remake clues as needed
5. Export approved clues

## Tech Stack

- HTML5 / Tailwind CSS (CDN)
- Vanilla JavaScript
- Claude API for AI clue generation

## License

© 2025 Visibility Games. All rights reserved.
