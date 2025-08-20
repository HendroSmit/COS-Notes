# COS-Notes — Curse of Strahd Reloaded (3 players)

Lightweight Markdown notes for a DnD 5e campaign using Curse of Strahd Reloaded.

- Campaign guide: [A DM's Guide to Curse of Strahd](https://www.strahdreloaded.com/Introduction/A+DM's+Guide+to+Curse+of+Strahd)

## Files

- `Campaign_Summary.md` — Big-picture overview: players/characters, relics/motivations, adventure hook, and a Sessions Index.
- `Session_1.md` — Session 1 log: Death House (arrival and first floor).
- `Session_2.md` — Prepared template/log for the next session (upper floors and descent).

## How to add a new session

1. Duplicate the latest session file and rename, e.g., `Session_2.md` → `Session_3.md`.
2. Update the H1 title and recap at the top.
3. Keep the structure: recap → timekeeping → party loadout → clues/leads → objectives → risks → room log → NPCs/entities → loot → to-do.
4. Add the new session to the Sessions Index table in `Campaign_Summary.md` with a brief highlight.

## Conventions

- Use a top-level H1 for each session file title.
- Character blurbs as H2 headings; include a short, punchy description and alignment.
- Add a “Clues and Leads” section to capture puzzles, items, time pressure, and open questions.
- Prefer Markdown links over bare URLs to keep lint clean.

## Publish to GitHub (optional)

From the repository folder in PowerShell:

```powershell
# First-time setup (if needed)
git init
git add .
git commit -m "Initial notes"
git branch -M main
# Replace with your repo URL
git remote add origin https://github.com/<your-user>/COS-Notes.git
git push -u origin main
```

Troubleshooting remotes (if `remote origin already exists`):

```powershell
# See configured remotes
git remote -v
# Update existing origin to a new URL
git remote set-url origin https://github.com/<your-user>/COS-Notes.git
# Or remove and re-add
git remote remove origin
git remote add origin https://github.com/<your-user>/COS-Notes.git
```

## Tips

- Keep highlights short in the Sessions Index; put detail in the session file.
- Track in-world time in Death House toward midnight (per the riddle) to keep tension.
- Silvered bolts are limited—note who holds them.
