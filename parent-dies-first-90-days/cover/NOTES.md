# Cover notes: The First 90 Days After a Parent Dies

## Concept (series continuation, not a fresh design)
This is **Book Three of The Family Paperwork Series**, so `cover/cover.html` is a direct copy of `books/executor-guide/cover/cover.html` (itself a copy of Book 1) with only the accent swap and the text changed, exactly as the template header instructs:

- Book 1 estate-planning-beginners - `#e8b45c` gold
- Book 2 executor-guide - `#d9814e` copper
- **Book 3 parent-dies-first-90-days - `#8fbdd0` slate blue (this book)**

Slate blue is the accent the series template already reserved for Book 3, and it is clearly distinct from both siblings: gold and copper are warm and heavy, this is cool and light, so the three thumbnails never read as the same book.

Unchanged from Books 1 and 2: forest ground (`#14332a` to `#1e4a3a`), 212 px top band and 280 px bottom band, the line-art folder with signed papers and the accent "done" check, Georgia title over Segoe UI support type, the 300x14 accent rule, and all margins. The top band reads "Book Three".

Because slate blue is a *light* accent (unlike Book 2's darker copper), `--bandink` returns to Book 1's `#14332a` ground colour for the band text instead of Book 2's `#0f2a21`.

## Title treatment
Four lines, the series cap. "THE FIRST" is the cream Segoe kicker, "90 DAYS" and "PARENT DIES" are the Georgia caps, and "AFTER A" is the slate-blue sans line that does the connecting work "STEP-BY-STEP" does in Book 2. Text matches `book.json` exactly: title split as The First / 90 Days / After a / Parent Dies, the shortened cover subtitle, author Ruth Calloway. The numeral "90" is the strongest shape on the cover, which is the point - the promise is a finite window.

## Self-critique (final, render 3)
| Criterion | Score | Note |
|---|---|---|
| Thumbnail legibility at 160 px | 9 | "90 DAYS" holds as one dense cream block and "PARENT DIES" as a second; the slate bands anchor top and bottom; the folder stays a readable silhouette. |
| Genre signal | 9 | Deep green plus serif caps plus the folder of signed papers reads bereavement-paperwork immediately, and matches the two siblings on the shelf. |
| Distinctiveness | 8 | Green ground and folder motif stay clear of the soft-focus candle-and-flower look common in grief titles, and the cool accent separates it from Books 1 and 2. |
| Professionalism | 9 | Series-identical geometry, one type pairing, hand-drawn SVG, renderer reports all text inside the 60 px safe area. |
| Emotional pull | 9 | A number with an end date is reassuring to someone in the first week; the cover promises the job is finite and already mapped. |

Contrast: cream `#f7f3e8` on `#14332a` ground is far past 4.5:1; `#14332a` on slate blue `#8fbdd0` is past 4.5:1; the `#c4dbcb` subtitle at 66 px clears the large-text threshold.

## Iterations (3 renders, all with `cover.mjs`)
1. Three-line stack with a 280 px serif and "AFTER A PARENT DIES" on one sans line - **Layout OK**, but the sans tail line was long and thin and the title stack lost the series rhythm.
2. Split to the series four-line stack at 232 px serif - **failed**: "title outside safe area", "Parent Dies is too wide".
3. Serif to 186 px (series-matching), kicker 78 px and sans tail 112 px to match Book 2 exactly - **Layout OK**. Final.

## Files
- `cover/cover.html` (source; series template with the slate-blue accent swap)
- `cover/cover.jpg` 1600x2560, 296079 bytes
- `cover/thumb-400.png`, `cover/thumb-160.png`

The Formatter must rebuild so the EPUB embeds this cover.
