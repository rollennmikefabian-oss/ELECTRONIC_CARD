# THE MONDAY ARCHIVES — An Unexpected Delivery

A fully offline-capable, audio-free, responsive HTML/CSS/JavaScript appreciation experience for Ma’am Roan.

## Concept
A cinematic motorcycle courier delivers a parcel outside a house at night. Open the delivery to read the **original submitted letter itself as actual HTML source code**, within a syntax-highlighted editor. Each of the six original letter sections has its own chapter link. Lab 1 has a gentle golden highlight. At the end, replay the delivery.

## Files
- `index.html` — complete animation and archive interface
- `styles.css` — night illustration, responsive layout, subtle motion and code styling
- `script.js` — delivery, code editor, reading progress, chapters, copy/save/replay
- `letter-data.js` — exact submitted original HTML code encoded as a JavaScript string for reliable offline access
- `original-letter.html` — original letter file copied byte-for-byte, without rewriting, rearranging, or changing any text

## Opening the website
Unzip the folder, then open `index.html` in a browser. The site works via `file://` and GitHub Pages. No build tooling needed. Fonts are enhanced through optional Google Fonts, with local fallbacks for offline use.

## GitHub Pages
Upload all six files to the repository root. Enable GitHub Pages under Settings → Pages → Deploy from a branch → root. Open the resulting GitHub Pages URL.

## Original letter preservation
The original letter HTML is separately available as `original-letter.html`. `letter-data.js` includes its precise source text, not an invented code sample. Code editor decoration adds display spans only and does not modify original wording or HTML. Save .HTML downloads those original source characters.

## Accessibility
Keyboard-operable buttons, code that remains readable, reduced-motion compliance, no audio, small-screen chapter drawer, skip animation and typing controls.
