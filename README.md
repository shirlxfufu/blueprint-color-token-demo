# Blueprint color token demo

[Open the interactive demo](https://shirlxfufu.github.io/blueprint-color-token-demo/)

Compare three semantic token approaches for transparent Blueprint fills, with editable light and dark values and a permanent first column showing Current Blueprint. Components have separate section headings; each sample shows its resulting background followed by the tokens and layers used to construct it.

This is an independent static GitHub Pages project. It has no dependency on the Blueprint icon comparison app. GitHub Pages publishes the repository root; no build or package installation is needed.

## Updating the demo

**Keep Current Blueprint as the first comparison column.** It must remain visible for every component, intent, theme, and approach selection. Approach checkboxes control only the three proposals. Do not remove or hide the reference during future simplification or layout changes. Its values remain independent of the token editor.

Update the HTML and JavaScript files on the default branch. Keep `index.html` and `method-comparison.html` synchronized. GitHub Pages redeploys automatically.

Earlier experiments remain archived in `surface-playground.html` and `opacity-comparison.html` and are no longer linked from the demo. `transparency-audit.md` records coverage and trial values.

## Reference license

`blueprint-reference.js` contains the published Blueprint Core 6.21.0 stylesheet and its Apache 2.0 license. Other Blueprint sources are linked in the comparison.
