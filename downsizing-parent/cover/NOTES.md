# Cover notes: Downsizing a Parent

## Series position
Book One of the **Caring for Mom and Dad Series** (Maggie Holloway). This is the third series grammar in the catalogue and it deliberately avoids both existing systems so the shelf never reads as one undifferentiated line:

| | Family Paperwork (Ruth) | Plain Talk Retirement (Walt) | Caring for Mom and Dad (Maggie) |
|---|---|---|---|
| Ground | dark forest green | ivory `#f4eee2` | warm oat `#f4e9d8` |
| Structure | accent bands top **and** bottom | accent hairline + dark navy footer slab | inset double accent frame, solid accent pill at top, no slab |
| Accent | gold / copper / slate blue | brick / pine | **terracotta `#a84a22`** |
| Title | serif caps + sans accent tail | serif caps + knockout accent bar | serif caps, second line set in the accent |
| Author | sans, letterspaced caps | sans, letterspaced caps on slab | **Georgia, mixed case** (warmer, more human) |
| Motif | line-art folder | geometric lettered sequence | solid two-object silhouette |

Accent reserved for Book Two (`dementia-caregiver`) is a cooler warm — dusty blue `#44708c` or heather `#6d5580` — with frame, pill, type scale and motif grammar unchanged.

## Concepts considered
1. **Oat + terracotta, big house → small house (chosen)** — warm light ground, double terracotta frame, accent series pill, cocoa serif title with "A PARENT" in terracotta, and a solid-silhouette motif of a large dark house, an accent arrow, and a smaller terracotta house sitting on a common ground line. The entire premise of the book is legible as a shape before a word is read, and the two solid houses survive a 160 px thumbnail where any line-art version would not.
2. **Stacked moving boxes with a labelled lid** (the `book.json` starter motif) — on-topic but boxes are the single most-used object in the downsizing category, which risks a look-alike cover, and a stack of same-sized rectangles turns to grey mush at thumbnail size.
3. **Open front door with a key** — emotionally warm, but a door says "home" generically and nothing about *moving*, and a thin key outline disappears at 160 px.

## Title treatment
Two lines, well under the four-line cap. "DOWNSIZING" and "A PARENT" are Georgia caps at 200 px, 7.8% of cover height per line, cocoa `#3a2a23` on oat for line one and terracotta for line two so the two halves separate without a bar or a rule between them. Title, subtitle wording and author all come from `book.json`: title *Downsizing a Parent*, the shortened cover subtitle "The Next Home, the Belongings, and the Family", the remainder of the long subtitle set as the byline "A Practical, Step-by-Step Guide", and the author as **Margaret "Maggie" Holloway** with the curly quotes intact. Light ground, so per KDP advice the whole cover carries a 4 px medium-gray `#9aa2a6` border outside the terracotta frame.

## Competitor conventions in this niche
Downsizing and senior-move covers cluster on white or pale-blue grounds with cardboard-box photography, a stock photo of an older couple with a realtor, or a hand-lettered "declutter" script, almost always with a small sans title and a long subtitle crowded into the bottom third. Points of difference here: a warm oat ground rather than clinical white, terracotta rather than the category's pale blue, a drawn solid-silhouette motif instead of box photography, a serif title that fills the midfield, and support text grouped tightly under a single accent rule rather than scattered.

## Self-critique (final, render 3)
| Criterion | Score | Note |
|---|---|---|
| Thumbnail legibility at 160 px | 9 | At 160 px the cover resolves to four clean bands — terracotta pill, two-tone title block, accent rule plus subtitle, house-arrow-house silhouette — with no mush. The colour split between the two title lines keeps them countable as separate words. |
| Genre signal | 8 | Warm palette, serif caps and a house-to-house move read "family / later-life logistics" immediately, and the warm ground signals caregiving rather than the cold legal-finance look of the Ruth series. |
| Distinctiveness | 9 | Oat and terracotta is the opposite of the category's white-and-pale-blue box photography, and the big-house-to-small-house silhouette is a motif no competitor in the top results is using. |
| Professionalism | 9 | One type pairing (Georgia + Segoe UI), hand-drawn SVG, symmetrical margins, double accent frame, gray KDP border on a light cover, renderer reports **Layout OK** with all text inside the 60 px safe area. |
| Emotional pull | 8 | Two houses and an arrow say "this move has a destination, and it is still a home" — the reassurance the reader holding the clipboard actually needs, without sentimentality. |

Contrast: cocoa `#3a2a23` on oat `#f4e9d8` is far past 4.5:1; terracotta `#a84a22` on oat clears 4.5:1 at both the title and byline sizes; cream `#fdf8ef` on the terracotta pill clears it; the `#6a5347` subtitle at 70 px clears the large-text threshold comfortably.

## Iterations (3 renders, all with `cover.mjs`)
1. Hand-crafted oat/terracotta design at 214 px title — **failed**: "title outside safe area", "title text overflows its box", "Downsizing is too wide".
2. Title to 184 px at -6 px tracking — **Layout OK**, but the title sat below the 9%-per-line target and left dead air between the rule and the motif.
3. Title to 200 px at -13 px tracking, byline changed to the exact `book.json` subtitle remainder "A Practical, Step-by-Step Guide" — **Layout OK**, the title block now carries the midfield and the two-tone split reads at 160 px. Final.

## Files
- `cover/cover.html` (source; Caring for Mom and Dad series template, Book One)
- `cover/cover.jpg` 1600x2560, 387,375 bytes
- `cover/thumb-400.png`, `cover/thumb-160.png`

The Formatter must rebuild so the EPUB embeds this cover.
