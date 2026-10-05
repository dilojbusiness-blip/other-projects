# Cover notes: Estate Planning for Beginners

## Concepts considered
1. **Green Folder (chosen)** - deep forest ground, accent bands top and bottom, line-art folder holding signed papers with a gold "done" check; cream Georgia title in two stacked words with a sans "for Beginners" in the accent colour. Literal, warm, and it reads as a single shape at thumbnail size.
2. **Open Door** - navy ground, gold arch doorway, title inside the arch. Handsome but the motif says nothing specific about paperwork and goes muddy at 160 px.
3. **Keystone / Shield** - cream ground, maroon shield, legal-crest feel. Too close to the cold corporate-law look that already saturates the category, and crests clutter at small sizes.

## Series system (The Family Paperwork Series)
`cover/cover.html` is the shared template. Sibling books copy it and change **only** the `--accent` custom property and the text. Ground colour, band heights, folder motif, type scale and spacing stay identical so the spines and thumbnails read as one shelf.

- Book 1 estate-planning-beginners - `#e8b45c` gold
- Book 2 executor-guide - `#d9814e` copper
- Book 3 parent-dies-first-90-days - `#8fbdd0` slate blue

Fonts are system only (Georgia for the title, Segoe UI for everything else). No external images, fonts or URLs.

## Competitor conventions in this niche (observed, not screenshotted this round)
Estate-planning covers cluster on navy or white grounds with gold serif type, and lean on gavels, columns, scales and family silhouettes. Many are template-flat with a small title and a long subtitle crammed into the lower third. Points of difference here: a forest-green ground instead of navy or white, a hand-drawn folder instead of legal iconography, title type that fills the midfield, and solid accent bands that carry the series name and the author at a size that still reads in a search grid.

## Self-critique (iteration 3, final)
| Criterion | Score | Note |
|---|---|---|
| Thumbnail legibility at 160 px | 9 | "ESTATE PLANNING" holds as two solid cream blocks; the gold bands anchor top and bottom; the folder stays a recognisable silhouette. |
| Genre signal | 9 | Deep green plus gold plus serif caps reads trust/legal/finance immediately; the folder of signed papers names the subject without a gavel. |
| Distinctiveness | 8 | Green ground, folder motif and full-bleed accent bands separate it from the navy-and-gavel field. |
| Professionalism | 9 | Even margins, one type pairing, hand-drawn SVG motif, no stock clip-art look; renderer reports all text inside the 60 px safe area. |
| Emotional pull | 8 | The gold check on the folder says "this is finished and findable", which is the promise the book makes. |

Contrast: cream `#f7f3e8` title on `#14332a` ground is well past 4.5:1; the dark `#14332a` band text on `#e8b45c` gold is also well past 4.5:1. Subtitle uses `#c4dbcb` at 66 px, comfortably above the threshold at that size.

Iterations: 1) starter template replaced with the hand-crafted folder design; 2) motif and series type enlarged, subtitle weight raised - the longer series line then broke the safe area; 3) series line split into a large series name plus a smaller "Book One", renderer reports **Layout OK**.

## Files
- `cover/cover.html` (source, series template)
- `cover/cover.jpg` 1600x2560
- `cover/thumb-400.png`, `cover/thumb-160.png`

The Formatter must rebuild so the EPUB embeds this cover.
