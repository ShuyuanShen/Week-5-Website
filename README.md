# Quarto personal website starter
1. Open Website.Rproj in RStudio.
2. Replace the sample text in index.qmd, about.qmd, and projects.qmd.
3. In the project Terminal run: quarto preview
4. Before publishing run: quarto render
5. Commit source and docs output, then push to your public GitHub repository.
6. Repository Settings > Pages > Deploy from a branch > main > /docs.
7. Check the public URL and all pages. After editing, render, commit, and push again.

The empty .nojekyll file belongs in the rendered docs folder. The configuration copies it as a project resource.
No R code is required by this starter. Use only content you intend to share.
Official guide: https://quarto.org/docs/publishing/github-pages.html
Gallery entries are inspiration; check any template's license before copying it.
