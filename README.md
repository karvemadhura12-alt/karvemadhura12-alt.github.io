# karvemadhura12-alt.github.io

Personal website of Madhura Karve, PharmD, an ScM candidate in Epidemiology (Clinical Trials and Evidence Synthesis) at the Johns Hopkins Bloomberg School of Public Health.

**Live site:** https://karvemadhura12-alt.github.io/

Built for JHU Biostat 776 (Statistical Computing) as the course's personal-website assignment, and maintained as a lightweight professional profile: background, skills and experience, what I hope to learn in the course, five fun facts, something I find cool, and how to reach me.

## How it's built

- [R Markdown](https://rmarkdown.rstudio.com/) with the [postcards](https://github.com/seankross/postcards) package, `trestles` template
- Icons via [fontawesome](https://rstudio.github.io/fontawesome/)
- Custom theme in `styles.css` (Inter + Cormorant Garamond, via Google Fonts) with subtle scroll-reveal animations in `footer.html`
- Hosted on [GitHub Pages](https://pages.github.com/) from the `gh-pages` branch

## Files

| File | Purpose |
|---|---|
| `index.Rmd` | Source for the site — edit this |
| `index.html` | Rendered page served by GitHub Pages — regenerate, don't hand-edit |
| `headshot.jpeg` | Profile photo (referenced by `image:` in the YAML header) |
| `styles.css` | Custom minimalist theme (typography, bullets, colors, motion) |
| `header.html` | Google Fonts link injected into `<head>` |
| `footer.html` | Small script for the fade-up-on-scroll and hero entrance animations |
| `.nojekyll` | Tells GitHub Pages to serve the HTML as-is, skipping Jekyll |
| `karvemadhura12-alt.github.io.Rproj` | RStudio project file |

Required packages: `install.packages(c("postcards", "fontawesome", "rmarkdown"))`.

## Contact

- Email: [mkarve1@jh.edu](mailto:mkarve1@jh.edu)
- LinkedIn: https://www.linkedin.com/in/madhura-karve/
- ORCID: https://orcid.org/0009-0008-9223-845X
