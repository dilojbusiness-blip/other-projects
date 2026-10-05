# Cover notes: The FAFSA, Step by Step

## Series position

A standalone Priya Raman college-aid title — the sixth cover grammar in the catalogue. It keeps the house DNA (Georgia caps title, Segoe UI support type, one hand-drawn solid SVG motif, a single accent colour that also carries the author) while taking a ground, an accent and a structure that none of the five existing lines owns.

| | Family Paperwork (Ruth) | Plain Talk Retirement (Walt) | Caring for Mom and Dad (Maggie) | Gray Divorce (Carol) | Health Series (Dana) | **This book (Priya)** |
|---|---|---|---|---|---|---|
| Ground | dark forest green | ivory `#f4eee2` | warm oat `#f4e9d8` | graphite `#272d33` | chalk `#f7f7f3` | **deep indigo `#1b2447`** |
| Structure | accent bands top **and** bottom | hairline + navy footer slab | inset double frame + accent pill | hairline top + accent footer band | accent title block mid-canvas | **no edge band, no frame: one solid cream form card floating in the lower midfield** |
| Accent | gold / copper / slate blue | brick / pine | terracotta / dusty blue | jade | ochre | **sky `#5ecbdc`** |
| Title | serif caps + sans accent tail | serif caps + knockout bar | serif caps, last line in accent | serif caps, last line in accent | serif caps on accent block | serif caps, last line in accent |
| Author | sans caps on band | sans caps on slab | Georgia mixed case | Georgia on accent band | Segoe UI caps on ground | **Georgia caps in accent, on the ground** |

Sky on indigo is the only cool-bright pairing in the catalogue, and the floating cream card is the only structure that makes the artifact — not a band, a frame or a type block — the brightest shape on the cover. So the book is unmistakably a sibling of the house without joining any line. No series pill, because there is no series.

## Concepts considered

1. **Indigo + sky, a cream form card with three boxes checked and one still open (chosen)** — deep indigo ground, a sky `2027-2028` year badge at the head, a three-line serif title with "STEP" in sky, and one large solid cream card carrying a title bar, three filled sky checkboxes and one empty outlined box. Heavy solid shapes only, so it survives 160 px, and the book's whole promise — the form, worked top to bottom, one box at a time, with you still mid-way through it — is legible before a word is read.
2. **A graduation cap over a dollar sign** — instantly on-genre, which is the problem: it is the single most-copied object in the college-aid category and edges toward a look-alike cover. The mortarboard tassel is also a thin stroke that disappears in a thumbnail.
3. **Cream + teal dotted path with a campus gate** (the `book.json` starter direction) — too generic. A path says "journey" and says nothing about a federal form, and a dashed 16 px stroke is invisible at 160 px.

## Title treatment

Three lines, well under the four-line cap. "THE FAFSA,", "STEP BY" and "STEP" are Georgia caps at 232 px — 9.1% of cover height per line — with the third line in sky so the repetition in the title separates visually instead of reading as one run-on block. Text matches `book.json` exactly: title *The FAFSA, Step by Step*; cover subtitle "A Parent's Plain-English Guide to the 2027-28 Form" taken verbatim from the start of the long subtitle; the remainder "Accounts, Assets, Awards and Appeals" set as the tagline; author Priya Raman. The badge carries the award year as `2027-2028`, matching `book.json`'s cover block. Dark ground, so no KDP gray border is needed (that advice applies to light covers).

## Competitor conventions in this niche

(No fresh Amazon screenshot set this round — the search page was not retrievable, the same fallback `medicare-2027` and `glp1-life` used — so this is category convention.) FAFSA and paying-for-college covers cluster on white, pale-blue or primary-red grounds with a graduation cap, a mortarboard on a stack of cash, a piggy bank wearing a cap, a diploma scroll, a calculator, or stock photography of a smiling student on a campus lawn, usually with a sans headline and a long subtitle crowded into the bottom third. Points of difference here: a *dark* indigo ground where the field is almost universally light; sky cyan instead of the category's navy-and-red or school-brand primaries; **no cap, no piggy bank, no diploma and no student photo**; a drawn solid form card instead of a money or campus symbol; a serif title that fills the upper two-thirds; and support text grouped into one subtitle plus one tagline rather than scattered lines.

## Self-critique (final, render 1)

| Criterion | Score | Note |
|---|---|---|
| Thumbnail legibility at 160 px | 9 | Resolves to four clean bands — sky year badge, three-line title block with the sky last line, bright cream card, accent author line — and nothing muddies. The card is a single high-contrast rectangle, so it reads as "a form" at thumbnail size without any of its internal rows needing to be legible. |
| Genre signal | 8 | A checkbox form on a dark institutional indigo with a prominent award year reads "federal paperwork guide, this year's edition" immediately, which is exactly the shelf, without borrowing a mortarboard. |
| Distinctiveness | 9 | Dark indigo plus cyan is the inverse of the white-and-navy, cap-and-piggy-bank field, and a cream form card with three boxes done and one open is a motif nothing in the top results is running. It also states the book's method rather than its topic. |
| Professionalism | 9 | One type pairing (Georgia + Segoe UI), hand-drawn SVG, symmetrical margins, one structural idea, renderer reports **Layout OK** with all text inside the 60 px safe area on the first pass. |
| Emotional pull | 8 | Three boxes checked and one still empty is the reader's actual position — part-way through, not finished, not lost — and the fourth box being merely outlined rather than crossed out says the remaining work is doable. No anxious student, no tuition-bill dread. |

Contrast: cream `#f4f1e8` on indigo `#1b2447` and sky `#5ecbdc` on indigo are both far past 4.5:1; indigo ink on the sky badge and on the cream card clears it comfortably; the `#b6c1dd` subtitle at 74 px and the `#8e9cc4` tagline at 54 px both clear the large-text threshold.

## Iterations (1 render, with `cover.mjs`)

1. Hand-crafted indigo/sky design: badge, 232 px three-line title with 26 px of padding for Georgia's descenders, 360 px accent rule, subtitle, 1040x666 form card on `margin-top:auto` so the slack distributes, tagline, author — **Layout OK** first pass, every criterion >= 8 at 160 px, so no re-render was made. Final.

## Files

- `cover/cover.html` (source; Priya Raman standalone grammar)
- `cover/cover.jpg` 1600x2560, 301,113 bytes
- `cover/thumb-400.png`, `cover/thumb-160.png`

The Formatter must rebuild so the EPUB embeds this cover.
