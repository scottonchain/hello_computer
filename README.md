# Hello Computer

This repository draws **HELLO HUMAN** on the 2025 GitHub contribution graph using backdated commits.

## How it works

- Each lit square (pixel day) receives exactly **25 commits**
- All commits are backdated to specific days in 2025
- The commit history gradually builds a miniature singularity story

## Stats

- Pixel days: 113
- Commits per pixel day: 25
- Total pixel commits: 2,825

## Files

- `draw_hello_human.py` — Reference script with the approved date list and letter pattern. For documentation and preview only.
- `pixels.txt` — The 113 target dates in chronological order.
- `singularity_story.txt` — A miniature singularity story, built one line per commit.
- `README.md` — This file.

## Reproduction

The original commit history was created using direct git commands with backdated timestamps:

```bash
GIT_AUTHOR_DATE="2025-01-06T12:00:00+00:00" \
GIT_COMMITTER_DATE="2025-01-06T12:00:00+00:00" \
git commit -m "pixel 001.01"
```

The `draw_hello_human.py` script is for reference and preview only — it was not used to create the commit history.
