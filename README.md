# python-foundations

Phase 1 of my 12-month BIE / Data Engineer learning pathway: getting fluent in everyday Python after CS50.

## What's in here
| Folder | What it contains |
|---|---|
| `exercises/` | My solutions to Exercism, LeetCode and Practice Python problems, grouped by topic |
| `fpl_lookup/` | A small command-line tool that looks up Fantasy Premier League players using the public FPL API |
| `tests/` | pytest tests for the FPL tool |
| `LEARNING_LOG.md` | A weekly 3-line log of what I learned |

## FPL player lookup
Type a player's name and get their team, price, total points and form.

```bash
python -m fpl_lookup.cli salah
```

Example output:
```
M.Salah (Liverpool) | £13.5m | 210 pts | form 7.2
```
*(numbers are illustrative)*

**Skills shown:** classes and dataclasses, working with an API and JSON, error handling, command-line arguments, unit tests.

## How to run
```bash
git clone https://github.com/amosmaan/python-foundations.git
cd python-foundations
python -m venv .venv
.venv\Scripts\activate        # Windows  (macOS/Linux: source .venv/bin/activate)
pip install -r requirements.txt
python -m fpl_lookup.cli salah
pytest
```

## Data source
Public Fantasy Premier League API (`fantasy.premierleague.com/api/bootstrap-static/`). This is an unofficial, undocumented endpoint, used here for personal learning only.

## What I learned / next
*(Fill this in at the end of Phase 1.)*
