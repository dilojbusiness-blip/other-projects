# Cover notes: Medicare Made Plain

## Series position
Book One of the **Plain Talk Retirement Series** (persona: Walter Brennan, retired civics teacher). This is a *different* series line from Ruth Calloway's Family Paperwork Series, so the cover deliberately inverts that system rather than extending it:

| | Family Paperwork (Ruth) | Plain Talk Retirement (Walt) |
|---|---|---|
| Ground | dark forest green | light ivory `#f4eee2` |
| Structure | accent band top **and** bottom | thin accent hairline top, one dark navy slab bottom |
| Accent | gold / copper / slate blue | brick red `#b1392b` |
| Title | serif caps + sans accent tail | serif caps + knockout serif bar |
| Motif | line-art folder | geometric A/B/C/D step sequence |

Accent reserved for Book Two (social-security-2027) will differ from brick; ground, slab, hairline, type scale and motif grammar stay identical so the two read as one shelf.

## Concepts considered
1. **Ivory + brick, A-B-C-D staircase (chosen)** - light ground, brick hairline and knockout title bar, four descending chevron steps lettered A, B, C, D, dark navy footer slab carrying subtitle, tagline and author. Reads as "four parts, in order" at any size, which is exactly the book's argument.
2. **Navy + gold calendar grid** - deadline-season framing with a circled date. Handsome but navy-and-gold is the single most crowded look in the Medicare category, and a grid dissolves to grey mush at 160 px.
3. **Cream + teal open door / path** (the `book.json` starter motif) - too generic; a dotted path says "journey" but says nothing about Medicare, and a thin dashed stroke is invisible in a thumbnail.

## Title treatment
Two lines, well under the four-line cap. "MEDICARE" is Georgia caps at 238 px (9.3% of cover height) in navy on ivory; "MADE PLAIN" is Georgia caps at 188 px knocked out in cream on a full brick bar. The bar is the single strongest shape on the cover and it carries the promise. Text matches `book.json` exactly: title *Medicare Made Plain*, cover subtitle "The 2027 Enrollment Season Guide" with the rest of the long subtitle set as the tagline underneath, author Walter Brennan.

Light ground, so per KDP advice the whole cover carries a 4 px medium-gray `#9aa2a6` border.

## Competitor conventions in this niche (observed from category convention, not screenshotted this round)
Medicare covers cluster hard on navy or teal grounds with gold or white sans type, a red-white-blue card graphic, stethoscopes, or a smiling stock couple; many pile a 30-word subtitle into small type at the bottom. Points of difference here: a *light* ivory ground (almost nobody in the category goes light), brick red rather than patriotic blue/gold, a knockout serif bar rather than a sans headline, an abstract A/B/C/D sequence instead of a card or stethoscope, and support text grouped into one dark slab so it reads as a block rather than as scattered lines.

## Self-critique (final, render 2)
| Criterion | Score | Note |
|---|---|---|
| Thumbnail legibility at 160 px | 9 | "MEDICARE" is dark on ivory and "MADE PLAIN" is a solid brick bar; at 160 px the cover resolves to three bands (ivory title / stepped motif / navy slab) with no mush. |
| Genre signal | 8 | Serif caps, muted ivory, navy slab and a lettered A-B-C-D sequence read retirement/benefits/government-explainer immediately without using a stethoscope or a flag. |
| Distinctiveness | 9 | Light ground plus brick accent is the opposite of the navy-and-gold Medicare field, and the A/B/C/D staircase is a motif no competitor is using. |
| Professionalism | 9 | One type pairing (Georgia + Segoe UI), hand-drawn SVG, even margins, gray border on a light cover, renderer reports **Layout OK** with all text inside the 60 px safe area. |
| Emotional pull | 8 | Steps that descend in order say "this is a sequence and I will walk you down it", which is the exact fear (missing a step, paying a lifetime penalty) the book answers. |

Contrast: navy `#0f3242` on ivory `#f4eee2` and cream `#fbf7ef` on brick `#b1392b` are both far past 4.5:1; cream subtitle on the navy slab is past 4.5:1; the `#a9c6d2` tagline at 48 px on `#0f3242` clears 4.5:1.

## Iterations (2 renders, both with `cover.mjs`)
1. Hand-crafted ivory/brick design with a vertical 560 px A-B-C-D ribbon stack on a center spine - **Layout OK**, but the spine plus four same-width ribbons read as a cluttered column at 160 px and wasted the horizontal midfield.
2. Motif redrawn as a 1020 px-wide descending chevron staircase (A and B navy, C and D brick) - **Layout OK**, fills the midfield, and the diagonal step read survives the 160 px thumbnail. Final.

## Files
- `cover/cover.html` (source; Plain Talk Retirement series template)
- `cover/cover.jpg` 1600x2560, 367714 bytes
- `cover/thumb-400.png`, `cover/thumb-160.png`

The Formatter must rebuild so the EPUB embeds this cover.
