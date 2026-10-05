# Cover notes: The Dementia Caregiver's First Year

## Series position
Book Two of the **Caring for Mom and Dad Series** (Maggie Holloway). The cover inherits Book One's grammar unchanged and changes only the accent, the motif and the text, which is exactly how the series system was specified in `downsizing-parent/cover/NOTES.md`.

| | Family Paperwork (Ruth) | Plain Talk Retirement (Walt) | Caring for Mom and Dad (Maggie) |
|---|---|---|---|
| Ground | dark forest green | ivory `#f4eee2` | warm oat `#f4e9d8` |
| Structure | accent bands top **and** bottom | hairline + dark navy footer slab | inset double accent frame, accent pill at top, no slab |
| Accent | gold / copper / slate blue | brick / pine | Bk1 terracotta `#a84a22` / **Bk2 dusty blue `#3d6680`** |
| Title | serif caps + sans accent tail | serif caps + knockout bar | serif caps, last line set in the accent |
| Author | sans, letterspaced caps | sans, letterspaced caps on slab | Georgia, mixed case |
| Motif | line-art folder | geometric lettered sequence | solid two-object silhouette |

Dusty blue `#3d6680` was the reserved Book Two accent. It is cooler and calmer than Book One's terracotta — right for a medical subject — while the identical oat ground, frame, pill, type scale and silhouette motif keep the two titles reading as one shelf.

## Concepts considered
1. **Oat + dusty blue, empty armchair and a lit lamp (chosen)** — the same oat ground and double frame, a dusty-blue series pill, a four-line cocoa serif title with "FIRST YEAR" in the accent, and a solid-silhouette motif: her chair with an accent cushion, a lamp still switched on, and a faint accent pool of light spilling across the floor between them. Two heavy solid shapes on a common ground line, so it survives 160 px.
2. **A lamp alone, large and centered** (nearest to the `book.json` starter motif) — a single object is the most legible choice of all, but a lamp by itself is a generic "home" symbol and says nothing about who is doing the caring.
3. **Twelve-square calendar with four months filled** — literal about "the first year", but a grid of small squares turns to grey mush at thumbnail size and reads as a planner, not a caregiving book.

## Title treatment
Four lines, at the cap. "THE" is a small letterspaced muted lead-in at 78 px; "DEMENTIA", "CAREGIVER'S" and "FIRST YEAR" are Georgia caps at 202 px (7.9% of cover height per line) with "FIRST YEAR" in dusty blue so the promise separates from the subject without a bar or rule. Text matches `book.json` exactly: title *The Dementia Caregiver's First Year* with the curly apostrophe, the cover subtitle "Diagnosis, Safety, Hard Days, and Protecting Yourself" taken verbatim from the subtitle, the remaining words "A Practical Guide" set as the byline, and the author as **Margaret "Maggie" Holloway** with the curly quotes intact. Light ground, so per KDP advice the cover carries a 4 px medium-gray `#9aa2a6` border outside the accent frame.

## Competitor conventions in this niche
Dementia and Alzheimer's caregiving covers cluster on white or pale-lilac grounds with a purple ribbon, a fragmenting or jigsaw-piece brain, scattered puzzle pieces, a silhouette head dissolving into birds, or a stock photo of two clasped hands, usually with a small sans title and a long subtitle crowded at the bottom. Points of difference here: a warm oat ground instead of clinical white or lilac, dusty blue instead of the category's near-universal purple, no brain and no puzzle piece, a domestic two-object silhouette instead of a medical symbol, a serif title that fills the midfield, and support text grouped tightly under one accent rule.

## Self-critique (final, render 4)
| Criterion | Score | Note |
|---|---|---|
| Thumbnail legibility at 160 px | 9 | Resolves to five clean bands — blue pill, four-line title block with the accent last line, accent rule plus subtitle, chair-and-lamp silhouette, author — with no mush. The colour change on "FIRST YEAR" keeps the long title countable. |
| Genre signal | 8 | Warm oat ground, serif caps, a domestic armchair and a lamp read "caring for a parent at home" immediately, and the cooler accent signals a health subject rather than Book One's move logistics. |
| Distinctiveness | 9 | No purple, no ribbon, no brain, no puzzle piece — the three things every competitor in the category uses. An empty chair and a lamp left on is a motif nothing else in the field is running. |
| Professionalism | 9 | One type pairing (Georgia + Segoe UI), hand-drawn SVG, symmetrical margins, double accent frame, gray KDP border on a light cover, renderer reports **Layout OK** with all text inside the 60 px safe area. |
| Emotional pull | 9 | The empty chair with the lamp still on is the caregiver's year in one image: someone is still here, and someone is still watching out for them. It earns the feeling without a sentimental photo. |

Contrast: cocoa `#3a2a23` on oat `#f4e9d8` is far past 4.5:1; dusty blue `#3d6680` on oat clears 4.5:1 at the 202 px title and the 42 px byline; cream `#fdf8ef` on the `#3d6680` pill clears it; the `#6a5347` subtitle at 70 px and the "THE" lead-in at 78 px clear the large-text threshold comfortably.

## Iterations (4 renders, all with `cover.mjs`)
1. Hand-crafted oat/dusty-blue design at 222 px title — **failed**: "title outside safe area", "title text overflows its box", "Caregiver's is too wide" (four lines at Book One's scale do not fit the taller stack).
2. Title to 190 px, motif reduced to 1060x436 — **Layout OK**, but the title sat below the 9%-per-line target and the block looked timid against the frame.
3. Title back up to 212 px at -17 px tracking — **failed**: "title text overflows its box".
4. Title to 202 px at -15 px tracking — **Layout OK**, the four-line block now carries the midfield, the accent last line reads at 160 px, and the chair and lamp sit clear of the rule and the byline. Final.

## Files
- `cover/cover.html` (source; Caring for Mom and Dad series template, Book Two)
- `cover/cover.jpg` 1600x2560, 424,914 bytes
- `cover/thumb-400.png`, `cover/thumb-160.png`

The Formatter must rebuild so the EPUB embeds this cover.
