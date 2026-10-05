# Cover notes: Living on GLP-1 Medicines

## Series position

Book One of the **Health Series** (Dana Whitfield). This is the fifth cover grammar in the catalogue. It keeps the house DNA — Georgia caps title, Segoe UI support type, one hand-drawn solid SVG motif, a single accent colour — while taking a ground and a structure that none of the four existing lines owns.

| | Family Paperwork (Ruth) | Plain Talk Retirement (Walt) | Caring for Mom and Dad (Maggie) | Gray Divorce (Carol) | **Health Series (Dana)** |
|---|---|---|---|---|---|
| Ground | dark forest green | ivory `#f4eee2` | warm oat `#f4e9d8` | graphite `#272d33` | **chalk `#f7f7f3`** |
| Structure | accent bands top **and** bottom | hairline + navy footer slab | inset double frame + accent pill | hairline top + accent footer band | **full-bleed accent title block floating mid-canvas; no edge band, no frame** |
| Accent | gold / copper / slate blue | brick / pine | terracotta / dusty blue | jade | **warm ochre `#d9962b`** |
| Title | serif caps + sans accent tail | serif caps + knockout bar | serif caps, last line in accent | serif caps, last line in accent | **serif caps knocked dark on a solid accent block** |
| Author | sans caps on band | sans caps on slab | Georgia mixed case | Georgia on accent band | **Segoe UI letterspaced caps, on the ground** |

Ochre on chalk is the only warm-bright pairing in the catalogue, and the title block is the only structure that puts the accent in the middle of the canvas rather than at an edge — so the book is unmistakably a sibling of the house but starts its own line. Accent reserved for Health Series Book Two is a cooler warm (clay or olive) with the chalk ground, block structure, type scale and motif grammar unchanged.

## Concepts considered

1. **Chalk + ochre, a dumbbell resting on a dinner plate (chosen)** — near-white ground, a full-bleed ochre block carrying the three-line serif title, and a single motif that is two heavy solid shapes on one axis: a warm ochre plate ring with a dark dumbbell lying across it. The entire thesis of the book — eat the protein, keep the muscle — is legible as a shape before a word is read, and both shapes survive 160 px.
2. **A protein-filled plate divided into thirds** — accurate to the content, but a segmented plate is the single most-used graphic in diet publishing, so it risks reading as a look-alike, and the thin divider lines vanish in a thumbnail.
3. **Chalk + sage, a kitchen outline** (the `book.json` starter motif) — too generic. A cooktop or utensil says "cookbook", which is exactly what this book says it is not, and sage on chalk is low enough in contrast to go grey at thumbnail size.

## Title treatment

Three lines, under the four-line cap. "LIVING ON", "GLP-1" and "MEDICINES" are Georgia caps at 232 px — 9.1% of cover height per line — set dark `#23291d` on the solid ochre block, so the block itself is the strongest shape on the cover and the title rides it. No colour change is needed to keep the lines countable because the block already separates the title from everything else. Text matches `book.json` exactly: title *Living on GLP-1 Medicines*, the cover subtitle "Protein, Muscle and Maintenance" taken verbatim from the start of the subtitle, the remainder "For the Life You're Building Now" set as the tagline, and the author as Dana Whitfield. Light ground, so per KDP advice the cover carries a 4 px medium-gray `#9aa2a6` border.

## Competitor conventions in this niche

(Amazon search returned 503 on this round, so this is category convention rather than a fresh screenshot set — the same fallback `medicare-2027` used.) GLP-1 and semaglutide covers cluster on clinical white or pale-blue grounds with a syringe or injector pen, a measuring tape wrapped around a waist, a downward weight-loss arrow, a plate of salmon and broccoli photography, or an ozempic-blue sans headline, usually with a long subtitle crowded into the bottom third. Points of difference here: a warm chalk ground instead of clinical white; ochre instead of the category's near-universal medical blue; **no syringe, no pen, no tape measure and no scale**; a drawn solid-silhouette dumbbell-on-plate instead of food photography; a serif title on a solid accent block rather than a sans headline; and support text grouped into one subtitle plus one tagline rather than scattered.

## Self-critique (final, render 2)

| Criterion | Score | Note |
|---|---|---|
| Thumbnail legibility at 160 px | 9 | Resolves to four clean bands — small kicker, solid ochre title block, subtitle, plate-and-dumbbell silhouette over the author — with no mush. The ochre block is the highest-contrast element on a retail page of white and pale-blue competitors. |
| Genre signal | 8 | A plate and a weight on a clean light ground reads health/nutrition/fitness immediately, and the serif title keeps it in guide territory rather than cookbook or clinical-textbook territory. |
| Distinctiveness | 9 | No syringe, no pen, no tape measure, no scale and no medical blue — the five things the category runs on. A dumbbell lying on a dinner plate is a motif nothing in the field is using, and it states the book's actual argument instead of its drug. |
| Professionalism | 9 | One type pairing (Georgia + Segoe UI), hand-drawn SVG, symmetrical margins, one structural idea, gray KDP border on a light cover, renderer reports **Layout OK** with all text inside the 60 px safe area. |
| Emotional pull | 8 | The weight sitting *on* the plate says the two are one job, not two — which is the reassurance a reader losing weight fast and worrying about losing strength actually needs. No before/after body, no shame. |

Contrast: ink `#23291d` on chalk `#f7f7f3` and ink on ochre `#d9962b` are both far past 4.5:1; the `#5d6354` kicker at 50 px, subtitle at 80 px and tagline at 54 px all clear 4.5:1 on chalk, and the two larger of those clear the large-text threshold with room to spare.

## Iterations (2 renders, both with `cover.mjs`)

1. Hand-crafted chalk/ochre design, title 232 px with 22 px of padding for Georgia's descenders, motif 1160x560 — **Layout OK** first pass, but the subtitle at full ink weight competed with the title block and the motif sat small inside its box with slack above and below.
2. Subtitle dropped to `--muted` so the hierarchy runs block → subtitle → motif, motif box up to 1240x598 with the viewBox tightened to 1160x540 so the plate fills the midfield — **Layout OK**. Final.

## Files

- `cover/cover.html` (source; Health Series template, Book One)
- `cover/cover.jpg` 1600x2560, 303,519 bytes
- `cover/thumb-400.png`, `cover/thumb-160.png`

The Formatter must rebuild so the EPUB embeds this cover.
