# Cover notes: The Executor's Step-by-Step Guide

## Concept (series continuation, not a fresh design)
This is **Book Two of The Family Paperwork Series**, so the brief was to copy the series look rather than invent one. `cover/cover.html` is a direct copy of `books/estate-planning-beginners/cover/cover.html` with only the accent swap and the text changed, exactly as that file's header instructs:

- Book 1 estate-planning-beginners - `#e8b45c` gold
- **Book 2 executor-guide - `#d9814e` copper (this book)**
- Book 3 parent-dies-first-90-days - `#8fbdd0` slate blue

Unchanged from Book 1: forest ground (`#14332a` to `#1e4a3a`), 212 px top band and 280 px bottom band, the line-art folder with signed papers and the accent "done" check, Georgia title over Segoe UI support type, the 300x14 accent rule, and all margins. The top band now reads "Book Two". Text matches `book.json` (title split as THE / EXECUTOR'S / STEP-BY-STEP / GUIDE, the shortened cover subtitle, author Ruth Calloway).

One addition beyond the accent: copper is a darker accent than Book 1's gold, so band text moved from `--ground` `#14332a` to `--bandink` `#0f2a21` to keep the series name and the author name comfortably above 4.5:1 on the copper band.

## Title treatment
The title is four lines (the series rule caps at four). "THE" is a small cream kicker, "EXECUTOR'S" and "GUIDE" are the Georgia caps, and "STEP-BY-STEP" is the copper sans line that does the work Book 1's "for Beginners" line does. The serif lines render at 196 px, about 7.7% of cover height each, and the stack as a whole fills the midfield.

## Self-critique (final, render 3)
| Criterion | Score | Note |
|---|---|---|
| Thumbnail legibility at 160 px | 9 | EXECUTOR'S and GUIDE hold as solid cream blocks; the copper STEP-BY-STEP line separates them without mushing; bands anchor top and bottom. |
| Genre signal | 9 | Deep green, copper and serif caps read legal/trust instantly, and the folder of signed papers plus the check names estate paperwork. |
| Distinctiveness | 8 | Green ground, folder motif and full-bleed bands stay clear of the navy-and-gavel probate field, and the copper separates it from its own Book 1. |
| Professionalism | 9 | Series-identical geometry, one type pairing, hand-drawn SVG, renderer reports all text inside the 60 px safe area. |
| Emotional pull | 8 | "STEP-BY-STEP" plus the completed-folder check promises a finite job with an end, which is what a new executor wants to hear. |

Contrast: cream `#f7f3e8` on `#14332a` ground is far past 4.5:1; `#0f2a21` on copper `#d9814e` is past 4.5:1; the `#c4dbcb` subtitle at 66 px clears the large-text threshold.

## Iterations (3 renders, all with `cover.mjs`)
1. Copy of the Book 1 template at 224 px title - **failed**: "title outside safe area", "EXECUTOR'S is too wide".
2. Title to 186 px, copper sans line to 112 px - **Layout OK**, but the serif had spare room and the "THE" kicker was too faint in `--soft` at thumbnail size.
3. Serif up to 196 px, kicker to `--ink` cream at 78 px/700 weight - **Layout OK** and the four-line stack reads cleanly at 160 px. Final.

## Files
- `cover/cover.html` (source; series template with the copper accent swap)
- `cover/cover.jpg` 1600x2560, 305485 bytes
- `cover/thumb-400.png`, `cover/thumb-160.png`

The Formatter must rebuild so the EPUB embeds this cover.
