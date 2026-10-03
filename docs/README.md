# Viktor Gradoux — website (redesign)

Plain HTML and CSS, no build step and no external requests (fonts and icons are self-hosted).

- `index.html` about page, `research.html` papers, `cv.html`, `404.html`
- `assets/css/style.css` colours (top of file, light and dark), type and layout
- `assets/js/site.js` theme toggle, mobile menu, Abstract and BibTeX buttons
- `assets/files/` paper draft and CV; `assets/img/` pictures

To update the paper, replace `assets/files/Gradoux_Marcoux_Oil_Shipping_and_Pirates.pdf`
(keep the file name). To add a paper or a talk, edit the `<li class="pub">` blocks in `research.html`.

To put it live: GitHub Pages currently serves the Quarto output in `docs/`.
Either copy the contents of this folder into `docs/` (replacing the Quarto files), or
set Settings > Pages to serve this folder from a branch.

Fonts: Newsreader and Instrument Sans (SIL Open Font License). Icons: Font Awesome Free (CC BY 4.0).
