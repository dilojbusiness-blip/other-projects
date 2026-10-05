# Cover notes: Gray Divorce After 50

## Series position

A standalone Carol Dunn title, not a numbered book in any of the three existing lines. It therefore takes the fourth cover grammar in the catalogue while keeping the house DNA — Georgia caps title, Segoe UI support type, one hand-drawn solid SVG motif, one accent colour that also carries the author.

| | Family Paperwork (Ruth) | Plain Talk Retirement (Walt) | Caring for Mom and Dad (Maggie) | **This book (Carol)** |
|---|---|---|---|---|
| Ground | dark forest green | ivory `#f4eee2` | warm oat `#f4e9d8` | **graphite `#272d33`** |
| Structure | accent bands top **and** bottom | hairline + navy footer slab | inset double frame + accent pill | **thin accent hairline top, solid full-bleed accent footer band** |
| Accent | gold / copper / slate blue | brick / pine | terracotta / dusty blue | **jade `#5cbf8f`** |
| Title | serif caps + sans accent tail | serif caps + knockout bar | serif caps, last line in accent | serif caps, last line in accent |
| Author | sans caps on band | sans caps on slab | Georgia mixed case | **Georgia mixed case, knocked out on the accent band** |

Jade on graphite is the only cool-fresh accent in the catalogue; none of the three series can use it without breaking its own system, so the book is unmistakably a sibling of the house but not a member of a line. No series pill, because there is no series.

## Concepts considered

1. **Graphite + jade, one pot cut into two unequal halves (chosen)** — dark neutral ground, jade hairline at the head, three-line serif title with "AFTER 50" in jade, and a single large disc split by a vertical gap into a cream half and a jade half, the cut deliberately off-centre. Two heavy solid shapes, so it survives 160 px, and the whole premise of the book is legible before a word is read.
2. **A wedding band cut open into a dollar curve** — clever, but it is a thin ring stroke that vanishes at thumbnail size, and the visual pun pushes the book toward breakup-memoir rather than money guide.
3. **Cream + teal dotted path** (the `book.json` starter motif) — too generic. A dashed path says "journey" and says nothing about division of assets, and a 16 px dash stroke is invisible at 160 px.

## Title treatment

Three lines, under the four-line cap. "GRAY", "DIVORCE" and "AFTER 50" are Georgia caps at 244 px — 9.5% of cover height per line — with the third line in jade so the "after 50" qualifier separates from the subject without a bar or a rule. Text matches `book.json` exactly: title *Gray Divorce After 50*, the cover subtitle "The Money Moves That Actually Matter" taken verbatim from the start of the subtitle, the remainder "House, Retirement Accounts, and Starting Over Solvent" set as the tagline, and the author as Carol Dunn. Dark ground, so no KDP gray border is needed (that advice applies to light covers).

## Competitor conventions in this niche

Gray-divorce and divorce-finance covers cluster on white or pale-blue grounds with a torn paper heart, two broken wedding rings, a cracked house, a gavel on a stack of papers, or a stock photo of a woman looking out of a window — usually with a small sans title and a long subtitle crowded into the bottom third, often with a script accent word. Points of difference here: a dark graphite ground where the field is almost universally light; jade green instead of the category's blue, pink or black-and-red; no ring, no heart, no gavel and no cracked house; an abstract divided disc instead of a literal breakup symbol; a serif title that fills the midfield; and support text grouped into a tagline plus one solid accent band rather than scattered lines.

## Self-critique (final, render 4)

| Criterion | Score | Note |
|---|---|---|
| Thumbnail legibility at 160 px | 9 | Resolves to four clean bands — jade hairline, three-line title block with the jade last line, split disc, solid jade footer with the author — and nothing muddies. The colour change on "AFTER 50" keeps the three-line title countable. |
| Genre signal | 8 | Serif caps on a dark neutral ground with a single green accent reads money/finance explainer immediately, and the divided pot names the subject without a ring or a gavel. |
| Distinctiveness | 9 | Dark graphite plus jade is the opposite of the category's white-and-pale-blue torn-heart field, and an off-centre split disc is a motif nothing in the top results is running. |
| Professionalism | 9 | One type pairing (Georgia + Segoe UI), hand-drawn SVG, symmetrical margins, a single structural idea carried top and bottom, renderer reports **Layout OK** with all text inside the 60 px safe area. |
| Emotional pull | 8 | One pot becoming two unequal halves is the reader's actual situation stated without pity — and the unequal cut quietly says what the book says: the split is negotiated, not automatic. |

Contrast: cream `#f3efe6` on graphite `#272d33` and jade `#5cbf8f` on graphite are both far past 4.5:1; ink `#16202a` on the jade footer band clears it comfortably; the `#b9c2c6` subtitle at 78 px and the `#9fb6a9` tagline at 52 px both clear the large-text threshold.

## Iterations (4 renders, all with `cover.mjs`)

1. Hand-crafted graphite/jade design at 244 px title — **failed**: "title text overflows its box" (Georgia descenders at this size sit 15 px below the flex line box). Fixed with 26 px of padding on the title rather than by shrinking the type, so the 9.5%-per-line target survived.
2. **Layout OK**, but the disc was small for its box and a fixed 84 px gap left dead air above the tagline.
3. Disc radius up from 200 to 238 and the art and tagline moved onto `margin:auto` so the slack distributes — **Layout OK**, midfield now carried.
4. 40 px of breathing room restored under the tagline so it does not crowd the footer band — **Layout OK**. Final.

## Files

- `cover/cover.html` (source; Carol Dunn standalone grammar)
- `cover/cover.jpg` 1600x2560, 277,838 bytes
- `cover/thumb-400.png`, `cover/thumb-160.png`

The Formatter must rebuild so the EPUB embeds this cover.
