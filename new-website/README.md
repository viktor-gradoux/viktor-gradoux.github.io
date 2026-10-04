# Viktor Gradoux — website (Quarto)

Render this folder with Quarto and the finished site is written to `../docs`,
the folder GitHub Pages publishes. Then commit and push.

In R (from the repository folder):

    quarto::quarto_preview("new-website")   # live preview while editing
    quarto::quarto_render("new-website")    # build into docs/

Or open `new-website/new-website.Rproj` in RStudio and use Build > Render Project.

What to edit:
- `index.qmd` about page (the biography is plain Markdown)
- `research.qmd` papers; each paper is one `<li class="pub">` block, talks go in its "Presented at" list
- `cv.qmd` CV page; replace `assets/files/cv.pdf` to update the CV
- `_includes/header.html` top menu, `_includes/footer.html` footer
- `assets/css/style.css` colours (top of file), type and layout
- `assets/files/Gradoux_Marcoux_Oil_Shipping_and_Pirates.pdf` the paper (keep the file name)

Do not render the old project at the repository root any more: it also writes to `docs/`.

Fonts: Newsreader and Instrument Sans (SIL Open Font License). Icons: Font Awesome Free (CC BY 4.0).
