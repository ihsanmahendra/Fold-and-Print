# Fold & Print — prototype

Hybrid casual paper-folding puzzle. Fold a sheet with wet paint blots so the paint prints onto the other side and matches the target picture. Where two colors land on each other they mix: blue + yellow = green.

## Play

Open `index.html` in any browser (desktop or phone). No build step, no dependencies.

## Rules

- Tap a crease tab (under the sheet for vertical folds, right of it for horizontal), check the preview, then tap FOLD.
- Both sides of the fold print onto each other (like an ink-blot butterfly).
- Paint landing where the target has none = Smudged (lose). Using all folds without matching = lose.
- Taped squares can't receive paint; tape peels off after one fold.
- Dry paint (matte, dotted ring) never prints but can still receive.

## Sheets in this build

| # | Sheet | Teaches |
| --- | --- | --- |
| 1 | Butterfly | Fold = mirror print |
| 2 | Leaf | Blue + Yellow = Green |
| 3 | Flower | Two folds |
| 4 | Lighthouse | Off-center creases |
| 5 | Kite | Tape, fold order |
| 6 | Owl | Dry paint |

Every sheet was brute-force checked: each has a winning fold sequence, and most first folds smudge, so the choice matters.
