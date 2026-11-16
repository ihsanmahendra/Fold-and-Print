# Tint Tangle — prototype

Hybrid casual color-mixing puzzle. Only red, yellow and blue paint exist; green, orange and purple pixels must be mixed by painting two colors on the same pixel.

## Play

Open `index.html` in any browser (desktop or phone). No build step, no dependencies.

## How it plays

- Tap the front bucket of a rack column. It rides the belt around the picture.
- Each step, the bucket sprays the first unfinished pixel in its line, if that pixel still needs its color.
- Finished pixels let paint pass through; half-mixed pixels (striped) block other colors until finished.
- A bucket with paint left after one lap parks in the Dock. Dock full = lose. Picture complete = win.

## What's in this build

| Level | Teaches |
| --- | --- |
| 1 Cherry | Tap, spray, primaries |
| 2 Frog | Green = Blue + Yellow |
| 3 Sunset | Orange, mixed edges blocking inner pixels |
| 4 Grapes | Purple, hidden `?` buckets |
| 5 Parrot | Frozen pixels (one hit of any color cracks the ice) |

Prototype limits: difficulty is not tuned yet (levels are teaching levels), no meta/Gallery, no boosters except the +1 Dock slot on fail.
