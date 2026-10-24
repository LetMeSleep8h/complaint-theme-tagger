# Complaint Theme Tagger
Live page: https://aamirtechs.github.io/complaint-theme-tagger/

Tag complaints and bad reviews with the CFPB style theme taxonomy so ops can route root causes, not just apologise. The tagger is a transparent keyword baseline with matched keywords as evidence for every tag.

## Features
- Tag complaints and reviews with a CFPB style theme taxonomy for debt settlement, using transparent keyword rules you can read and edit.
- Multi-label tagging: one complaint can carry several themes, and every tag lists the matched keywords as evidence.
- Promise versus outcome sub-tag when a text contains both a promise phrase and an outcome complaint phrase.
- Per-theme counts and percentages, plus a theme by month trend when a date column exists.
- Download a tagged CSV with date, channel, text, themes and matched keyword evidence.
- Sample dataset is paraphrased synthetic complaints only. No real consumer data is used or needed.

## How it works
Paste complaints one per line or upload CSV with date, channel and text columns, edit the taxonomy JSON if needed, and run it. You get per-theme counts, a trend by month when dates exist, and a downloadable tagged CSV. It runs entirely in the browser.

## Privacy
Runs 100% in your browser. Your files never leave this device, nothing is uploaded,
and there is no tracking.

## Development
Core logic lives in `src/logic.js` and is shared by the page and the tests.
Run the tests with `npm test`.

## License
MIT, Copyright 2026 Amir Hussain.
